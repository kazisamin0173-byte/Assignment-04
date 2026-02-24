1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: getElementById - selects one element using its id.

getElementsByClassName - selects multiple elements using a class name (live collection).

querySelector - selects the first element that matches a CSS selector.

querySelectorAll - selects all elements that match a CSS selector.

2. How do you create and insert a new element into the DOM?

Ans:
1.Create the element - using document.createElement()
2 . Add content or attributes - like text, class, id, etc.
3️. Insert it into the DOM - using methods like appendChild(), append()

3. What is Event Bubbling? And how does it work?

ans: Event Bubbling is a behavior in JavaScript where an event triggered on a child element automatically moves upward to its parent elements in the DOM.It means when an event happens on a specific element, it doesn’t stay there, it also affects its parent elements step by step until it reaches the top of the document.

4. What is Event Delegation in JavaScript? Why is it useful?
ans:Event Delegation is a technique in JavaScript where instead of adding event listeners to multiple child elements, we add a single event listener to their parent element and handle events using event bubbling.When a child element is clicked, the event bubbles up to the parent, and the parent handles it.


5.  What is the difference between preventDefault() and stopPropagation() methods?

ans: preventDefault() is usited to stop the default behavior of an element.It can stop a form from submitting or a link from opening.
stopPropagation() is used to stop the event from moving to parent elements in the DOM. It prevents event bubbling.

