# Creating a Bot Account

Before you start using discord.js, you need to decide which type of bot you want to make.
You have the option to create a self-bot or a "real" bot.

## 1) Choosing a Bot

### Self Bots \(User Bots\)

A self-bot runs on _your_ account. This can be useful for creating custom commands for
yourself. A self-bot comes with multiple restrictions:

* Self-bots cannot respond to the messages of other users
* Self-bots cannot collect information about invites sent in chat channels - this is
known as _"invite scraping"_.
* Self-bots are subject to the same [Terms of Service](https://discordapp.com/tos) as any
other account.

Additionally, self bots cannot use some features of discord.js due to limitations set by
the [Discord API](https://discordapp.com/developers/docs/intro), e.g. bulk-deleting messages.

### "Real" Bots

Real bots are known as bot accounts. They are allowed to interact with other users and generally
have access to more features of discord.js and the [Discord API](https://discordapp.com/developers/docs/intro).
They are not allowed to scrape for invites and are subject to the same
[Terms of Service](https://discordapp.com/tos) as any other account.

Bot accounts should be used for any serious development of bots. They can be identified by
their _BOT_ badge next to the username:

<img src="../assets/bot-account.png">

## 2) Getting an Account Token

To have access to your bot account, you need access to its token. Both user and bot accounts have tokens.
You can think of your bot's token as its password, so you should _keep the token private_.

Once you have obtained an account token following the steps below, make sure you keep it safe. If other people get this
token, they have full access to your bot account. If you are using a self-bot, they have full access to your
user account.

### Self Bots \(User Bots\)

1) From either the official Discord Client or the web application,