# require-any
Automatically install dependencies, allow registering of require paths and "unrequiring".

### Usage
#### Registration
```js
const requireAny = require('require-any');
requireAny.register();
```

#### Install
Installing a missing dependency, e.g. `request` when it has not been npm installed.
```js
const request = require('request');
```

#### Unrequire


#### Register Dependency