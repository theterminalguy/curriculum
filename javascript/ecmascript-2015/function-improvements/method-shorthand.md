---
author: alexjmackey

levels:
  - beginner

type: normal

category: must-know

inAlgoPool: false

links:
  - '[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions){website}'

---
# Method Shorthand

---
## Content

ES6 method shorthand allows us remove the function key word and colon making code more succinct.

For example prior to ES6 you would have written something similar to the below:

```javascript
return {
   func: function func() {
   ...
   }
};
```

With ES6 this can now become:

```javascript
return {
    func() {
    ...
    }
};
```

---
## Practice

Consider the function `sayHi` which is supposed to log the `Hi` message.
Likewise, the `sayHello` function should log the `Hello` message.

Complete the following snippet such that the both functions are defind within the object `return`ed, using method shorthand in both cases:

```javascript
return {
 ??? {
   console.log('Hi')
 },
 ??? ??? {
   console.log('Hello)
 }
}
```

* sayHi()
* sayHello
* ()
* function
* sayHi: function()
* sayHello:
* function()
* sayHello: function()

---
## Revision

Fill in the missing gaps of the following snippet such that it makes use of method shorthand:

```javascript
return {
  ??? ??? {
    ...
  }
}
```

* func
* ()
* func:
* function func()
* func()
* () =>
 
