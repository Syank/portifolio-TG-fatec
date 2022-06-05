## Sobre o projeto
Para o projeto do quarto semestre, a empresa parceira foi a [Embraer](https://embraer.com/br/pt).
O desafio proposto, desta vez, foi baseado em um problema real da empresa. O problema era de que na empresa, em certas ocasiões, certas aeronaves produzidas, podem necessitar de ajustes após sua manufatura, resultando em **recalls** aos seus clientes.

Cada recall é definida em um arquivo PDF chamado FOL, onde contêm a descrição do problema, o equipamento (avião) pertinente e o que deve ser feito pelo cliente.

O maior problema para a empresa em si é manter seus clientes atualizados e informados sobre essas recalls. Para isso, a solução oferecida foi a criação de um aplicativo mobile que notifique os clientes sobre novos avisos relacionados aos seus aviões.

O aplicativo desenvolvido fornece aos usuários as seguintes funcionalidades:

- Acesso por meio de um registro já existente da empresa de seus clientes;
- Visualização da sua lista de equipamentos (aviões)
- Notificações sobre novas FOLs
- Visualização das FOLs

A solução oferecida também contêmpla uma interface web, onde administradores tem acessos à informações de localização dos clientes que visualização uma FOL e que utilizaram o aplicativo.

Abaixo está um GIF exemplificando a aplicação

<img src="https://github.com/barbaraport/api-claradb/blob/main/docs/media/gifs/Sprint%203.gif" width="500"/>

***O repositório oficial do projeto pode ser acessado pelo link a seguir: https://github.com/barbaraport/api-claradb***


## Tecnologias Utilizadas
Para este projeto, utilizamos as seguintes tecnologias:
- Python: Linguagem utilizada para construir o servidor REST da aplicação e realizar manipulação de dados de entrada fornecidos pelo cliente
- Flask: Mini framework utilizada no servidor para fornecer decoradores para criação de serviços REST
- MongoDB: Banco de dados não relacional usado para a persistência de dados usados pela aplicação
- TypeScript: Linguagem utilizada para construir a aplicação do cliente, tanto mobile quanto web
- React-Native: Framework utilizada para criação de aplicativos mobile de multiplas plataformas, utilizando tecnologias web
- Webpack: Utilizado para empacotes módulos de tecnologia web e gerar a aplicação final


## Contribuições Pessoais
Neste projeto fui o *master*, o representante da equipe em reuniões e apresentações, bem como também participante do desenvolvimento em si.
Configurei e dei manutenção nas configurações do *webpack* de nosso projeto, desenvolvi serviços em Python no servidor para serem acessados por nessas aplicações clientes (mobile e web).
Participei ativamente do desenvolvimento da aplicação mobile, criando interfaces, regras de negócios e funcionalidades para o aplicativo.
Na parte de dados e sua persistência, elaborei o algoritmo responsável por fazer a portabilidade dos dados mockados a serem usados fornecidos pelo cliente para o banco de dados MongoDB que utilizamos.
Fiz uso e implementei a biblioteca ***Watchdog***, em Python, responsável por ouvir modificações em arquivos. Fez-se necessário essa funcionalidade em razão de um dos requisitos do cliente ser a sincronização instantânea da fonte de dados dos acessos dos clientes após alguma modificação.


## Hard Skills
Aqui, para fins de organização, é possível dividir as hard skills desenvolvidas entre front-end e back-end

Front-end:
- React-Native: Framework para criação de aplicativos mobile multiplataforma com tecnologias web | Sei fazer com auxílio de consulta
- TypeScript: Super-conjunto da linguagem JavaScript, com tipagem | Sei fazer autonomia
- Webpack: Criador de módulos de tecnologias web | Sei fazer com auxílio de consulta


Back-end:
- Python: Linguagem utilizada para a construção do servidor das aplicações | Sei fazer com autonomia
- Serviços REST: Criação de um servidor fornecedor de serviços *REST* | Sei fazer com autonomia
- Persistência de dados: Utilização de um Banco não relacional (MongoDB) para a persistência dos dados | Sei fazer com autonomia

## Soft Skills
Como desempenhei o papel de *master*, tive a oportunidade de exercitar as soft skills de gestão de equipes, planejamento de sprints e resolução de conflitos entre os integrantes do projeto.
Por ser o primeiro semestre em que temos aula 100% presencial, pude ter contato direto com o cliente e consegui compreender melhor suas necessidades para a aplicação.
