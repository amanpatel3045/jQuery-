jQuery selectors are one of the most important parts of the jQuery library.

jQuery Selectors
jQuery selectors allow you to select and manipulate HTML element(s).

jQuery selectors are used to "find" (or select) HTML elements based on their name, id, classes, types, attributes, values of attributes and much more. It's based on the existing CSS Selectors, and in addition, it has some own custom selectors.

All selectors in jQuery start with the dollar sign and parentheses: $().

The element Selector
The jQuery element selector selects elements based on the element name.

You can select all <p> elements on a page like this:
  ```
  $("p")
  ```
  
  Example

When a user clicks on a button, all <p> elements will be hidden:
  
  ```
  <!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").hide();
  });
});
</script>
</head>
<body>

<h2>This is a heading</h2>

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

<button>Click me to hide paragraphs</button>

</body>
</html>
```
  OUTPUT
  This is a heading
This is a paragraph.

This is another paragraph.

Click me to hide paragraphs
