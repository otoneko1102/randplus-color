# @randplus/color
Generate random colors.<br>
This package is included in '[randplus](https://www.npmjs.com/package/randplus)'.

## Usage
```js
// Classic
const random = require('@randplus/color');

console.log(random('hex')); // '000000' ~ 'ffffff'
console.log(random('hex', { prefix: '#' })); // '#000000' ~ '#ffffff'
console.log(random('rgb')); // [0, 0, 0] ~ [255, 255, 255]
console.log(color('word')); // 'limegreen'
console.log(color('word', { language: 'ja' })); // '鉄色'
```
```js
// Advanced
const { hex, rgb, word } = require('@randplus/color');

console.log(hex()); // '000000' ~ 'ffffff'
console.log(hex('#')); // '#000000' ~ '#ffffff'
console.log(rgb()); // [0, 0, 0] ~ [255, 255, 255]
console.log(word()); // 'limegreen'
console.log(word('cn')); // '紫磨金'
```

## Get Support
<a href="https://discord.gg/yKW8wWKCnS"><img src="https://discordapp.com/api/guilds/1005287561582878800/widget.png?style=banner4" alt="Discord Banner"/></a>