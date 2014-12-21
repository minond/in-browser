check if you're currently in a browser (as opposed to being in node)

#### intalling

`npm i in-browser`

#### usage

```js
var in_browser = require('in-browser');

if (in_browser) {
    // code for clients only
} else {
    // code for servers only
}
```
