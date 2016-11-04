# node-detect-heroku
(extremely) simple node module to detect if we're running on Heroku or not

```
const WE_ARE_ON_HEROKU = require('node-detect-heroku');
console.log(`Are we running on Heroku ? ${WE_ARE_ON_HEROKU ? 'yes' : 'no'}`);
```
