## About

The boardroom bot allows for active proposals to be displayed within discord.

## Setup

The bot is configurable for specific daos. Start by cloning the code from github to your own computer or server.

Next create a new file in the base directory named .env
Copy the BOT_TOKEN and DAO lines from the sample.env file and put them into the .env file.
Set the DAO variable to be the name of the DAO that you wish to use from the Boardroom overview URL, for example Shapeshift would use 'shapeshift' since that is what is in the overview URL here: https://boardroom.io/shapeshift/overview
Set the BOT_TOKEN to your discords bot token, setup for that can be found here: https://discordpy.readthedocs.io/en/stable/discord.html
Make sure to invite the bot to your discord as well.

Finally run 'node index.js' to start the bot. Now you can type !proposals in your chat to see active proposals for your DAO!

If you want to run the bot on a server something like forever.js can be used to setup the bot to continuously run https://www.npmjs.com/package/forever 
