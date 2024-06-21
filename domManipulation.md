# DOM Manipulation
<!-- > ## DOM manipulation in ` Browser Console ` -->
> #### [!IMPORTANT] What is DOM
> The DOM ` Document Object Model ` represents a document with a logical tree\
> It allow us to maniplute/change webpage content ` HTML Elements `


## Properties

> #### [!TIP] innerText
> Shows the visible text contained in a node
 
> #### [!TIP] innerHTML
> Shows the full markup
 
> #### [!TIP] textContent
> Shows the full text
 

## Methods

> [!WARNING]
> These Commands works Only in ` Browser Console `

> ### View Global Object
```js
console.log(this) // Window
```
> ### View Document Object
```js
console.log(document)
console.dir(document) // array format
```

> ### Get Element by Tag
```js
document.getElementById("id") 
```

docum
> ### Get Element by Class
```js
document.getElementsByClassName("class")
```

> ### Get Element by TagName
```js
document.getElementsByTagName("img")
```

### Query Selector

```js
document.querySelector('p') // select first p element
document.querySelector('#myId') // select first element with id = "myId"
document.querySelector('.myClass') // select first element with class = "myClass"

document.querySelectorAll('p') // select all p elements
```

