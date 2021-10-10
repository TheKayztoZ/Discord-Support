# Discord-Support
Spero que les guste este tutorial ;D

Para Instalar node.js v16 hay que poner esto en el shell

npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH

Ahora crea un script de start

{
  "name": "Discord Support",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "node .",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  
Ahora instala discord.js
  
npm install discord.js

inicia tu bot

npm start

