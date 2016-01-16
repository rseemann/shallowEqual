# shallowEqual

Dependency free shallow comparison tool to compare one level deep objects's properties.

**Deeply** inspired by https://github.com/facebook/fbjs/blob/master/src/core/shallowEqual.js

## Installation

`npm i --save https://github.com/rseemann/shallowEqual.git`

## Usage

Simple Usage

```javascript
import shallowEqual from 'shallowEqual';

const objFoo = {foo: 'foo'};
const arrFoo = ['foo', 'foo2'];

console.log(objFoo == {foo: 'foo'}); //false
console.log(arrFoo == ['foo', 'foo2']); //false

console.log(shallowEqual(objFoo, {foo: 'foo'})); //true
console.log(shallowEqual(arrFoo, ['foo', 'foo2'])); //true

```

## Motivation

Very lightweight script to use at pure rendering react components




