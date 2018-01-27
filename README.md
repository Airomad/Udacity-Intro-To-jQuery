# jQuery notes

## Find elements in the DOM
- **$('div')** - Get all divs in the DOM tree.
- **$('.class')** - Get all elements in the DOM tree with provided CSS class name.
- **$('#myid')** - Get the element in the DOM tree with provided id attribute.

## Traverse the DOM
- **$('#node').children()** - Get the children of each element in the set of matched elements, optionally filtered by a selector.
- **$('#node').find()** - Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.
- **$('#node').parent()** - Get the parent of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').parents()** - Get the ancestors of each element in the current set of matched elements, optionally filtered by a selector.
- **$('#node').siblings()** - Get the siblings of each element in the set of matched elements, optionally filtered by a selector.
- ##### [All methods in Documentation](https://api.jquery.com/category/traversing/)

## Get the content of the DOM element
- **$('#node').val()** - Get the current value of the first element in the set of matched elements.
- **$('#node').html()** - Get the HTML contents of the first element in the set of matched elements.
- **$('#node').text()** - Get the combined text contents of each element in the set of matched elements, including their descendants.

## Modify the content of the DOM element
- **$('#node').val("Some value")** - Set the value of every matched element.
- **$('#node').html("<div>Some value</div>")** - Set the HTML contents of every matched element.
- **$('#node').text("Some value")** - Set the text contents of the matched elements.