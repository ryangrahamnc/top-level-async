# Top Level Async

Lets you run an async function at the top level of a node app.

Because people are too afraid of writing `;((async()=>{ /* code */ })());`

# Install

`npm i --save top-level-async`

# Usage

```
topLevelAsync = require('top-level-async');
topLevelAsync(async()=>{
    await someFunc();
    console.log('we did it! good job everyone!')
});
```
