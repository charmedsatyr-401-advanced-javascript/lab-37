![cf](http://i.imgur.com/7v5ASc8.png) LAB
============================================================================    

## Lab 37: Login and Authentication

### Author: Joseph Wolfe

### Links and Resources
* [PR](https://github.com/charmedsatyr-401-advanced-javascript/lab-37/pull/1)
* [![Build Status](https://travis-ci.com/charmedsatyr-401-advanced-javascript/lab-37.svg?branch=submission)](https://travis-ci.com/charmedsatyr-401-advanced-javascript/lab-37)
* [Netlify]()

### Modules
```
##### FILE TREE

```
### Summary
The application has been refactored to be fully modular and use the React Context API for functionality. Context wrappers only provide the appropriate context to their children; I intentionally avoided providing global context.

`index.js` renders `<App/>`.
`<App/>` renders component `<ToDo/>`.

The `<ToDo/>` component is a function component that receives context from its class component context providers `<ToDoProvider/>`.

`./src/components/todo/` contains all files related to `<Todo/>`. Its `index.js` renders `<Count/>`, `<AddToDo/>`, and `<List/>`. The `<ToDo/>` component uses `<If/>` from `./src/components/if/index.js` for some conditional logic.

#### Tests
* What assertions were made?
  * A placeholder test is in place.

* What assertions need to be / should be made?
  * Snapshot and functional tests could be made for each component.
  * Tests could ensure each component properly receives and handles its context.

#### UML
![UML](assets/uml.jpg)  
