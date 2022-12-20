# Discord Bot Template

A simple discord bot template for the [bohr.io](https://bohr.io) platform. It uses api endpoints to respond to slash commands on the Discord app.

## Setting your project

1. In the [bohr.io](https://bohr.io) platform start a new project with this template.
2. Create a [Discord application](https://discord.com/developers/applications) and a bot.
3. Generate a url in the OAuth2/Url Generator, with the options:
    - `SCOPES`:
        - `applications.commands`
        - `bot`
    - `BOT PERMISSIONS`:
        - `Use Slash Commands`
        - `Send Messages`
4. Invite the bot to your server using the generated url.
5. Set the following environment variables on the [bohr.io](https://bohr.io) project dashbord:
    - `APPLICATION_ID`
    - `DISCORD_BOT_TOKEN`
    - `DISCORD_PUBLIC_KEY`
    - `TEST_GUILD_ID`
6. In the discord application General Information, set the `INTERACTIONS ENDPOINT URL` with the project's url.

## Developing

1. Create a second Discord application to be your development application.
2. Start the bot locally using the commands in the project's overview page in the [bohr.io](https://bohr.io) platform.
3. When starting your project locally, it will be provided a tunnel url to your local project. Use it as the `INTERACTIONS ENDPOINT URL` in the development application.

</br>

## Commands

 - server: send the channel and server that the user is in
 - user: send a mention to the user
