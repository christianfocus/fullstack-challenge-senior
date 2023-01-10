<p align="center">
  <img src="https://i.postimg.cc/JnWV6rm6/download.png" alt="Sublime's custom image"/>
</p>


- [Desafio FullStack Senior:earth_americas: :computer: :iphone:](#desafio-fullstack-senior-earth_americas-computer-iphone)
- [Introdução :game_die:](#introdução-game_die)
- [Proposta	:grey_exclamation:](#proposta-grey_exclamation)
  - [Requisitos funcionais :white_check_mark:](#requisitos-funcionais-white_check_mark)
    - [Backend :earth_americas:](#backend-earth_americas)
    - [Frontend :computer:](#frontend-computer)
- [Opcional - Requisitos avançados 	:grey_exclamation:](#opcional---requisitos-avançados-grey_exclamation)




# Desafio FullStack Senior :earth_americas: :computer: :iphone:

**Seja bem-vindo ao nosso desafio de desenvolvimento!

*Tenha certeza de ter lido todo o documento atentamente até o final e esclarecido as dúvidas com nosso time caso surja alguma.*

:rocket: Tudo certo!?  Então vamos lá! 

# Introdução :game_die:

- Faça um fork deste repositório.
-	É obrigatório que seja desenvolvido em apenas nodeJS.
-	É obrigatório ser totalmente codado em typescript.
-	Respeite os princípios do SOLID.
-	Backend (deverá ser feito em node-js em typescript, podendo usar frameworks como nestJS ou adonisJS).
-	Frontend (deverá ser feito em reactJS em typescript, podendo utilizar vite, nextjs ou qualquer outro framework do mundo react).
-	Após finalizar, submeta um pull request com um comentário informando o seu e-mail de contato e aguarde nossa avaliação.

# Proposta :grey_exclamation:

Você deverá desenvolver uma central de ajuda. Esta plataforma deverá possuir uma API REST em node em uma aplicação front-end em REACT para se comunicar. Esta plataforma abrirá suporte a usuários, com abertura de ticket de solicitação e comunicação a um atendente do suporte.

- Eu como usuário desejo ter um usuário na plataforma para abrir um chamado.
- Eu como usuário devo ter um ter um botão para acionar um chat para falar com uma atendente e gerar um ticket de solicitação.
- Eu como usuário gerenciador da plataforma desejo ver em tempo real os chamados solicitados pelos usuários da plataforma.
- Eu como usuário gerenciador desejo conversar como usuários da plafatorma
- Eu como usuário gerenciador desejo finalizar um atendimento solicitado ou atendido e o ticket referente.
- EU como usuário gerenciador desejo visualizar a lista de todos os chamados com os dados referente aquela solicitação atendida/pendente.


> **Observações:**
> - Sua aplicação web DEVE se comunicar com sua API.
> - O chat assim que for atendido por um algum usuário gerenciador deve ser feito em TEMPO REAL.
> - Você pode utilizar os bancos de dados relacional (ou não relacional) de sua preferência.
> - Você pode utilizar a estratégia que lhe for pertinente para garantir a comunicação em tempo real das aplicações web.
> - Você pode utilizar gerenciamento de chamados em fila até o haja um gerenciador disponível ou a estratégia que preferir.

## Requisitos funcionais :white_check_mark:
### Backend :earth_americas:

- A API deve seguir as boas práticas e padrões de implementação REST.
- Os dados deve ser salvos em um banco de dados.
- Escrever os testes para o código e as APIs geradas.
- Prover documentação para API. (Sugestão OpenAPI/Swagger)
- Respeitar os protocolos HTTP.
- Padrões de segurança (token, criptografia).
- Utilize alguma estratégia de arquitetura (DDD, etc...)
- Fique a vontade para utilizar bibliotecas de componentes de mercado ou criar os seus.
- Utilize **TypeScript**
- Sua API deverá ter tratamento de erros internos e externos para comportamentos inesperados.

### Frontend :computer:

- Criar uma tela login para acesso a plataforma.
- Criar uma tela home com menu de acesso as funcionalidades.
- O tela home deverá ter funcionalidades e padrões diferentes para usuário da plataforma e usuário gerenciador.
- Para usuário gerenciador deverá ter uma pagina de listagem de solicitações feitas, atendidas e em execução em tempo real.
- Para usuário da plataforma deverá existir um local de preenchimento de solicitação de dados para conseguir falar com um usuário gerenciador para atender seu pedido.
- A tela home do usuário deverá ser listado seus historico de solicitações, número do pedido, status e quem o atendeu.
- Utilize **TypeScript**

> **Observações:**
> - Seu código deverá trabalhar com contextos e criacão de hooks feitos especificamente para aplicação
> - Fique a vontade para trabalhar com frameworks auxiliares ao react.
> - Fique a vontade para utilizar o cliente HTTP que preferir (Fetch, Axios)
> - Deverá ter tratamento de erros para não quebrar a pagina ou deixar de ter feedback ao usuário caso haja algum imprevisto.


## Diferenciais
- Serão considerados diferenciais o desenvolvimento de testes unitários e de integração em qualquer uma das aplicações desenvolvidas.
- Utilização de design patterns.
- Linters e padronização de código.
- Semantica.


## Opcional - Requisitos avançados 	:grey_exclamation:

Estes requisitos são opcionais no desafio, sinta-se a vontade para deixá-los de lado, a menos que seja solicitado que os cumpra!   

- Criar mecanismo completo de autenticação e autorização (authentication/authorization/etc.) , como OAuth.
- Mecanismos de login via conta google/facebook ao usuário da plataforma...
- Criar mecanismo de log e auditoria (quando/como/quem etc.).
- Hospedar aplicacão em algum lugar e disponibilizar o link.


[Voltar ao topo](#desafio-fullstack-earth_americas-computer-iphone)
