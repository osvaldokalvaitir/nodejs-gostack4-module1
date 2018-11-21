## Node - Módulo 1

API in using Node.js, Express and Nunjucks.

API em usando Node.js, Express e Nunjucks.

## Instalação e execução

Depois de instalado o Node.js, abra o prompt de comando e dentro da pasta do projeto execute os comandos abaixo.

Para instalar as dependências do projeto:

```
npm install | yarn install
```

Executar o projeto localmente:

```
npm run dev | yarn run dev
```

## Índice

- [Tecnologias](#tecnologias)

  - [Visual Studio Code](#visual-studio-code)

    - [Extensões](#extensões)

      - [EditorConfig for VS Code](#editorconfig-for-vs-code)
      - [ESLint](#eslint-for-vs-code)
      - [Nunjucks](#nunjucks-for-vs-code)
      - [Prettier - Code formatter](#prettier---code-formatter)

    - [Configurações](#configurações)

  - [Node.js](#nodejs)
  - [Yarn](#yarn)

- [Bibliotecas](#bibliotecas)
  - [ESLint](#eslint)
  - [Express](#express)
  - [Nodemon](#nodemon)
  - [Nunjucks](#nunjucks)

## Tecnologias

### [Visual Studio Code](https://code.visualstudio.com)

Editor de código-fonte que inclui suporte para depuração, realce de sintaxe, complementação inteligente de código, snippets, entre outros.

##### [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Utilizado para padronizar quebra de linha, indentação, espaços e tabs entre desenvolvedores de um mesmo projeto.

##### [ESLint for VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Utilizado para padronizar código entre desenvolvedores como utilização de pontos e vírgulas, tamanho máximo de caracteres em linhas e todo outro tipo de padronização.

##### [Nunjucks for VS Code](https://marketplace.visualstudio.com/items?itemName=ronnidc.nunjucks)

Utilizado para ter suporte à sintaxe .njk.


#### Configurações

Depois de adicionar as extensões, setar as configurações (Settings > Open settings.json):

```
{
  // Configura o Prettier e o ESLint
  "prettier.eslintIntegration": true,
  "editor.formatOnSave": true
}
```

### [Node.js](https://nodejs.org)

Interpretador de código JavaScript com o código aberto, focado em migrar o Javascript do lado do cliente para servidores.

### [Yarn](https://yarnpkg.com)

Gerenciamento de dependências rápido, confiável e seguro.

## Bibliotecas

### [ESLint](https://github.com/eslint/eslint)

Ferramenta para identificar e relatar padrões em JavaScript. Se o projeto for em Node é recomendado a utilização do guia de estilo 'Standard' e se for em React o guia de estilo do [AirBnB](https://www.npmjs.com/package/eslint-config-airbnb-base).

### [Express](https://github.com/expressjs/express)

Framework web rápido, flexível e minimalista para Node.js que ajuda a controlar as rotas e as views.

### [Nodemon](https://github.com/remy/nodemon)

Monitora as alterações no aplicativo node.js e reinicie o servidor automaticamente.

### [Nunjucks](https://github.com/mozilla/nunjucks)

Template engine para JavaScript.
