## Languages:
```ts
import { languages } from 'wraith';

console.log(
  languages.join(', ')
);
```
```sh
> node --loader ts-node/esm .
# JavaScript, TypeScript, HTML, CSS, PHP, Python, GO, Java, C++, C#, R, Ruby, Elm, Scala, Rust, CoffeScript
```
## Frameworks:
```php
include 'wraith.php';

echo $framework;
```
```sh
> php -f framework.php
# React, EJS, Rails, Laravel, Django, ASP.NET, Express, Spring, Angular, Ember, Vue, Svelte and so more...
```
## Projects:
```js
const fs = require('node:fs');

const arg = process.argv[2]?.replace('--', '');

;(async function () {
  const { Projects } = JSON.parse(
    await fs.readFileSync('./Wraith.js', 'utf-8')
  );
  console.log(
    Projects[
      arg || 'all'
    ]
  );
})();
```
```sh
> node .
# FATAL ERROR: CALL_AND_RETRY_LAST Allocation failed - JavaScript heap out of memory ( a.k.a so much projects )

> node . --best
# wafoen.com
```
