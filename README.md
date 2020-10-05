# Decimal Number to Words

This Package is an implementaion of an existing package, number-to-words. It's purpose is to convert numbers into words.

## Install
```cmd
npm install number-to-words 
```

## How to use

##### toOrdinal(number)
> Converts an integer into a string with an ordinal postfix.
```js 
var convert = require('decimal-number-to-words');
convert.toOrdinal(21); // => “21st”
```
##### toWords(number)
> Converts an integer into words.
```js 
var converter = require('number-to-words');
converter.toWords(13); // => “thirteen”
 
// Decimal numbers:
converter.toWords(2.9); // => “two point nine”
 
// Negative numbers:
converter.toWords(-3); // => “minus three”
 
// Large numbers:
converter.toWords(9007199254740992); // => “nine quadrillion, seven trillion, one hundred ninety-nine billion, two hundred fifty-four million, seven hundred forty thousand, nine hundred ninety-two”
```
##### toWordsOrdinal(number)
> Converts a number into ordinal words.
```js 
var converter = require('number-to-words');
converter.toWordsOrdinal(21); // => “twenty-first”
```