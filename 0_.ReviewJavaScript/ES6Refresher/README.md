# ES6 Refresher 
<br>

## The this keyword
 - - - -
```javascript
const person = {
 name:"Mosh",
 walk(){
 
    console.log(this);    
    }        I
};

person.walk();
const walk=person.walk;
walk();
```
## Binding this
 - - - -
```javascript
const person={
  name:"Mosh",
 walk(){
 }
    console.log(this);
};
person.walk();
const walk = person.walk.bind(person);
walk();
```
## Arrow Functions
 - - - -
```javascript
const square = function(number){
    return number*number;
}
```
<h2>👇</h2>

```javascript
const square= number => number * number;   
```

<br><br><br><br><br><br><br><br>
 - - - -
 ---
[Bookmark Link](https://codewithmosh.com/courses/357787/lectures/5634563)
 <br>
→ Currently in ES6 #7
 <br>
 - - - -
  ---