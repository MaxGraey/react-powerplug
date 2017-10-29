# Toggle

The Toggle component is used to toggle a boolean. True/false.

```js
import { Toggle } from 'react-powerplug'
``` 

```jsx
<Toggle initial={false}>
  {({ on, toggle }) => (
    <Checkbox
      onClick={toggle}
      checked={on}
    />
  )}
</Toggle>
``` 

## Toggle Props

**initial = false** *(optional)*  
Specifies the initial on state, must be an boolean.
By default, the initial on state is false.

## Toggle Children Props

TL;DR: `{ on, off, toggle, setOn }`

**on**  
`boolean`  
Your on state

**off**  
`boolean`  
Negate your on state

**toggle**  
`() => void`  
Toggle your on state value

**setOn**  
`(value: boolean) => void`  
Set `value` to your on state
