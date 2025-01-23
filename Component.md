# Component
- **In React, a component is the fundamental building block for building user interfaces. Components allow you to split the UI into reusable, independent pieces, and manage each part in isolation.**
- **There are two main types of components:**
## Functional Component:
```
import React from 'reat'
const Greeting = () =>{
return (
<>
<h1> Hello JavaScript </h1>
</>
)
}
export default Greeting;
```
## Class Components:
```
import React {Component} from 'react';
class Greeting extends component{
render(){
return (
<>
<h1> Hello JavaScript </h1>
</>
)
}
}
export default Greeting;
```
# Reusable Component:
```
////Person.jx
const Person = ()=>{
return (
<>
<h1> Hello JavaScript </h1>
</>
)}
export default Person;
////App.jsx
import Person from './Person.jsx'
const App = ()=>{
return(
<>
<Person/>
<Person/>
<Person/>
</>
)}
export default App;
//// Output:
Hello JavaScript
Hello JavaScript
Hello JavaScript
```
![image](https://github.com/user-attachments/assets/4347fd5f-11c6-41e6-a6d3-89674f2396f7)
