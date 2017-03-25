# muthurBot

A chat bot by [Brian Rinaldi](http://developer.telerik.com/author/brianrinaldi/) to demonstrate [SuperScript](https://github.com/superscriptjs/superscript). Forked so I could play with it.

## Set up

- If you don't have SuperScript installed: `sudo npm install -g superscript`
- Install dependencies:
```
git clone https://github.com/HarryStevens/muthurBot
cd muthurBot
npm install
```
- Open a new Terminal tab and start Mongo: `mongod`
- In the original Terminal tab, prepare the project and run it:
```
npm run parse
npm run build
npm run start-telnet
```
- Open a new Terminal tab to connect to the Telnet server: `telnet localhost 2000`

That's it! To learn how he built the bot and what it does, [see the tutorial](http://developer.telerik.com/content-types/tutorials/building-conversational-bot-javascript/].