# Tutorial de Instalação e Uso do Sphinx com Furo

Guia de instalação e configuração do Sphinx com o tema Furo para documentar seu projeto. Ele também inclui informações sobre como configurar o MyST-Parser para permitir a utilização de arquivos Markdown na documentação.

<figure style="display: inline-block;">
  <img src="/source/imgs/sphinx-logo.png" alt="sphinx logo">
  <figcaption style="text-align: center;">Logo Sphinx</figcaption>
</figure>

## Passos para Instalação e Configuração

### 1. Criar e Ativar um Ambiente Virtual

Primeiro, crie um ambiente virtual para isolar as dependências do seu projeto.

```bash
$ python -m venv docs_petacademy_env
$ source docs_petacademy_env/Scripts/activate  # No Windows
$ source docs_petacademy_env/bin/activate  # No Linux/Mac
```

### 2. Instalar Sphinx e Furo

Com o ambiente virtual ativo, instale o Sphinx e o tema Furo.

```bash
(docs_petacademy_env) $ pip install sphinx furo
```

### 3. Iniciar um Novo Projeto Sphinx

Use a ferramenta `sphinx-quickstart` para iniciar um novo projeto Sphinx. Siga os prompts para configurar seu projeto.

```bash
(docs_petacademy_env) $ sphinx-quickstart
```

Durante a configuração, você pode usar as seguintes opções:

```
Welcome to the Sphinx 7.3.7 quickstart utility.

> Separate source and build directories (y/n) [n]: y

The project name will occur in several places in the built documentation.
> Project name: docs-petacademy
> Author name(s): petsimc
> Project release []: \\ aqui pode-se colocar a versão da documentação (ex: v1.2; v2; v3.1)

If the documents are to be written in a language other than English, you can select a language here by its language code. Sphinx will then translate text that it generates into that language.
> Project language [en]: pt_BR

```

### 4. Configurar o Tema Furo

Instale o tema Furo e configure-o no arquivo `conf.py`.

```bash
(docs_petacademy_env) $ pip install furo
```

No arquivo `conf.py`, atualize a configuração do tema:

```python
html_theme = "furo"
```

### 5. Instalar e Configurar o MyST-Parser

Instale o MyST-Parser para permitir o uso de arquivos Markdown na documentação.

```bash
(docs_petacademy_env) $ pip install --upgrade myst-parser
```

Em seguida, adicione `'myst_parser'` à lista de extensões no arquivo `conf.py`:

```python
extensions = [
    'myst_parser',
]
```

### 6. Construir a Documentação

Para construir a documentação em HTML, use o comando apropriado para o seu sistema operacional:

No Windows:
```bash
(docs_petacademy_env) $ ./make.bat html
```

No Linux/Mac:
```bash
(docs_petacademy_env) $ make html
```

## Usando Diferentes Tipos de Arquivos na Documentação

O Sphinx permite o uso de diferentes tipos de arquivos para a documentação, incluindo reStructuredText (.rst), Markdown (.md) e HTML. No entanto, para padronizar e facilitar a manutenção, estamos focando no uso de arquivos Markdown (.md).

Dentro dos arquivos Markdown, você pode incluir HTML para adicionar elementos personalizados. Por exemplo:

```markdown
# Título do Artigo

Este é o conteúdo do seu artigo. 

<figure style="display: inline-block;">
  <img src="/source/imgs/sphinx-logo.png" alt="sphinx logo">
  <figcaption style="text-align: center;">Logo Sphinx</figcaption>
</figure>
```

## Tutorial Simples de Markdown

Aqui estão alguns dos elementos básicos do Markdown que você pode usar em sua documentação:

### Títulos

Use `#` para títulos. Adicione mais `#` para sub-títulos.

```markdown
# Título Principal
## Sub-título
### Sub-sub-título
```

### Ênfase

Use `*` ou `_` para itálico e `**` ou `__` para negrito.

```markdown
*Itálico* ou _Itálico_

**Negrito** ou __Negrito__
```

### Listas

Use `-` ou `*` para listas não ordenadas e números para listas ordenadas.

```markdown
- Item 1
- Item 2
  - Sub-item

1. Primeiro item
2. Segundo item
   1. Sub-item
```

### Links

Use `[texto](url)` para links.

```markdown
[Documentação do Sphinx](https://www.sphinx-doc.org/)
```

### Imagens

Use `![texto alternativo](caminho-da-imagem)` para imagens.

```markdown
![Logo Sphinx](https://www.sphinx-doc.org/en/master/_static/sphinx.png)
```

## Conclusão

Seguindo estes passos, você terá uma documentação configurada com Sphinx utilizando o tema Furo e suporte para arquivos Markdown. Agora você pode adicionar mais conteúdo ao seu projeto, modificar o arquivo `index.rst` para incluir seus documentos e personalizar sua documentação conforme necessário.

## Recursos Adicionais

- [Documentação do Sphinx](https://www.sphinx-doc.org/)
- [Tema Furo](https://pradyunsg.me/furo/)
- [MyST-Parser](https://myst-parser.readthedocs.io/)

