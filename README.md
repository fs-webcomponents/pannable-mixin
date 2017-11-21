# pannable-mixin

Web Component mixin that makes elements pannable. By default it will add mouse
event listeners to the element and apply a CSS transform to it whenever it's
dragged. You can change the element that the tranform is applied to by calling
`setPanningElement()`. Note that this doesn't change where the mouse event
listeners are applied.
