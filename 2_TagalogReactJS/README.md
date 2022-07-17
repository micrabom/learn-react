# Learn React JS - Tagalog
This is for the part 1


<h2> index.js </h2>

```javascrript
import React from 'react';
import ReactDOM from 'react-dom';

import App from './App'

ReactDOM.render(<App />, document.getElementById('root'))
```
<h2> App.js </h2>

```javascrript
import React, { useState } from "react";

const App = () => {
    const [count, setCount] = useState(0)
    const [user, setUser] = useState('')

    const increment = () => {
        setCount(count + 1)
    }

    const handleOnChange = (e) => {
        setUser(e.target.value)
    }

    console.log("user: ", user)

    return (
        <>
            <div>Count: {count}</div>
            <button onClick={increment}>Increment</button>
            <br />
            <input name="user" onChange={handleOnChange} value={user} />
        </>
    )
}

export default App
```

# Tutorial Link


Continue . . .
<br />
[TAGALOG] React JS Tutorial Part 1 - Basic Fundamentals
<br />
https://www.youtube.com/watch?v=LjESmR8NVTA
<br />
19:26