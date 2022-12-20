# Discord Bot Template

A simple discord bot template for the [bohr.io](https://bohr.io) platform. It uses api endpoints to respond to slash commands on the Discord app.

## Usage

1. In the [bohr.io](https://bohr.io) platform start a new project with this template.
1. Create a [Discord application](https://discord.com/developers/applications) and a bot.
1. Invite the bot to your server using the generated link.
1. Set the following environment variables on the [bohr.io](https://bohr.io) project dashbord:
    - `APPLICATION_ID`
    - `DISCORD_BOT_TOKEN`
    - `DISCORD_PUBLIC_KEY`
    - `TEST_GUILD_ID`

5. Start the bot locally using the commands in the project's overview page in the [bohr.io](https://bohr.io) platform.

</br>

The TEST_GUILD_ID is the id of the discord server you want to use to test your bot while developing the bot.

## Commands

 - server: send the channel and server that the user is in
 - user: send a mention to the user
