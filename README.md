# Rock-Paper-Scissors Discord Bot
This is a Discord Bot that you can play rock paper scissors with. Use the command "/play", and choose rock, paper, scissors, or even gun!

## How It's Made:

**Tech used:** JavaScript, Node.js, Discord.js

This is a barebones Node.js app that connects to the Discord API. A random number is generated in Javascript and used to determine the computer's "move", and the move and the subsequent game result are communicated to the reader.

## Lessons Learned:

This is my first time building a Node.js app. I also got experience with a lot of tools that I'd heard of, such as using .gitignore, config files and using a Linter.

## Setup Instructions:

1. Ensure Node.js is installed on your computer.
2. Pull the source code.
3. Create or login a Discord account, and create a bot on the Developer Portal. Create a config file in the same folder as the source code with the following:
{
    "token": "XXXXXXXXX",
    "clientId": "XXXXXXXXX",
    "guildId": "XXXXXXXXX"
}
4. Deploy commands by running "node deploy.js", then start the app by running "node index.js".
5. Add your bot to servers by generating an invite link on the developper portal.
6. Use the bot and enjoy!

