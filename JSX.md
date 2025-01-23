# JSX(JavaScript XML)
1. JSX stands for JavaScript XML(extensible Markup Language).
2. It is a syntax extension for JavaScript that allows us to write HTML - like code directly within JavaScript.
# HTML - Like Synatx:
1. `const element = <h1>Hello JSX</h1>`
# Embedding Expression
1. It allows embedding JavaScript expressions within curly braces `{}`.This enables dynamic content rendering and logic within JSX.
```
const name = "Hello"
const element = <h1>Hello {name}</h1>
```
# Babel Compilation
1.JSX is not directly understood by browser,so it need to be transpiled into regular JavaScript using Babel, which converts JSX into `React.createElement()` calls.
### JSX: 
```
const element =<h1>Hello JavaScript</h1>
```
## Transpiled Babel into
```
const element = React.createElement('h1',null,'Hello JavaScript')
``` 

