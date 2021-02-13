---
# Simple UseState Hook
---

## Setting up the UseState

### Run useState each time the component is rendered

```javascript
import React, {useState} from 'react'

const [state, setState] = useState(1)
```

### Run only when initializing the component at the start

```javascript
import React, {useState} from 'react'

const [state, setState] = useState(() => {return 1}))
```

## Updating the State

```javascript
// Set new state directly
setState(newState)

// Modifying previous state
setState((prevState) => prevState + 1)
```

---

# Destructuring UseState Hook

---

## Setting up the UseState

```javascript
import React, {useState} from 'react'

const [state, setState] = useState({count: 4, theme: 'blue'})
const count = state.count
const theme = state.theme
```

## Updating the State

When updating the state when the state is destructured, we overwrite the _whole_ state.  
Which means is necessary to take into account all our state properties.

```javascript
// Overwriting the state like this will make us loose the theme property
setState((prevState) => {
  return {count: prevState.count + 1}
})

// We need to return the previous state, and then modify the property we want
setState((prevState) => {
  return {...prevState, count: prevState.count + 1}
})
```

---

# Alternative Solution

---

### We can otherwise define two states, which will make it easier to manage

## Setting up the UseState

```javascript
import React, {useState} from 'react'

const [count, setCount] = useState(1)
const [theme, setTheme] = useState('blue')
```
