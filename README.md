### Answer of all the questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
  getElementById() -> we can get an element containing a specific Id and access its content by storing in a variable.<br>
  getElementsByClassName() -> We can get all the elements of same class name as HTML Collection and access its content.<br>
  querySelector() -> We can get the first element that matches a CSS selector.<br>
  querySelectorAll() -> We can get all elements that matches the specific CSS selector as NodeList.<br>

### 2. How do you create and insert a new element into the DOM?
  1st, we have to create the element. 2nd, we have to add attributes. 3rd, we have to append the attribute to the newly created element. For Example:

     const newDiv = document.createElement("div");
     newDiv.innerText = "Hello World!";
     document.body.appendChild(newDiv);

### 3. What is Event Bubbling? And how does it work?
  Event Bubbling is when an event starts at the child element and propagates upward through its parent.

### 4. What is Event Delegation in JavaScript? Why is it useful?
  Event Delegation is adding a single event listener to a parent element to handle events from its children.<br>
  It is useful because we dont have to add event listener to every child. As a result we can save many lines of code.

### 5. What is the difference between preventDefault() and stopPropagation() methods?
  preventDefault() -> It cancels the browser's default behavior.<br>
  stopPropagation() -> It stops the event from going up to parent elements.