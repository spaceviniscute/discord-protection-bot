## Setup Instructions

NOTE: This bot was not coded with the intention of scaling to many discord servers. Use with caution.

Before continuing, please install Node.js 16.6.0

Steps:

`1.` Create a bot application on https://discord.com/developers

`2.` Make sure you enable MESSAGE CONTENT INTENT

`3.` Copy the token from the Bot page

`4.` Enter the token into the config.js file within the application files

`5.` Type `npm install` to install all the dependecies. This should take only a moment.

`6.` Run the application by typing `npm run start`

`7.` Finally and most importantly invite the bot into your server (this must be last) using the URL below, replace `BOT-ID` with the "APPLICATION ID" found in the developers page of Discord

https://discord.com/oauth2/authorize?client_id=BOT-ID&scope=bot&permissions=8

I usually also recommend running the application with PM2 (Process Manager 2). Here's how to do that:

`1.` Install PM2 in your machine by typing `npm install -g pm2`
`2.` Within the application root directory, type `pm2 start app.js`

The application will run, and auto-restart in any case. You can check the status by typing `pm2 ls`
