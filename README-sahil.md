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
  const onComponentMount = async () => {
    // code here (making this function async is optional)
  }
  onComponentMount()
}, [])



// case 2
const [state1, setState1] = useState('Sahil Rajput')
const [state2, setState2] = useState('Sahil Rajput')

useEffect(() =>{
  // code here
}, [state1, state2])



// case 3
const [state, setState] = useState({name: 'Sahil Rajput'})

useEffect(() => {
  // code here
}, [state?.name])
````
