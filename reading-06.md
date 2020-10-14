# Node.JS

- What is it 
  - Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine 
    - The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers
- Installing locally
  - Terminal Commands
```
npm init -y
npm install lodash --save
```
  - Create a test.js file
    - Input this:
    ```
    const _ = require('lodash');

const arr = [0, 1, false, 2, '', 3];
console.log(_.compact(arr));```



