# Projeto Olá Mundo com o Angular
## Requisitos
- Angular CLI
- NodeJS
- NPM

## Como criei o projeto?
Criar o projeto:
>ng new ola-mundo

Entrar no projeto:
>cd ola-mundo

## Após clonar o projeto, digite no terminal
NPM:
>npm install

Executar um teste:
>ng test

Executar o projeto:
>ng serve

Abra o projeto no navegador:
>http://localhost:4200/

## O que é o Webpack?
O webpack pega todos o código e transforma em um código que nosso compilador entenda

## Entendendo o código
`app.e2e-spec.ts`: navega até a página principal e busca os h1 e vê se contém as frases que você definiu `app.po.ts`, `tsconfig.e2e.json`
`node_modules`: é o segundo diretório, aqui estão todas as bibliotecas do projeto
`src`: é o 3 diretório, aqui está todo o código fonte da aplicação
`app` aqui vamos colocar todos o nosso código-fonte
`assets` coloca as imagens
`environments`: cria uma versão de produção ou desenvolvimento
`main.ts`: faz a inicialização do Angular na aplicação
`polyfills.ts`: adiciona bibliotecas externas
