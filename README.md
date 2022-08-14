# Mini Console
A javascript module that abbreviates the Console methods.

Nothing more than a quick way to display messages on the console using less characters.

## Install

### NPM
```bash
npm install mini-console --save-dev
```

### Yarn
```bash
yarn add -D mini-console
```

### Build
```bash
git clone https://github.com/JunaidSikander/mini-console.git 
cd mini-console
```

## Usage

```js
const { cl, cw, ce } = require('mini-console');
// Or using ES2015 imports if you come from the future:
// import { cl, cw, ce } from 'consl';

// console.log
cl('Outputs a message to the Console.');
cl('First', 'Second', 'Third');
cl([1, 2, 3, 4], { a: 1, b: 2, c: 3 });
// console.warn
cw('Outputs a warn message to the Console.');
// console.error
ce('Outputs a error message to the Console.');
// console.info
ce('Outputs a info message to the Console.');
```

## Methods

* `cl -> console.log`
* `cw -> console.warn`
* `ce -> console.error`
* `ci -> console.info`
* `cd -> console.dir`
* `ct -> console.time`
* `cte -> console.timeEnd`
* `ctr -> console.trace`
* `ca -> console.assert`
* `cC -> console.Console`
