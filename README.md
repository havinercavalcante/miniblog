# MiniBlogue

O MiniBlogue é uma aplicação web que permite aos usuários se cadastrar, fazer login e postar conteúdo em um blog. Esta aplicação foi desenvolvida com o objetivo de fornecer uma plataforma simples e fácil de usar para compartilhar ideias, pensamentos e informações.

## Funcionalidades

- Cadastro de usuários: Os usuários podem se cadastrar fornecendo um nome de usuário, endereço de e-mail e senha.
- Login de usuários: Os usuários registrados podem fazer login usando seu nome de usuário e senha.
- Postagem de conteúdo: Os usuários autenticados podem criar postagens no blog, incluindo um título e texto para o conteúdo do post.
- Visualização de postagens: Os visitantes podem visualizar todas as postagens disponíveis no blog, incluindo o título, autor e data de criação.

## Como Usar

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter o Node.js e o npm instalados em sua máquina.
3. Navegue até o diretório do projeto no terminal.
4. Execute `npm install` para instalar as dependências do projeto.
5. Configure o banco de dados de sua preferência (por exemplo, MongoDB, MySQL).
6. Configure as variáveis de ambiente necessárias no arquivo `.env`.
7. Execute `npm start` para iniciar o servidor da aplicação.
8. Acesse a aplicação em seu navegador usando o endereço `http://localhost:3000`.

## Tecnologias Utilizadas

- Node.js
- Express.js
- MongoDB (ou banco de dados de sua escolha)
- React.js
- HTML5
- CSS3
- JavaScript

## Estrutura do Projeto

- `client/`: Contém o código-fonte do frontend da aplicação React.
- `server/`: Contém o código-fonte do backend da aplicação Node.js.
  - `controllers/`: Controladores que lidam com as requisições HTTP.
  - `models/`: Modelos de dados da aplicação.
  - `routes/`: Rotas da API RESTful da aplicação.
  - `config/`: Configurações da aplicação, incluindo conexão com o banco de dados e autenticação.
  - `middlewares/`: Middlewares para autenticação e outras funcionalidades.
  - `index.js`: Arquivo de entrada do servidor Node.js.

## Contribuindo

Se você gostaria de contribuir para este projeto, fique à vontade para abrir uma issue ou enviar uma solicitação de pull request. Toda contribuição é bem-vinda!
