# jQuery notes

## Find elements in the DOM
- **$('div')** - Get all divs in the DOM tree.
- **$('.class')** - Get all elements in the DOM tree with provided CSS class name.
- **$('#myid')** - Get the element in the DOM tree with provided id attribute.

## Traversing the DOM
- **$('#node').children()** - Get the children of each element in the set of matched elements, optionally filtered by a selector.
- **$('#node').find()** - Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.
- **$('#node').parent()** - Get the parent of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').parents()** - Get the ancestors of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').siblings()** - Get the siblings of each element in the set of matched elements, optionally filtered by a selector.
- ##### [All methods in Documentation](https://api.jquery.com/category/traversing/)