# indefinitely
a promise that never resolves

useful for debugging and adding breakpoints

```javascript
import indefinitely from 'indefinitely'

async function somethingYoureDebugging () {
  // doing some stuff
  await indefinitely
  console.log('this never gets called')
}
```


