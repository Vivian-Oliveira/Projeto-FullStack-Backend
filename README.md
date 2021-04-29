#  📌 PROJETO X
#### Projeto FullStack - Backend
<h4 align='center'>
👉 Status:🚧 Em construção 🚧 🚧 
</h4>
<hr />
### ✨ Funcionamento:

- [] Autenticação Cadastro
- Usuários se cadastram com nome, email, nickname e senha. Aqui, a senha tem que possuir, no mínimo, 6 caracteres. 
- Email e nickname são valores que precisam ser únicos. Ao se cadastrar o usuário deve receber um token de acesso, para que possa se logar.
- O cadastro deve ser criado com um método post
- [] Autenticação Login
- O usuário deve passar seu email e sua senha.
- O login também será criado usando um método post.
- Caso queira incrementar, permita que o usuário se logue também usando a combinação de nickname e senha. 
- Ao fazer login o usuário deve receber um token de acesso, para que possa acessar
- [] Criação de música ou imagem
- Uma música precisa ser guardada com o método POST. 
- O caminho fica a seu critério, mas uma sugestão possível é manter em um simples /music ou /image.
- O endpoint de criação deve ser autenticado, ou seja, somente um usuário logado deve poder criar uma música ou imagem.
- Eles devem ser criados de forma associada ao usuário.
- [] Leitura de música ou imagem
- O conteúdo precisa ser lido com o método GET. 
- O endpoint de leitura também deve ser autenticado, recebendo o token do usuário.
- Para buscar todos os itens, basta bater no endpoint e o retorno será um array com todos os valores associados ao usuário inseridos até o momento.
- Para buscar um item específico, complemente o caminho do endpoint com um /:id.

### 💻 Tecnologias:
As seguintes tecnologias foram usadas na construção do projeto:
- [Node.js](https://www.w3schools.com/nodejs/ref_modules.asp)
- [TypeScript](https://www.typescriptlang.org/)
- [Postman](https://www.postman.com/)
- [Mysq](https://www.mysql.com/products/workbench/)

### 📂 Como instalar o projeto:
##### Passo 1. Clone este repositório:
$ git clone ....
##### Passo 2. Acesse a pasta do projeto no terminal/cmd:
$ cd pasta
##### Passo 3. Instale as dependências:
$ npm install
##### Passo 4. Rode o projeto:
$ npm run start

