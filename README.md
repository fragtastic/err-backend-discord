[Work in progress, this is unusable at the moment.]

This is a backend for Discord (http://discordapp.com) for errbot (http://errbot.io).

It allows you to use errbot from Discord.

It is Python 3.4+ only.

## Installation

```
git checkout https://github.com/gbin/err-backend-discord.git
```

and add:

```
BACKEND = 'Discord'
BOT_EXTRA_BACKEND_DIR = '/path_to/err-backend-discord'
```

to your config.py

## Authentication

Create an app and a bot user in 'https://discordapp.com/developers/applications' like:

```
BOT_IDENTITY = {
    'token' : 'MTg5NzMwMjA4MTYxMTR2ODgw.CiYq-A.Su1ghlljJUYnrvgKDdxdRm0al0Y'
}
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
