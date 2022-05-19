# Supernova


[![Run on Replit](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/replit.svg)](https://replit.com/github/InterstellarNetwork/Supernova)


Deploying on machine

```
git clone https://github.com/titaniumnetwork-dev/uv-app/
cd uv-app
git submodule update --init
npm install
npm start
```

`uv.config.js`

```javascript
self.__uv$config = {
    prefix: '/sw/', // Proxy url prefix
    bare: '/bare/', // Bare server location
    encodeUrl: Ultraviolet.codec.xor.encode, // URL Encoding function
    decodeUrl: Ultraviolet.codec.xor.decode, // Decode URL function
    handler: '/uv.handler.js', // Handler script
    bundle: '/uv.bundle.js', // Bundled script
    config: '/uv.config.js', // Configuration script
    sw: '/uv.sw.js', // Service Worker Script
};
```
