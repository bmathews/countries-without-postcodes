# Countries without postcodes
JS object containing country codes of countries that don't have postcodes

## Install
```
npm install countries-without-postcodes
```

## Usage

```js
const countries = require('countries-without-postcodes');

// US has postcodes
const hasUS = !!countries['US']; // false

// Bahamas does not
const hasBH = !!countries['BS']; // true
```
