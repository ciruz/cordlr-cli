[![https://img.shields.io/badge/GITTER-join%20chat-green.svg](https://img.shields.io/badge/GITTER-join%20chat-green.svg)](https://gitter.im/Devcord/cordlr)

![cordlr](http://i.imgur.com/GPVoYNk.jpg)

> A discord bot using plugins created by the community.

## What is Cordlr?

Cordlr is a highly customizable bot for [Discord](https://discordapp.com/) that uses [plugins created by the community](https://www.npmjs.com/browse/keyword/cordlr), so that you can have a bot perfect for your server with only a small amount of effort.  Read the ["Getting Started"](docs/getting-started.md) page to learn how to use cordlr.

### Usecase

This CLI is directed to Discord server owners who are able to host Node.js applications and want to have a modular loader for
Discord bot functionalities. Cordlr can load different functionalities like Palette generators, Role and modding tools,
fun commands and more.

## Installation

### Requirements

* A Discord server
* A Discord bot ([create one here](https://discordapp.com/developers/applications/me))
* NodeJS 6.0 or higher
* NPM

### Setup

First you have to install Cordlr via NPM.

```sh
npm install -g cordlr-cli
```

*Install experimental releases with `cordlr-cli@next`.*

After that create a folder containing a `package.json` for cordlr-package installation and a `cordlr.json` containing following values.

```js
{
  "token": "Your Bot Token",
  "actions": [],
  "prefix": "$",
  "plugins": []
}
```

For more advanced installation guides check the [getting started documentation](docs/getting-started.md)

For more configuration guides check the [configuration documentation](docs/configuration.md)

If you want to know how to write a Cordlr package learn more about that in [package documentation](docs/plugins.md)

## Documentation

See more documentation in the [`docs/`](docs/) folder.<br>
See ["Getting Started"](docs/getting-started.md) if you are new to Cordlr.

## License
Devcord © [GPLv3](LICENSE)
