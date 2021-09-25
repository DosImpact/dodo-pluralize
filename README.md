[![Build Status](https://app.travis-ci.com/DosImpact/dodo-pluralize.svg?branch=master)](https://app.travis-ci.com/DosImpact/dodo-pluralize)
[![Coverage Status](https://coveralls.io/repos/github/DosImpact/dodo-pluralize/badge.svg?branch=master)](https://coveralls.io/github/DosImpact/dodo-pluralize?branch=master)

<!-- [![npm version](https://badge.fury.io/js/mypluralize.svg)](https://badge.fury.io/js/mypluralize) -->

# mypluralize
A Node.js module that returns the plural or singular form of any noun

## Installation 
```sh
npm install mypluralize --save
yarn add mypluralize
bower install pluralize --save
```

## Usage

### JavaScript

```javascript
var pluralise = require('mypluralize');
var boys = pluralise.getPlural('Boy');
console.log(boys);

var thief = pluralise.getSingular('Thieves');
console.log(thief);
```
```sh
Output should be 'Boys'
Output should be 'Thief'
```

### TypeScript
```typescript
import { getPlural } from 'mypluralize';
console.log(getPlural('Goose'))
console.log(getSingular('Guns'))
```
```sh
Output should be 'Geese'
Output should be 'Gun'
```

### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('mypluralize');
});
```

## Test 
```sh
npm run test
```

## CI