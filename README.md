# To-Do List

## 📌 Buenas Senhores! Tudo certo?

Esse repositório se trada de uma To-Do List funcional e um teste de um desenvolvedor back se aventurando no front-end!

## 🚀 Tecnologias Utilizadas

- React.js
- JavaScript
- Node.js
- GraphQl

## 🛠 Como rodar o projeto do jeito convencional (back e front)

1. Clone este repositório:
   ```sh
   git clone https://github.com/ZDjow/To-DoList.git
   ```
2. Instale as dependências (back):
   ```sh
   cd serverless
   yarn install
   ```
3. Inicie o servidor (back):
   ```sh
   yarn start
   ```
4. Acesse o projeto (back):
   ```sh
   http://localhost:4000/graphql
   ```
5. Instale as dependências (front):
   ```sh
   cd frontend
   yarn install
   ```
6. Inicie o servidor (front):
   ```sh
   yarn start
   ```
7. Acesse o projeto (fron):
   ```sh
   http://localhost:3000/
   ```

## 🛠 Como rodar o projeto de um jeito simples (um terminal)

1. Clone este repositório:
   ```sh
   git clone https://github.com/ZDjow/Uno-Solucoes.git
   ```
2. Para rodar dessa forma certifique-se que tem o concurrently adicionado na raiz do projeto:
   ```sh
   cd Uno-Solucoes
   yarn add concurrently --dev
   ```
3. Instale as dependências:
   ```sh
   yarn install
   ```
4. Inicie o servidor:
   ```sh
   yarn start
   ```
5. Acesse o projeto:
   ```sh
   http://localhost:3000/
   ```

## 🛠 Como rodar o projeto com um click (script)

1. Para rodar dessa forma certifique-se que tem o concurrently adicionado na raiz do projeto:
   ```sh
   cd Uno-Solucoes
   yarn add concurrently --dev
   ```
2. Na pasta raiz do projeto e depois de ter instalado as dependências execute o arquivo:
   ```sh
   start.bat
   ```

## Observações:

Algumas inconsistências aconteceram na hora de subir o front por causa de uma incompatibilidade na versão do Node.js (versão utilizada: v22.14.0).

1. npm install (front):
   ```sh
   Houve conflito nas dependências entre o styled-components e o @mui/styled-engine-sc.
   Usado legado na instalação:
   npm install --legacy-peer-deps
   ```
2. npm start (front):
   ```sh
   Usada variável de ambiente:
   $env:NODE_OPTIONS="--openssl-legacy-provider"
   yarn start
   ```
3. Se a sua versão do Node.js for mais antiga e você tentar rodar o projeto com apenas um terminal
   ou direto pelo .bat retirar a variável de ambiente do package.json da raiz do projeto.

## 👨‍💻 Autor

**ZDjow**

- GitHub: [@ZDjow](https://github.com/ZDjow)
