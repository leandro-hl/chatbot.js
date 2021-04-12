# chatbot.js

## ENVIRONMENT
* Install SQL Server Express (And Management Studio if you want to make your own queries). https://www.microsoft.com/en-us/sql-server/sql-server-downloads
* npm i to install dependencies

### ------ To Generate SQL Databse Schema -------
* Execute Database Script

### ------ To Start API ------
* npm run dev
* F5 to attach vs code debugger to process
* port 3000

### ------ To Start Bot -----
* npm run dev
* F5 to attach vs code debugger to process
* port 3120

### ------ To Talk with the bot ----
* Open https://webchat.freenode.net/ on your browser
* Enter your NickName and join the channel configured in IRCClient on ChatBotServer.sln (#lxbuniquekdskds)
* To know which commands are available send !commands
* !timepopularity accepts timezones, prefixes and also suffixes (like the Vancouver example)

### ------ To Test the API -----
* Open Postman
* Make a POST request to http://localhost:3000 + timeat / timepopularity
* Set Body RAW JSON with content like { "Timezone": "Vancouver" }
