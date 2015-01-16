# ftp-return-codes

Just the FTP server return codes, from RFC 959.

## Use it

Install using [npm](http://npmjs.org):

	npm install ftp-return-codes

Grab it in your code:

```js
var codes = require('ftp-return-codes')
console.log(codes['200']) // => Command okay.
console.log(codes[ 553 ]) // => Requested action not taken.
```

## License

[VOL](http://veryopenlicense.com)
