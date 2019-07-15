<p align="center">
	<img src="https://raw.githubusercontent.com/intelligo-systems/intelligo/master/.github/intelligo-logo.png" width="200"/>
<br>
	<b>🛠️ Chatbot generator for Intelligo Framework</b>
</p>
<p align="center">
    <a href="https://ci.appveyor.com/project/tortuvshin/intelligo-cli">
        <img alt="undefined" src="https://ci.appveyor.com/api/projects/status/eue1p0li7vf7hqt9?svg=true">
    </a>
   <a href="https://www.npmjs.com/package/intelligo-cli">
      <img alt="npm downloads" src="https://img.shields.io/npm/dt/intelligo-cli.svg?style=flat-square">
    </a>
    <a href="https://www.npmjs.com/package/intelligo-cli">
        <img alt="undefined" src="https://img.shields.io/npm/v/intelligo-cli.svg?style=flat-square">
        </a>
    <a href="https://github.com/tortuvshin/">
        <img src="https://img.shields.io/github/followers/tortuvshin.svg?style=social&label=Follow"
            alt="Followers"></a>
    <a href="https://github.com/intelligo-systems/intelligo-cli/blob/master/LICENSE">
            <img alt="License" src="https://img.shields.io/github/license/intelligo-systems/intelligo-cli.svg?colorB=blue&style=flat-square">
           </a>
      <a href="https://twitter.com/intent/tweet?text=Wow:&url=https://github.com/intelligo-systems/intelligo">
     <img alt="Tweet" src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social">
     </a>

</p>

🛠️ Chatbot generator for Intelligo Framework

## Installation


```bash
$ npm install intelligo-cli -g 
```

## Quick Start

### Messenger bot

Generate the your messenger bot project:

<p align="center">
<img width="100%" src=".github/intelligo-cli-messenger.gif">
</p>

Set the values in `config/default.json` before running the bot. Using your Facebook Page's / App's `ACCESS_TOKEN`, `VERIFY_TOKEN` and `APP_SECRET`

- `ACCESS_TOKEN:` A page access token for your app, found under App -> Products -> Messenger -> Settings -> Token Generation
- `VERIFY_TOKEN:` A token that verifies your webhook is being called. Can be any value, but needs to match the value in App -> Products -> Webhooks -> Edit Subscription
- `APP_SECRET:` A app secret for your app, found under App -> Settings -> Basic -> App Secret -> Show

**Note:** If you don't know how to get these tokens, take a look at Facebook's [Quick Start Guide](https://developers.facebook.com/docs/messenger-platform/guides/quick-start) .

### Slack bot

Generate the your slack bot project:

<p align="center">
<img width="100%" src=".github/intelligo-cli-slack.gif">
</p>

Before you start, you'll need a Slack App. If you don't already have one, click the following [link to create it](https://my.slack.com/services/new/bot) and put ```token``` in `index.js` file.

## Install dependencies:

```bash
$ npm install
```

## Run bot

Start your bot app:

```bash
$ npm start
```

## Documentation

To check out docs, visit [intelligo.js.org](https://intelligo.js.org).

## License

> Copyright (C) 2019 Intelligo Systems.  
> Intelligo framework is open-sourced software licensed under the [MIT](https://opensource.org/licenses/MIT) license.  
> (See the [LICENSE](https://github.com/intelligo-systems/intelligo-cli/blob/master/LICENSE) file for the whole license text.)
