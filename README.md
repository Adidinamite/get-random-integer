# Description

This is the best javascript library to generate a random integer.

## Installation
```bash
npm install get-the-best-random-integer
```

## Usage

```javascript
import React, {useState} from 'react';
import {getRandomInteger} from "get-random-integer";
function App() {
    const [integer, setInteger] = useState(undefined);
    const handleOnClick = () =>  setInteger(getRandomInteger());
  return (
    <div className="App">
     <h1>{integer}</h1>
        <button onClick={handleOnClick}>Get integer</button>
    </div>
  );
}

export default App;

```