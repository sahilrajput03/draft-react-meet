# Cases of licycles

**Suggestions, questions, cases, complex cases(be specific with code)**

- **Sahil**

3 Cases of executes side effects:
- on component mount
- on state change
- on particular change of property of state

Code

```js
// case 1
useEffect(() =>{
  const onComponentMount = () => {
    // code ehre
  }
  onComponentMount()
}, [])


// case 2
useEffect(() =>{
  // code here
}, [state1, state2])
````
