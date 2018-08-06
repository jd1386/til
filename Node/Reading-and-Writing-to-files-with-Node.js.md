### Reading and Writing to files with Node.js

#### Writing to Files

```javascript
const fs = require('fs');

fs.writeFile('temp.txt', data, (err, data) => {
  if (err) console.log(err);
  console.log("Successfully written to file");
})
```





#### Reading from files

```javascript
const fs = require('fs');

fs.readFile('temp.txt', 'utf-8', (err, buf) => {
  console.log(buf.toString());
});
```











https://tutorialedge.net/javascript/nodejs/reading-writing-files-with-nodejs/