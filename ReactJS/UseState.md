# Simple UseState Hook

## Setting up the UseState

### Run useState each time the component is rendered

```javascript
import React, {useState} from 'react'

const [state, updateState] = useState(1)
```

### Run only when initializing the component at the start

```javascript
import React, {useState} from 'react'

const [state, updateState] = useState(() => {return 1}))
```

## Updating the State

```javascript
// Set new state directly
update(newState)

// Modifying previous state
update((prevState) => prevState + 1)
```

# Destructuring UseState Hook
