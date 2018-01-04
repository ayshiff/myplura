# myplura 
[![Build Status](https://travis-ci.org/ayshiff/myplura.svg?branch=master)](https://travis-ci.org/ayshiff/myplura)

A Node.js module that returns the plural form of any noun

## Installation 
```sh
npm install myplura --save
yarn add myplura
bower install plura --save
```
## Usage
### Javascript
```javascript
var plura = require('myplura');
var boys = plura.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'myplura';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var plura = require('myplura');
});
```
## Test 
```sh
npm run test
```
