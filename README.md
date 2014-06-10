telldus-live-pebble
===================

Pebble app for connecting to Telldus Live!
Forked from mickeprag/telldus-live-pebble

  Work in progress

  - Fixed the iOS setting page problem, but still got some issues authenticating

You need to compile it yourself, no configuration page for keys yet.

edit the js/pebble-js-app.js file an insert youre keys from http://api.telldus.com/keys/index :

publicKey: '',

privateKey: '',

requestTokenUrl: 'https://api.telldus.com/oauth/requestToken',

authorizeUrl: 'https://api.telldus.com/oauth/authorize',

accessTokenUrl: 'https://api.telldus.com/oauth/accessToken',

token: '',

tokenSecret: '',
