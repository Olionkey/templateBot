# templateBot

## Before you start
- Make sure you install node.js and it is working.
- You can see if it working by opening up command prompt and type in
  ``node``
- If you got some command options that you have installed it correctly.
- Next you will need an text editor to write the bot in. I use atom for my developing of my bots.

## Before you do any coding
  You may need to run the following in the directory with the js files:
    ``npm install --save discord.js``

## Required files to have the bot work.
  After that you will need to put some information into two files. auth.json, and config.json
  This is what will go into the auth.json

  ```json
  {
    "token":     "put-your-token-here"
  }
  ```
  This is what will go into config.json
  ```json
  {
    "general": {
              "prefix" : "How-you-want-the-bot-to-be-called",
              "statusChannelID" : "The Status Channel Id"
            }
  }
  ```
### Running the bot
  To run the bot open up command prompt
  Then move to the directory of the index.js file with ``cd``
    example.
      ``cd C:/User/User/Documents/Discordbot``
  After you have moved to the directory of the index.js file, you will have to run this command which will start the bot.
  `` node .``
