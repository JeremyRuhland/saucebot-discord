Saucebot
========

A discord bot for interacting with multiple art hosting website URLs.

If you would like to add this bot to your server [click here](https://discordapp.com/oauth2/authorize?client_id=284138973318742026&scope=bot&permissions=0) and authorize it through your discord account.

Currently supports:

 * Furaffinity
 * Deviantart
 * Weasly
 * e621
 * ~~Most multi-image twitter posts~~ Now supported natively, but feature can be enabled
 * Pixiv
 * Hentai-foundry

Enclosing messages in angle brackets disables image preview. Links hiden by spoilers are automatically disabled.

Requires
--------

 * `>=Python3.5`
 * [Discord.py](https://github.com/Rapptz/discord.py) >= 1
 * [pixivpy](https://github.com/upbit/pixivpy)
 * [twitter](https://github.com/bear/python-twitter) if twitter feature enabled
 * re
 * requests
 * io
 * json
 * Discord bot token
 * Weasly API key
 * Pixiv login and password

Installing
----------

Do the install stuff, you'll need a discord app and bot account.
Set the appropriate environment variables to pass credentials into the program.
Follow the instructions [here](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token) for creating those and getting the bot invited to your server.
