# Props
- **Props is a property of component which can be passed from one component to another or other component.It is way to transfer from one component to another component.**
- **We can only pass,props from parent component to child component.To recieve props(data) from child component to parent,we have to create function in parent and pass as a props in child.**
- **With the help of pops we can pass.**
1. Variable:numbers,decimals,string, character
2. Objects
3. functions
4. Array,String{anything}
5. State
# Parent Component:
- **Parent component is a component where the another component render.**
# Child Component:
- **Let say we have `Person.jsx` and Person.jsx is render inside `App.jsx` then `Person.jsx` is known as chld component**
```
/////App.jsx
import React from 'react'
import Person from './assets/Person'
import Mobile from './assets/Mobile'
  const App = () => {
      return (
  <>
  <Person name="Person_1" age={100} salary={100000}/>
  <Person name="Person_2" age={150} salary={200000}/>
  <Person name="Person_3" age={200} salary={300000}/>
  </>
  )}
export default App
////
//? Example-1 of Props
// const Person = (props) => {
//   return (
//     <>
//         <h1>Name:-{props.name}</h1>
//          <h1>Age:-{props.age}</h1>
//     </>
//   )}
export default Person
//? Example-2 of Props Using Destructuring
const Person = ({name,age,salary}) => {
    return (
      <>
          <h1>Name:-{name}</h1>
           <h1>Age:-{age}</h1>
           <h1>Salary:-{salary}</h1>
      </>
    )}
export default Person
```
# Graphical representation of props
![image](https://github.com/user-attachments/assets/311a6811-578c-47ef-aa65-ad844b4cb61b)
