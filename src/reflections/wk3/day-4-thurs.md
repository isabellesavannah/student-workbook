What problems does the Observer Pattern seek to solve?
>The need for lots of 'push' and pull making things sloppy

What are the three mechanisms of the observer pattern?
>Enables one-to many data binding between elems
>Event Driven
>Build reusable code

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
>The proxystate is in charge of taking in changes which triggers an event listener that changes the dom, proxy takes info in from services that takes info from controller that deals with what the user interacts with