# myplura  👫
[![Build Status](https://travis-ci.org/ayshiff/myplura.svg?branch=master)](https://travis-ci.org/ayshiff/myplura)
[![Coverage Status](https://coveralls.io/repos/github/ayshiff/myplura/badge.svg?branch=master)](https://coveralls.io/github/ayshiff/myplura?branch=master)

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

## Test 
```sh
npm run test
```
