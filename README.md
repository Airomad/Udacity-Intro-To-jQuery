# jQuery notes

## Find elements in the DOM
- **$('div')** - Get all divs in the DOM tree.
- **$('.class')** - Get all elements in the DOM tree with provided CSS class name.
- **$('#myid')** - Get the element in the DOM tree with provided id attribute.

## Traverse the DOM
- **$('#node').[children()](http://api.jquery.com/children/)** - Get the children of each element in the set of matched elements, optionally filtered by a selector.
- **$('#node').[find()](http://api.jquery.com/find/)** - Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.
- **$('#node').[parent()](http://api.jquery.com/parent/)** - Get the parent of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').[parents()](http://api.jquery.com/parents/)** - Get the ancestors of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').[siblings()](http://api.jquery.com/siblings/)** - Get the siblings of each element in the set of matched elements, optionally filtered by a selector.
- ##### [All methods in Documentation](https://api.jquery.com/category/traversing/)

## Get the content of the DOM element
- **$('#node').[val()](http://api.jquery.com/val/)** - Get the current value of the first element in the set of matched elements.
- **$('#node').[html()](http://api.jquery.com/html/)** - Get the HTML contents of the first element in the set of matched elements.
- **$('#node').[text()](http://api.jquery.com/text/)** - Get the combined text contents of each element in the set of matched elements, including their descendants.

## Modify the content of the DOM element
- **$('#node').[val("Some value")](http://api.jquery.com/val/)** - Set the value of every matched element.
- **$('#node').[html("`<div>`Some value`</div>`")](http://api.jquery.com/html/)** - Set the HTML contents of every matched element.
- **$('#node').[text("Some value")](http://api.jquery.com/html/)** - Set the text contents of the matched elements.

## Handle events on the DOM
- **$('#node').[change(function)](http://api.jquery.com/change/)** - Bind an event handler to the “change” JavaScript event, or trigger that event on an element.
- **$('#node').[click(function)](http://api.jquery.com/click/)** - Bind an event handler to the “click” JavaScript event, or trigger that event on an element.
- **$('#node').[contextmenu(function)](http://api.jquery.com/contextmenu/)** - Bind an event handler to the “contextmenu” JavaScript event, or trigger that event on an element.
- **$('#node').[dblclick(function)](http://api.jquery.com/dblclick/)** - Bind an event handler to the "dblclick" JavaScript event, or trigger that event on an element.