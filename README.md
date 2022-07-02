# Cloud Native App

Exemplo de uma aplicação com boas práticas de desenvolvimento nativo em nuvem e os 12 fatores em uma aplicação web.

## 1. Criação do projeto

> Ignorar essa seção caso o projeto já tiver sido criado

Inicializar projeto

	npm init

## 2. Instalar extensões no VS Code

[ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## 3. Ferramentas de qualidade

ESLint

	npm install eslint --save-dev

Prettier

	npm install --save-dev --save-exact prettier

Husky

	npm install husky --save-dev

	npx husky-init && npm install

Configuração e integração

	npm install --save-dev eslint-config-prettier

	npm install --save-dev eslint-plugin-prettier

	npm install --save-dev prettier-plugin-organize-imports
