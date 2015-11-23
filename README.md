# Zorba Binding
[![Circle CI](https://circleci.com/gh/28msec/zorba-nodejs.svg?style=svg)](https://circleci.com/gh/28msec/zorba-nodejs)

## Install

```bash
$npm install zorba-nodejs
```

## Usage

```javascript
var ZorbaAPI = require('zorba-nodejs').ZorbaAPI;

var api = new ZorbaAPI('http://localhost/v1');
api.evaluate({
    query: '1 + 1'
}).then(function(result){
    console.log(result.body);
});
```

