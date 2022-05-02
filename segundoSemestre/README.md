## Sobre o projeto
No segundo semestre, tivemos como empresa parceira a [IACIT](https://www.iacit.com.br/), de modo que os mesmos contribuíram junto aos professores para a elaboração do problema a ser resolvido pelos alunos.
O problema proposto foi a elaboração de uma aplicação **desktop** que auxiliá-se motoristas de caminhão durante sua jornada, servindo como principal meio de comunicação entre os usuários (motoristas) e empregadores, sinalizando problemas, situações e notificações entre eles, além de registrar as horas trabalhadas pelos motoristas.
De forma mais detalhada, a aplicação oferece:
- Cadastro dos motoristas
- Cadastro das empresas
- Cadastro dos veículos
- Emissão de avisos/notificações da empresa para os motoristas
- Emissão de avisos/notificações do motorista para a empresa
- Registro de atividades do motorista:
  - Registro de horas trabalhadas
  - Registro de horas descansadas
  - Registro de tempo de almoço
- Emissão de relatórios estatísticos sobre os motoristas

#### Níveis de acesso da aplicação
A aplicação oferece três níveis de acessos distintos aos usuários, cada um apresentando, aos mesmos, funcionalidades específicas de interesse do perfil

**Motorista:** Motoristas tem acesso a sua jornada/viagem atual, que são atribuídas pelos **Supervisores**. Ao entrar com este perfil de acesso, o motorista poderá acionar o início de sua jornada de trabalho para ser registrada no sistema, parar para almoço e descanso e notificar sobre a conclusão da sua viagem. Também podem enviar avisos para os supervisores sobre algum imprevisto na sua jornada.

<img src="https://github.com/Syank/PI-JornadaDeMotoristas/blob/master/doc/apresentacao_entrega_4/GIFS%20entrega%20final/GIF%20Motorista.gif" width="500"/>

**Supervisores**: Supervisores podem alterar as informações dos veículos e motoristas cadastrados na aplicação pelos **Administradores**, atribuir viagens aos motoristas e verificar a situação de cada uma delas. Eles também tem acesso a área de notificações do sistema, podendo visualizar e emitir novos avisos para os usuários da plataforma.

<img src="https://github.com/Syank/PI-JornadaDeMotoristas/blob/master/doc/apresentacao_entrega_4/GIFS%20entrega%20final/GIF%20Supervisor.gif" width="500"/>

**Administradores**: São os usuários com maior poder de acesso à plataforma, eles podem criar, alterar e excluir qualquer dado na plataforma, visualizar as notificações do sistema, emitir notificações e também contam com acesso a área de emissão de relatórios sobre as estátisticas da situação dos motoristas em viagem.

<img src="https://github.com/Syank/PI-JornadaDeMotoristas/blob/master/doc/apresentacao_entrega_4/GIFS%20entrega%20final/GIF%20Administrador.gif" width="500"/>


***O repositório oficial do projeto pode ser acessado pelo link a seguir: https://github.com/Syank/PI-JornadaDeMotoristas***


## Tecnologias Utilizadas
Para este projeto, utilizamos as seguintes tecnologias:
- **Java**: Como um dos requisitos exigidos para elaborar o projeto, utilizamos a linguagem Java para a criação da aplicação
- **JavaFX**: Framework utilizada para a criação da interface gráfica (GUI) para exibição ao usuário
- **CSS**: Graças à framework JavaFX, é possível utilizar CSS para estilizar as interfaces
- **Hibernate**: Utilizado para realizar a persistência de dados da aplicação no banco de dados através de ***ORM***
- **PostgreSQL**: Banco de dados relacional exigido como requisito

## Contribuições Pessoais
Na equipe, assumi o papel de *Scrum Master*, dessa forma, fui responsável por representar a equipe durante as reuniões e apresentações, bem como ajudar a gerênciar as atividades e objetivos da equipe.
Na parte de desenvolvimento, contribuí na elaboração da interface gráfica, tanto na prototipação quanto na codificação final. Participei da configuração do projeto em questão às suas dependências e configuração do **Hibernate** para a persistência de dados. Auxiliei no design e planejamento do banco de dados.

## Hard Skills
No quesito de hard skills, neste semestre tive o primeiro contato com Java e Bancos de dados relacionais, assim, aprendi o suficiente para desenvolver de forma eficaz o projeto, levando em conta os requisitos estabelecidos.
Específicamente, em Java, aprendi a estruturar um projeto, a sintaxe básica da linguagem, noções de threads, bibliotecas e dependências e integração ao banco de dados através do ORM oferecido pelo **Hibernate**.
Já com relação ao banco de dados relacional, tive o primeiro contato também com PostgreSQL, aprendi a elaborar queries básicas, relacionamento e integridade dos dados e a configuração básica do mesmo.

## Soft Skills
Como desempenhei o papel de *master*, tive a oportunidade de exercitar as soft skills de gestão de equipes, planejamento de sprints e resolução de conflitos entre os integrantes do projeto.
Como neste semestre tivemos contato com um cliente real, também pude desenvolver as noções de levantamento de requisitos para o projeto e como gerir a equipe de forma adequada a cumprir os objetivos de cada entrega a ser realizada.
