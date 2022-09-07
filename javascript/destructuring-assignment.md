# Destructuring assignment

Destructuring assignment is a special syntax introduced in ES6 that allows us to “unpack” arrays or objects into a bunch of variables, as sometimes that’s more convenient.

Destructuring also works great with complex functions that have a lot of parameters, default values, and so on. Soon we’ll see that.

- Here’s an example of how an array is destructured into variables:
```sh
// we have an array with the name and surname
let arr = ["John", "Smith"]

// destructuring assignment
// sets firstName = arr[0]
// and surname = arr[1]
let [firstName, surname] = arr;

alert(firstName); // John
alert(surname);  // Smith
```

- The destructuring assignment also works with objects.
```sh
let options = {
  title: "Menu",
  width: 100,
  height: 200
};

let {title, width, height} = options;

alert(title);  // Menu
alert(width);  // 100
alert(height); // 200
```
