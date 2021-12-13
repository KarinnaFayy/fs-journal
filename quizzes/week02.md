# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var
let
const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
function:  a body of code that returns a value. The value returned may depend on arguments provided to the function. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S — Single responsibility principle
O — Open closed principle
L — Liskov substitution principle
I — Interface segregation principle
D — Dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index[2]
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
????
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
function getImage(happy) {

    let image = "";
    if (happy <= 10) {
        image = "https://thumbs.gfycat.com/WarpedAchingHagfish-size_restricted.gif"
    }
    else {
        image = "https://media3.giphy.com/media/l0E9CrSVVI3g4/giphy.gif"
    }
    return image;
    update()
}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The incrementor...i++

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The Document Object Model (DOM) is a programming API for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated.

```

**9.** What are the `5` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
strings, numbers, booleans, undefined, and null.

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Argument is the actual value of this variable that gets passed to function. A parameter is something you have to fill in when you call a function.

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
The difference is that primitive variables store the actual values, whereas reference variables store the addresses of the objects they refer to.

```