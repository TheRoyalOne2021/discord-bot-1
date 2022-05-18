![Untitled1](https://user-images.githubusercontent.com/78038416/160035221-80e3abd7-844e-4535-87d1-77126751ee32.png)
# discord-bot-1

a multipurpose discord bot in progress

prerequisites - node.js v13+, npm

dependencies - discord.js, discord.js-commando, discord-rpc, fs

copy/paste your bots token in the token section of ".env"

to run: cd into the bot directory then install all of the dependencies, after installation is complete execute "node index"

bot should go online as soon as "node index" is executed

replace channelId with your ticket channel ID in "ticket.js"

mute command requires role called "muted" and assumes permissions are already set for the role

default prefix is "$" because it conflicts the least, can be changed within ./assets/config.json

Procfile is for deploying to heroku (optional), instructions are not included
