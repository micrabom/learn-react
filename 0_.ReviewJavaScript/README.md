# Review JavaScript


## Print Hell World
```javascript
<body>
  <h1>Hello World</h1>
  <script>
    // This is my first JavaScript code!
    console.log('Hello World');
</script>
```

## Separation Concern

### index.html
```html
<body>
  <h1>Hello World</h1>

  <script src="index.js"></script>
</body>
```
### index.js
```javascript
console.log('Hello World');
```

## JavaScript Node
Run time execution for javascript

```html
node index.js
<!-- Output 
Hello World -->
```

## Variables
sudlanan sa mga variables

### index.js
```javascript
let name = 'Rab';

console.log(name);
// Output:
// Rab
```
## Objects
Using let and const
### index.js
```javascript
let person={
  name:'Mosh',
  age:30
};

// Dot Notation
person.name='John';
// Bracket Notation
let selection = 'name';
person['name']='Mary';

console.log(person.name);
```
## Arrays

```javascript
let selectedColors = ['red','blue'];
selectedColors[2] = 1;

console.log(selectedColors.length);
```
## function

```javascript
function greet(hame){
  console.log('Hello World');
}
greet();
```

```javascript
function greet(name){
  console.log('Hello' + name);
}
greet('John');
greet('Mary');
                      
```



