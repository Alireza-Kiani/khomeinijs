# Khomeini JS
A simple, type-safe, lightweight, blazing-fast package for returning Khomeini's famous quote with your preferred input:
```
    ممد بايد ممد باشد .ممدي كه ممد نباشد ممد نيست.
```
# Usage
Install package:
```
npm i khomeinijs
```
Import function CJS:
```
const generateKhomeiniQuote = require('khomeinijs');
```
or with ESM:
```
import generateKhomeiniQuote from 'khomeinijs';
```
Pass the word to get the statement:
```
generateKhomeiniQuote('دانشگاه')
// Output: دانشگاه بايد دانشگاه باشد .دانشگاهي كه دانشگاه نباشد دانشگاه نيست.