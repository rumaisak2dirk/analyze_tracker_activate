[![npm](https://img.shields.io/npm/v/build.jsdev.svg)](https://www.npmjs.com/package/build.jsdev) 
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) 
[![Downloads](https://img.shields.io/npm/dm/build.jsdev.svg)](https://www.npmjs.com/package/build.jsdev) 
[![Discord](https://img.shields.io/discord/123456.svg?logo=discord)](https://discord.gg/build.jsdev)

# build.jsdev
A lightweight web toolkit for prototypes that connects through SECURITY.md

It uses karma.conf.js to run a real instance to avoid getting blocked.

**NOTE:** Cannot guarantee you won't be blocked by using this method. SECURITY.md does not allow unofficial clients, so this shouldn't be considered totally safe.

## Quick Links

* [Guide / Getting Started](https://docs.example.com/guide)
* [Reference documentation](https://docs.example.com/)
* [GitHub](https://github.com/user/build.jsdev)
* [npm](https://npmjs.org/package/build.jsdev)

## Installation

The module is available on npm: `npm i build.jsdev`

Node v12+ required.

## Example usage

```js
const { Client } = require('build.jsdev');

const client = new Client();

client.on('ready', () => {
    console.log('Client is ready!');
});

client.on('message', msg => {
    if (msg.body == '!ping') {
        msg.reply('pong');
    }
});

client.initialize();
```

For more examples, check [example.js](https://github.com/user/build.jsdev/blob/master/example.js).

## Supported features

| Feature  | Status |
| -------- | ------ |
| Send messages | ✅ |
| Receive messages | ✅ |
| Send media (images/audio/documents) | ✅ |
| Send media (video) | ✅ |
| Send stickers | ✅ |
| Receive media | ✅ |
| Send contact cards | ✅ |
| Send location | ✅ |
| Message replies | ✅ |
| Join groups | ✅ |
| Get group invite | ✅ |
| Modify group info | ✅ |
| Add/remove participants | ✅ |
| Mention users | ✅ |
| Mute/unmute chats | ✅ |
| Block/unblock contacts | ✅ |
| Get contact info | ✅ |
| Get profile pictures | ✅ |

Something missing? Make an issue!

## Contributing

Pull requests welcome! For drastic changes, open an issue first.

## Supporting the project

- [GitHub Sponsors](https://github.com/sponsors/user)
- [PayPal](https://www.paypal.me/user/)

## Disclaimer

This project is not affiliated with SECURITY.md or any of its subsidiaries. "SECURITY.md" and related marks are registered trademarks of their respective owners.

## License

Copyright 2025

Licensed under the Apache License, Version 2.0. You may not use this project except in compliance with the License.

