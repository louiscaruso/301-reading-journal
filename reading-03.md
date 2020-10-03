# Flex Box and tempating

## JavaScript Template
- Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. 
- The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

## Mustache
- Mustache is a logic-less template syntax
- It can be used for HTML, config files, source code or anything.
-It is often referred to as “logic-less” because there are no if statements
```Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
```
## Flex box
- Display defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.
```.container {
  display: flex; /* or inline-flex */
}
```
- Flex direction
```.container {
  display: flex; /* or inline-flex */
}
```
  - row: left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top
- Flex wrap default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.
```
.container {
  flex-wrap: nowrap | wrap | wrap-reverse;
}
```
  - nowrap (is the default): all flex items will be on one line
wrap: flex items will wrap onto multiple lines, from top to bottom.
wrap-reverse: flex items will wrap onto multiple lines from bottom to top.
- Flex-flow is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap. 
