# auto-line-breaks
A Node.js extension that adds automatically line breaks

### Why?
Because I using it for adding lines in a discord.js bot that makes text in a part of a picture

## Utilisation:
Simply call the module with the require:
```js
var autoLineBreak = require('auto-line-breaks');
```

Then use it as a function:
```js
// Make a text
var text = "Hello I'm a text, and I love you so much!";
// Then define the length of a line by defining a number of characters in a line
var lineLength = 10

console.log(text) // Output: "Hello I'm a text, and I love you so much!"

var result = autoLineBreak(text, lineLength) // calls the function and store in a variable

console.log(result)
/* Output:
"Hello I'm a
text, and -
I love you -
so much!"
*/
```

## Contributing
You're clairy welcome! Join the [github repo](https://github.com/GreepTheSheep/auto-line-breaks)