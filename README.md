# Pré-processador CSS SASS
----

1. `npm init -y` -  Criar nosso package.json;
2. `npm install --save node-sass` - adicionar Sass ao nosso projeto;
3. criar o .gitignore e adicionar a pasta node_modules a exclusão;
4. adicionar o script ao package.json, necessário para observarmos as alterações em tempo real `"scss": "npx node-sass -w scss/app.scss -o assets/css/"`;