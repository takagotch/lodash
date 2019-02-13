### lodash
---
https://github.com/lodash/lodash

https://lodash.com/

```html
<script src="lodash.js"></script>
```

```sh
npm i -g npm
npm i --save lodash
```

```js
var _ = require('lodash');
var _ = require('lodash/core');
var fp = require('lodash/fp');

var array = require('lodash/array');
var object = require('lodash/fp/object');

var at = require('lodash/at');
var curryN = require('lodash/fp/curryN');


_.chunk(['a', 'b', 'c', 'd'], 2);
_.chunk(['a', 'b', 'c', 'd'], 3);

_.compact([0, 1, false, 2, '', 3]);

var array = [1];
var other = _.concat(array, 2, [3], [[4]]);

_.times(3, String)
_.times(4, _.constant(0));
```

