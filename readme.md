# Arrow Key Controller

A simple, lightweight controller designed for canvas games that only uses the arrow keys. When an arrow key is pressed down, it is true.

## Install

`$ npm install arrow-key-controller`

## Use It

```javascript
import { Controller } from 'arrow-key-controller';

const controller = new Controller();

controller.init(); // adds event listener to document

controller.up; // false
controller.down; // false
controller.right; // false
controller.left; // false
```
