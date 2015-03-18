# http-incoming

Node's internal Request object. Useful for proper mocking.

Located here: https://github.com/joyent/node/blob/master/lib/_http_incoming.js

## Installation

```js
npm install http-incoming
```

## Usage

```js
var Request = require('http-incoming').IncomingMessage;
var req = new Request({});
```
