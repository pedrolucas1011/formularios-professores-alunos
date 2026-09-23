# Sistema Escolar

## Pré-requisitos

- [Node.js](https://nodejs.org/) instalado (você já deve ter, mas confira com `node -v` no terminal).

## Como baixar o projeto

1. Baixe o projeto pelo GitHub: **https://github.com/JefersonQueiroga/sistema-escolar**
     git clone https://github.com/JefersonQueiroga/sistema-escolar.git

2. Abra a pasta do projeto no VS Code (ou no terminal, navegue até ela com `cd`).

No terminal, dentro da pasta do projeto, rode:

npm install

## Como rodar o projeto

Este projeto precisa de dois terminais abertos ao mesmo tempo, um para a API simulada e outro para a aplicação React.

Terminal 1 — API simulada:

npx json-server --watch db.json --port 3000

Terminal 2 — aplicação React (Vite):
npm run dev


Abra no navegador o endereço mostrado no terminal

