# is-empty

Simple Empty Object Checker.

```bash
npm i @jellybeanci/is-empty
```

### import module

```js
// ES6 Syntax
import {isEmpty} from "@jellybeanci/is-empty";

// Commonjs Syntax
const {isEmpty} = require("@jellybeanci/is-empty");
```

### usage

```js
const myObject = {};
isEmpty(myObject); // true

const person = {name: "Göksel", surname: "KÜÇÜKŞAHİN"};
isEmpty(person); // false
```

### types

```ts
type isEmpty = (object: Object) => boolean;
```