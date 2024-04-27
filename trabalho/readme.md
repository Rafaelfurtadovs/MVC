### Nome do projeto
Projeto abandono zero
### Descrição
O projeto será um site de formulário para uma pesquisa sobre abandono e adoção de animais, O site contará com um formulário e uma aba de estatisticas para o ADM visualizar oque foi respondido.
### Arquitetura MVC

<img src="assets/MVCCcc.png">

### Ferramenta de Diagramação
Draw.IO
### Models
-Users: É responsável pela parte de dados dos usuários que responderão o formulário

-Formulário: É responsáver pelos dados preenchidos no formulário e é relacionado com o ADM

-Stats: É responsável pelos dados das estatisticas do formulário.
### Controllers 
-ADM:O adm é quem tem total acesso ao formulário

-Tutor: o Tutor é quem responde o formulário

### Views

Tela inicio: tela inicial do formulário, ela te introduz ao site.

-Login: tela de login

-Formulário: formulário em sí com perguntas e respostas

-Adm: tela de acessdo do admin

-Fim: tela de formulário preenchido

### Infraestrutura

API: Sails

Banco de dados: PostgreeSQL