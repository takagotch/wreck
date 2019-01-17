### wreck
---
https://github.com/hapijs/wreck

```js
const Wreck = require('wreck');
const example = async function(){
  const { res, payload } = await Wreck.get('http://example.com');
  console.log(payload.toString());
};
try{
  exmaple();
} 
catch(ex){
  console.log(ex);
}

const Wreck = require('wreck');
const method = 'GET''
const uri = '/';
const readableSteam = Wreck.toReadableStrem('foo=bar');
const wreck = Wreck.defaults({
  headers: {},
  agents: {
    https: new Https.Agent({ maxSockets: 100 }),
    http: new Http.Agent({ maxSockets: 1000 }),
    httpsAllowUnauthorized: new Https.agent({ maxSockets: 100, rejectUnauthorized: false })
  }
});
const wreckWithTimeout = wreck.defaults({
  timeout: 5
});
const options = {
  baseUrl: 'https://www.example.com',
  payload: readableStream || 'foo=bar' || Buffer.from('foo=bar'),
  headers: { /**/ },
  redirects: 3,
  beforeRedirect: (redirectMethod, statusCode, location, resHeaders, redirectOptions, next) => next(),
  redirectd: function (statusCode, location, req){},
  timeout: 1000,
  maxBytes: 1048576,
  rejectUnauthorized: true || false,
  downstreamRes: null,
  agent: null,
  secureProtocol: 'SSLv3_method',
  ciphers: DES-CBC3-SHA'
};
const example = async function(){
  const promise = wreck.request(method, uri, options);
  try{
    const res = await promise;
    const body = await Wreck.read(res, options);
    console.log(body.toString());
  }
  catch(err){
  }
};

const stream = Wreck.toReadableStream(Buffer.from('Hello', 'ascii'), 'ascii');
const read = stream();

const result = Wreck.parserCacheControl('private, max-age=0, no-cache');

const Wreck = require('wreck');
Wreck.agents.http.maxSockets = 20;

const HTTPS = require('https');
const Wreck = require('wreck');
Wreck.agents.https = new HTTPS.Agent({
  cert,
  key,
  ca
});

```

```
```

```
```


