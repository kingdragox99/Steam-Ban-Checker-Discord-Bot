# Steam Ban Checker Discord Bot

this bot will check if a user has been monitored vac ban or ow ban

## Installation

Install Steam-Ban-Checker-Discord-Bot with yarn

[Discord api](https://discord.com/developers/applications)

[Mongo DB](https://www.mongodb.com/)

Make .env with

```bash
CLIENT_TOKEN="YOUR_DISCORD_API_KEY"
MONGO_URL="YOUR_MONGODB_CONNECT"
```

After putting that in console

```bash
  yarn
  node index.js
```

Go on discord and type in channels

Example :

- Suspected cheater
- Confirmed cheater

```bash
  !setup input // In your input channel where you  put the url of suspected cheaters
  !setup output // If a cheater was detected, he will be put here
```

![Logo](https://i.imgur.com/ErAZmVx.png)
