## Sobre o projeto
Para o projeto do sexto semestre, a empresa parceira foi a [Visiona](https://www.visionaespacial.com.br/).
O desafio proposto foi dar continuidade ao projeto desenvolvido por outra turma, o [eSoja](https://github.com/cluster-8/esoja-mobile).
Este projeto é um aplicativo móvel que fornece funcionalidades focadas para usuários donos de talhões de soja, onde o maior foco é registrar os estágios das plantações e calcular estimativas de produção.

Uma das funcionalidades é o registro de amostras das plantações, para que sejam feito os cálculos de estimativa de produção.

Na versão original, essa funcionalidade exige que o usuário fotografe previamente as plantas que serão utilizadas como amostras e informe a quantia de grãos de cada amostra. Dessa forma, o usuário precisa manualmente realizar a contagem dos grãos das plantas, o que resulta em muito tempo perdido.

Com isso, foi pedido à equipe que realizasse um ajuste nessa funcionalidade, de forma que o usuário não precise mais contar os grãos, apenas enviar as imagens, e com a ajuda de uma IA de segmentação de imagens, realizar a contagem dos grãos de cada planta.

Abaixo está um GIF exibindo a funcionalidade de reconhecimento implementada:

<img src="https://github.com/barbaraport/softtelie-ehsoja/blob/main/docs/MVPs/sprint_3/ehSoja-Sprint-3.gif" width="500"/>

***O repositório oficial do projeto pode ser acessado pelo link a seguir: https://github.com/barbaraport/softtelie-ehsoja***


## Tecnologias Utilizadas
Para este projeto, utilizamos as seguintes tecnologias:
- Python: Linguagem utilizada para construir o servidor REST da aplicação e codificar a IA a ser utilizada para analisar as imagens
- Flask: Mini framework utilizada no servidor para fornecer decoradores para criação de serviços REST
- PostgreSQL: Banco de dados relacional usado para a persistência de dados usados pela aplicação
- TypeScript: Linguagem utilizada para construir a aplicação do cliente, tanto mobile quanto web
- React-Native: Framework utilizada para criação de aplicativos mobile de múltiplas plataformas, utilizando tecnologias web
- Webpack: Utilizado para empacotes módulos de tecnologia web e gerar a aplicação final


## Contribuições Pessoais
Neste projeto fui o *product owner*, o representante da equipe frente ao cliente e responsável por criar o backlog e requisitos para o desenvolvimento do projeto, bem como também participante do desenvolvimento em si.

O maior desafio desse projeto foi, sem dúvidas, o entendimento de como criar uma IA capaz de reconhecer elementos nas imagens e treina-lá.
Participei ativamente desse desenvolvimento, pesquisando métodos de realizar a implementação da IA, como treina-la, melhorar sua eficácia e integrar isso com o projeto.

Na parte do nosso servidor Flask, onde se encontra os serviços para acessar a IA, fui responsável por criar a arquitetura de organização do código para que os membros da equipe pudessem desenvolver seguindo padrões de projeto que ajudassem na resolução de nossos problemas.

O projeto original é dividido em duas partes, o *cliente*, desenvolvido em *React-Native*, e o *servidor* do cliente, desenvolvido em *Node*.

No *cliente* fui responsável por realizar os ajustes das interfaces envolvidas para que ficassem adequadas à nova funcionalidade.
No *servidor* realizei ajustes para que fizesse chamadas ao serviços *Python* e utilizasse os serviços relacionados à IA.

Sobre a IA, utilizamos a framework *Tensorflow* para realizar a criação do modelo de segmentação, com a implementação Mask-RCNN, onde um modelo pré-treinado já foi fornecido pela biblioteca, o que facilitou o desenvolvimento do modelo.

Nessa parte, contribuí com EDA do modelo, sugerindo e propondo soluções para como fazer o pré-processamento das imagens fornecidas para o treinando e como realizar o *data augmentation* sobre a base de dados.


## Hard Skills
Aqui, para fins de organização, é possível dividir as hard skills desenvolvidas entre front-end e back-end

Front-end:
- React-Native: Framework para criação de aplicativos mobile multiplataforma com tecnologias web | Sei fazer com auxílio de consulta
- TypeScript: Super-conjunto da linguagem JavaScript, com tipagem | Sei fazer autonomia
- Webpack: Criador de módulos de tecnologias web | Sei fazer com auxílio de consulta


Back-end:
- Python: Linguagem utilizada para a construção do servidor das aplicações | Sei fazer com autonomia
- Tensorflow: Framework utilizada para criação de modelos de IA | Sei fazer com autonomia
- Serviços REST: Criação de um servidor fornecedor de serviços *REST* | Sei fazer com autonomia
- Persistência de dados: Utilização de um Banco relacional (PostgreSQL) para a persistência dos dados | Sei fazer com autonomia

## Soft Skills
Como desempenhei o papel de *product owner*, tive a oportunidade de exercitar as soft skills de desenvolvimento de backlog, planejamento de sprints e organização de tarefas.
