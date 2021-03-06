# extend
Merge two or more objects together. A vanilla JavaScript equivalent of jQuery's `.extend()` function.

[Download extend](https://github.com/cferdinandi/extend/archive/master.zip)

<hr>

### Want to learn vanilla JavaScript? Check out ["The Vanilla JS Guidebook"](https://gomakethings.com/vanilla-js-guidebook/) and level-up as a web developer. 🚀

<hr>


## Getting Started

### 1. Include extend on your site.

Include the code in your script, or load it as an external file.

```js
var extend = function () {
	...
};
```

### 2. Extend your objects

Pass in two or more objects to extend. For a deep or recursive merge, set the first argument to `true`.

```js
// Example objects
var object1 = {
    apple: 0,
    banana: { weight: 52, price: 100 },
    cherry: 97
};
var object2 = {
    banana: { price: 200 },
    durian: 100
};
var object3 = {
    apple: 'yum',
    pie: 3.214,
    applePie: true
};

// Create a new object by combining two or more objects
var newObjectShallow = extend( object1, object2, object3 );
var newObjectDeep = extend( true, object1, object2, object3 );
```



## Browser Compatibility

extend works in all modern browsers, and IE 6 and above.



## How to Contribute

Please review the [contributing guidelines](CONTRIBUTING.md).



## License

The code is available under the [MIT License](LICENSE.md).
