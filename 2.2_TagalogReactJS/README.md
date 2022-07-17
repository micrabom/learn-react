# Learn React JS - Tagalog
This is for the part 1


<h2> index.js </h2>

``` javascript
import React from 'react';
import ReactDOM from 'react-dom';

import App from './App'

ReactDOM.render(<App />, document.getElementById('root'))
```

<h2> App.css </h2>

```css
html, body{
    padding: 0;
    margin: 0;
}

.root {
    height: 100vh;
}

.app-main{
    height: 100vh;

    /*Layout*/
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.app-main .card-main {
    border:1px solid black;
    height:200px;
    width: 200px;

    /*Layout*/
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```
<h2> App.js </h2>

``` javascript
import React, { useState } from "react";

/* Style */
import './App.css'

/* Component */
import Card from './Card'

const App = () => {
    
    return (
        <>
          <div className="app-main">
             <Card name="bossRambs" age="30" gender="Male" title="Boss Amo"/>
             <Card name="samael" age="35" gender="Male" title="Desire"/>
             <Card name="amenadiel" age="40" gender="Female" title="Warrior"/>
             <Card name="michael" age="35" gender="Male" title="Fear"/>
          </div>
        </>
    )
}

export default App 
```
<h2> Card.js </h2>

``` javascript
import React from "react"

const Card = ({ name, age, gender, title} ) => {
   

    return (
    <div className = "card-main">
        <h1>{title}</h1>
        <div>Name: {name}</div>
        <div>Age: {age}</div>
        <div>Gender: {gender}</div>
    </div>
    )
       
}

export default Card
```

# Tutorial Link


Continue . . .
<br />
[TAGALOG] React JS Tutorial Part 1 - Basic Fundamentals
<br />
https://www.youtube.com/watch?v=LjESmR8NVTA
<br />
19:26