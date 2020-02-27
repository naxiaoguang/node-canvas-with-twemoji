# node-canvas-with-twemoji

## Installation
xxx

## Quick Example
```javascript
const { createCanvas } = require('canvas');
const { fillTextWithTwemoji } = require('node-canvas-with-twemoji');

async function main () {
    const canvas = createCanvas(200, 200);
    const context = canvas.getContext('2d');

    context.textBaseline = 'top';

    context.fillStyle = '#000000';
    context.font = '30px Arial';
    await fillTextWithTwemoji(context, '😉', 10, 10);
}

main();
```

## Dependencies

- node-canvas [GitHub](https://github.com/Automattic/node-canvas)
- twemoji-parser [GitHub](https://github.com/twitter/twemoji-parser)

## Licence

### node-canvas-with-twemoji

Copyright (c) 2020 cagpie <cagpie@gmail.com>

Code licensed under the MIT License: http://opensource.org/licenses/MIT
