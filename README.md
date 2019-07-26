### bitcore-p2p
---
https://github.com/bitpay/bitcore-p2p


```js
var Peer = require().Peer;

var peer = new Peer({host: '127.0.0.1'});

peer.on('ready', function() {
  console.log(peer.version, peer.subversion, peer.bestHeight);
});
peer.on('disconnect', function() {
  console.log('connection closed');
});
peer.connect();


peer.on('inv', function(message) {
  // message.inventory[]
});
peer.on('tx', function(message) {
  // message.transaction
});
```

```
```

```
```


