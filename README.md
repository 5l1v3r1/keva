# keva
Object iterator for for...of statements.

# Example Usage
````
const keva = require('keva');

for (var [key, val] of keva({foo: 1, bar: 2})) {
    console.log(key, val);
}
````
````
>foo 1
>bar 2
````
