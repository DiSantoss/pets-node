# Site de Pets (Gato e Cachorro) - Node.js, Express, TypeScript
Este é um projeto de um site de pets desenvolvido utilizando Node.js, Express, TypeScript e segue o padrão MVC (Model-View-Controller).

# Pré-requisitos
Antes de começar, certifique-se de ter instalado o seguinte:

Node.js: https://nodejs.org
# Configuração
Siga os passos abaixo para configurar e executar o projeto em seu ambiente local:

* 1 - Faça o download dos arquivos do projeto.
* 2 - Abra o diretório do projeto no seu editor de código preferido, como o Visual Studio Code.
* 3 - Abra o diretório do projeto no terminal de sua preferência.
* 4 - Execute o comando npm install para instalar as dependências do projeto, incluindo o dotenv, express, nodemon e mustache.
 
  ```npm install dotenv express nodemon mustache```
* 5 - Após a instalação das dependências, execute o comando npm run start-dev no terminal para iniciar o servidor local utilizando o nodemon.

  ```npm run start-dev```
* 6 - No seu navegador, digite localhost:4000 na barra de navegação.
* 7 - Agora você pode visualizar o projeto em funcionamento.
# Estrutura do Projeto
 O projeto segue a estrutura MVC (Model-View-Controller), com a seguinte organização de diretórios:

```
Copy code
├── src/
│   ├── controllers/
│   │   └── ... (controladores do MVC)
│   ├── models/
│   │   └── ... (modelos do MVC)
│   ├── views/
│   │   └── ... (visualizações do MVC)
│   ├── routes/
│   │   └── ... (rotas do Express)
│   ├── app.ts (arquivo principal)
│   └── ... (outros arquivos)
├── node_modules/
├── .env (arquivo de configuração do dotenv)
├── package.json
├── tsconfig.json
└── ... (outros arquivos e diretórios)
```
Certifique-se de explorar os diretórios e arquivos para entender melhor a estrutura do projeto.

# Contribuição
Contribuições são bem-vindas! Se você quiser contribuir com melhorias ou correções para este projeto, fique à vontade para enviar um pull request.
