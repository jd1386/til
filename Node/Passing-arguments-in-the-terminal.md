### Passing arguments in the terminal



```javascript
// npm i yargs
const arg = require('yargs').argv;

let city = argv.c || 'New York';

// Run program with an argument
node index.js -c Boston
```

