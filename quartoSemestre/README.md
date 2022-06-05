## Sobre o projeto
Para o projeto do quarto semestre, a empresa parceira foi a [Embraer](https://embraer.com/br/pt).
O desafio proposto, desta vez, foi baseado em um problema real da empresa. O problema era de que na empresa, toda aeronave produzida possuí um manual de seu operamento e de como funcionam suas peças, contúdo, esse manual é criado, mantido e atualizado de forma manual, através de planilhas. Além de tomar muito tempo por se tratar de algo complexo, também possibilita muitas chances de erros surgirem.

Dessa forma, a solução para o problema foi a elaboração de uma aplicação desktop, que se comunique com um servidor interno, para que todos os usuários possam acessar os manuais e gerarem suas modificações de forma simples, rápida e automatizada.

Os manuais possuem uma *codelist* que descreve como devem ser montados a partir de fragmentos de arquivos PDFs. Nossa aplicação oferece uma forma simples de se manipular a codelist e refletir diretamente no manual gerado no final.

Por se tratar de uma solução que será aplicada em um sistema já em andamento, foi necessário adicionar funcionalidades ao mesmo de forma com que suporte a importação das codelists, arquivos e manuais já gerados pelo método manual antigo, para que possam ser integrados e migrados para a métodologia nova que a aplicação oferece, mantendo assim a compatibilidade necessária.

Abaixo está um GIF exemplificando a aplicação

<img src="https://github.com/Syank/AirplaneDocGenerator/blob/main/doc/gifs/sprint4/Apresenta%C3%A7%C3%A3o%20Sprint%204%20GIF.gif" width="500"/>

***O repositório oficial do projeto pode ser acessado pelo link a seguir: https://github.com/Syank/AirplaneDocGenerator***


## Tecnologias Utilizadas
Para este projeto, utilizamos as seguintes tecnologias:
- Java: Linguagem utilizada para construir o servidor REST da aplicação
- Spring Boot: Framework utilizada no servidor para fornecer anotações para criar controladores, mapear entidades ORM e mais funcionalidades úteis
- PostgreSQL: Banco de dados relacional usado para a persistência de dados
- JavaScript: Linguagem utilizada para construir a aplicação do cliente
- React: Biblioteca para criar a interface do usuário utilizando o padrão de componentização dos elementos HTML, utilizando a extensão JSX do JavaScript para a definição desses componentes
- Tailwind: Biblioteca para definição, agrupamento e reaproveitabilidade de estilos CSS, para personalizar a aplicação
- Electron: Framework utilizada para criar aplicações desktop com tecnologias web

## Contribuições Pessoais
Assumi o papel de *Product Owner* na equipe, desta forma fui capaz de ter contato direto com o cliente e ralizar o levantamento de requisitos para o desenvolvimento do projeto, bem como também planejar as sprints e as suas respectivas entregas.

Na parte de desenvolvimento, assim como nos projetos passados, ajudei fortemente na montagem e configuração do ambiente de desenvolvimento, tanto do servidor quanto do cliente. Participei da modelagem do banco de dados, no mapeamento das entidades ORM. Tive grande participação também na condificação da aplicação do cliente, sendo uma considerável parte da interface ter sido feita por mim.

## Hard Skills
Aqui, para fins de organização, é possível dividir as hard skills desenvolvidas entre front-end e back-end

Front-end:
- HTML: Organização e estruturação de páginas web | Sei fazer com autonomia
- Tailwind: Biblioteca para abordar estilos CSS de forma extremamente reutilizável | Sei fazer com auxílio de consulta
- Web Components: Tecnologia web nativa que permite a criação de **TAGs HTML** reaproveitáveis | Sei fazer com auxílio de consulta


Back-end:
- Padrão de projeto: Estruturação de um projeto no padrão ***MVC*** | Sei fazer com autonomia
- Serviços REST: Criação de um servidor fornecedor de serviços *REST* | Sei fazer com autonomia
- Persistência de dados: Utilização da estrutura ORM para acesso a dados através do padrão de *repositórios*. Recurso facilitado graças à framework Spring Boot | Sei fazer com autonomia

## Soft Skills
Por ter sido o *Product Owner*, tive a oportunidade de aprender como realizar o levantamento de requisitos diretamente com o cliente, como entender e atender suas necessidades, propondo soluções que não haviam sido imaginadas antes e como me relacionar de forma correta com ele.
