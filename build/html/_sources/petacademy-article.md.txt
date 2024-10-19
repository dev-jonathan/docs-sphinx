# PETACADEMY: PLATAFORMA DE CURSOS

## Resumo

O PETSIMC está desenvolvendo o PetAcademy, uma inovadora plataforma educacional da Universidade Federal de Uberlândia (UFU). Este projeto busca oferecer educação de alta qualidade, gratuita e acessível, inicialmente voltada à programação e tecnologia da informação, com planos de expansão para diversas áreas de conhecimento. Seu design responsivo garante adaptabilidade a diversos dispositivos, e sua natureza baseada na web elimina barreiras técnicas. As funcionalidades da plataforma incluem visualização de informações dos cursos, sistema de chat interativo, gestão de cursos e conteúdo, e avaliação com certificação autenticada. A infraestrutura tecnológica é fundamentada em ferramentas consolidadas, como Firebase e NodeJS, e a metodologia de conteúdo segue os padrões da universidade. A implementação do PetAcademy promete beneficiar amplamente a comunidade educacional, reforçando o compromisso meio acadêmico com a inovação e a difusão do conhecimento. Esta iniciativa exemplifica o poder da tecnologia em democratizar a educação e criar oportunidades de aprendizado acessíveis.

## 1. Introdução

O PetAcademy, em desenvolvimento pelo PETSIMC, surge como uma plataforma educacional promissora na Universidade Federal de Uberlândia (UFU). Este projeto em progresso visa ser um meio proeminente de aprendizado, não apenas para os estudantes de Sistemas de Informação, mas também para estudantes de diferentes áreas, tanto da comunidade interna quanto externa à UFU. Assim, promove uma disseminação multifacetada do conhecimento de forma gratuita e aberta, onde qualquer pessoa pode acessar as videoaulas, concluir exercícios, tirar dúvidas e obter certificação.

## 2. Objetivos

Este projeto em evolução tem como meta mitigar taxas de reprovação e desistência ao oferecer um ambiente de aprendizagem abrangente e enriquecedor. Diante de desafios educacionais, as metodologias de ensino inovadoras, especialmente aquelas que fazem uso de b-learning e ferramentas digitais, têm sido fundamentais para manter padrões de qualidade no ensino universitário (Ruiz et al., 2021). O principal objetivo da PetAcademy é diversificar e democratizar o aprendizado, tornando-o acessível tanto para a comunidade interna quanto para a externa da UFU, além de promover a interação entre diversos campos do saber. A missão principal da PetAcademy é oferecer educação de alta qualidade, gratuita e acessível, com foco inicial em programação e tecnologia da informação, mas com planos de expandir para outras disciplinas e áreas do conhecimento.

## 3. Estado Atual e Desenvolvimento Continuado

O estágio presente do PetAcademy é marcado por uma fase intensiva de desenvolvimento. A equipe está dedicando esforços significativos para finalizar as funcionalidades e otimizar a experiência do usuário, assegurando que a plataforma atenda às necessidades educacionais de maneira eficaz e intuitiva. Enquanto o desenvolvimento e a criação inicial de conteúdo são realizados pelo PETSIMC, já está disponível a funcionalidade que permite a outros grupos PET se cadastrarem e tornarem-se criadores de conteúdo para a plataforma. Esta adição amplia o alcance e a diversidade do material didático oferecido.

## 4. Adaptabilidade e Acessibilidade Web

A adaptabilidade do sistema às diversas dimensões de tela, independentemente do dispositivo, é um aspecto crítico na era digital. A plataforma PetAcademy foi desenvolvida para ser responsiva, o que implica que seu design foi otimizado para assegurar uma visualização adequada e uma interação eficaz em dispositivos variados, desde computadores desktop até smartphones. Esta característica é essencial, considerando a diversidade de dispositivos utilizados no contexto educacional contemporâneo. A natureza baseada na web da plataforma simplifica a acessibilidade ao conteúdo. Ao ser hospedada na web, a PetAcademy elimina a necessidade de softwares específicos, permitindo o acesso via qualquer navegador padrão. Este aspecto facilita o engajamento dos alunos, uma vez que elimina potenciais barreiras técnicas.

## 5. Funcionalidades do Sistema

Mesmo em desenvolvimento, a plataforma já apresenta uma estrutura intuitiva e de fácil navegação. Os usuários podem visualizar informações detalhadas sobre os cursos disponíveis, os professores responsáveis e os módulos que compõem cada curso, bem como suas videoaulas, materiais de apoio em texto e chat para tirar dúvidas.

<figure style="display: inline-block;">
  <img src="/source/imgs/site-diferentes-telas.png" alt="Representação do site em diferentes dispositivos">
  <figcaption style="text-align: center;">Figura 1 - Representação do site em diferentes dispositivos</figcaption>
</figure>

### 5.1 Login e Acesso

Os usuários podem acessar facilmente a plataforma utilizando diferentes métodos de login, como e-mail, senha ou conta Google, garantindo assim um acesso descomplicado aos recursos educativos.

<figure style="display: inline-block;">
  <img src="/source/imgs/login.png" alt="Figura 2 - Tela de login">
  <figcaption style="text-align: center;">Figura 2 - Tela de login</figcaption>
</figure>

### 5.2 Interatividade e Comunicação

O ambiente de aprendizagem é potencializado por um sistema de chat interativo, permitindo discussões, esclarecimento de dúvidas e sugestões sobre os temas abordados, utilizando a renomada plataforma Disqus, que possui políticas eficientes contra spam e comentários ofensivos, além de várias funcionalidades de gerenciamento de comentários.

<figure style="display: inline-block;">
  <img src="/source/imgs/chat.png" alt="Figura 3 - Chat das aulas">
  <figcaption style="text-align: center;">Figura 3 - Chat das aulas</figcaption>
</figure>

### 5.3 Gestão de Cursos e Conteúdo

Membros do Programa de Educação Tutorial, incluindo grupos PET além do PETSIMC, têm privilégios adicionais na plataforma, podendo criar, alterar e excluir cursos. Esta funcionalidade não só permite uma constante atualização e diversificação dos conhecimentos oferecidos na plataforma, como também incentiva a colaboração interdisciplinar e a contribuição de diversos especialistas no domínio acadêmico.

### 5.4 Avaliação e Certificação

A avaliação rigorosa por meio de questionários e a exigência de uma média mínima de 60% de acertos para certificação asseguram a credibilidade dos cursos. A automação na emissão de certificados é realizada por meio da integração com a plataforma PetCert, desenvolvida pelo PETSIMC, validando ainda mais a autenticidade e legitimidade dos certificados emitidos.

<figure style="display: inline-block;">
  <img src="/source/imgs/petcert.png" alt="Figura 4 - PetCert, componente que automatiza os certificados">
  <figcaption style="text-align: center;">Figura 4 - PetCert, componente que automatiza os certificados</figcaption>
</figure>

## 6. Tecnologias Empregadas

A infraestrutura tecnológica da PetAcademy é fundamentada em ferramentas e tecnologias consolidadas no mercado de desenvolvimento web:

- Firebase Hosting: Utilizado para a hospedagem da plataforma, garante estabilidade e velocidade no carregamento dos conteúdos.
- Firebase Authentication: Responsável pelo sistema de autenticação de usuários, é empregado para garantir a segurança e integridade das informações de acesso dos usuários.
- Firebase Realtime Database: Esta base de dados em tempo real é empregada para facilitar a dinâmica de interações na plataforma, desde a administração de cursos até comunicações em tempo real.
- Tecnologias de Front-end: JS, CSS e HTML são os pilares da construção da interface da PetAcademy. O uso de técnicas de design responsivo e acessível, como as delineadas por Baker (2014), e do framework Bootstrap garante uma padronização e adaptabilidade do design, tornando a plataforma acessível em diferentes dispositivos.
- Backend com Vercel e NodeJS: A estrutura de back-end foi desenvolvida em NodeJS e é hospedada pela Vercel, proporcionando um sistema eficiente em termos de processamento e resposta às solicitações.
- GitHub: A plataforma GitHub é empregada para o versionamento do código, garantindo a organização das versões do projeto e facilitando a colaboração entre os desenvolvedores envolvidos (Spinellis, D. (2012)).
- Trello: No âmbito do gerenciamento de projetos, o Trello é usado para acompanhar o desenvolvimento das tarefas, estabelecer metas e coordenar a equipe em relação a prazos e responsabilidades.

Ao combinar estas tecnologias, a PetAcademy estabelece um fundamento robusto que atende às necessidades atuais do campo educacional, mantendo a capacidade de adaptação a futuras demandas e melhorias.

## 7. Metodologia e Estrutura de Conteúdo

Os cursos são meticulosamente planejados, referenciando os planos de ensino da UFU e abrangendo tópicos cruciais em diversas áreas. Cada curso é estruturado em módulos, com aulas em vídeo, textos de apoio, links e materiais variados, proporcionando uma aprendizagem multifacetada e abrangente.

## 8. Impacto e Contribuições

A implementação da PetAcademy promete gerar um impacto significativo na comunidade educacional, servindo como um recurso valioso para estudantes, educadores e aprendizes autodidatas. O projeto visa beneficiar não só a comunidade da UFU, mas também proporcionar oportunidades de aprendizagem para indivíduos em todo o mundo.

## 9. Conclusão

A PetAcademy representa um avanço significativo na promoção da educação e na difusão do conhecimento na Universidade Federal de Uberlândia. Com sua interface amigável, variedade de cursos e sistema robusto de certificação, a plataforma tem o potencial de impactar positivamente a vida de estudantes e indivíduos interessados em expandir seus horizontes educacionais, reafirmando o compromisso da universidade com a inovação educacional e a disseminação do saber. Este projeto é um exemplo eloquente de como a tecnologia pode ser utilizada para superar barreiras educacionais e criar oportunidades de aprendizagem acessíveis, contribuindo para a construção de uma sociedade mais informada e educada.

## 10. Agradecimentos

Expressamos nossa profunda gratidão a todos os colaboradores, mentores e desenvolvedores que estão contribuindo para a realização deste projeto, superando obstáculos e criando oportunidades de aprendizagem acessíveis para uma sociedade mais informada e educada, dedicaram seu tempo e esforço.

## Referências

- Baker, S. (2014). Making It Work for Everyone: HTML5 and CSS Level 3 for Responsive, Accessible Design on Your Library's Web Site. Journal of Library & Information Services in Distance Learning, 8, 118 - 136. [DOI: 10.1080/1533290X.2014.945825](https://doi.org/10.1080/1533290X.2014.945825).

- Spinellis, D. (2012). Git. IEEE Software, 29, 100-101. https://doi.org/10.1109/ms.2012.61.
