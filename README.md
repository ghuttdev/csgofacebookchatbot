# CS:GO Pro Player Configs Facebook Chat Bot

This is a node.js chat bot using Claudia, that provides information to users about game settings of professional CS:GO players. 

Services/Tools used: 
- Node.js;
- Claudia.js (ferramenta de deploy para projetos Node.js);
- Artificial Intelligence Markup Language (AIML);
- AWS

Message https://www.facebook.com/csgoproplayerconfigs/ with the following commands:

- Hello
- Thanks
- Fox
- Forest
- S1mple

More players/commands can be added in the AIML file, which works as a database for the bot.

SETUP (After cloning)

npm install claudia -g
npm install
claudia create --region eu-west-2 --api-module bot --configure-fb-bot



