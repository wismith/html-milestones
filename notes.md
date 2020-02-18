
## HTML

#### Elements:
Elements are designators that define the structure and content of objects within a page.
- Heading levels
- Paragraphs
- `<div>`
- `<span>`
- `<strong>`
- `<em>`

#### Tags
The use of angle brackets surrounding an element creates a tag.

Examples:
`<a>element</a>`

#### Attributes
Attributes are properties used to provide additional information about an element.  The most common attributes include:
- `id`, which identifies an element
- `class` attribute, which classifies an element
- `src` attribute, which specifies a source for embeddable content
- `href` attribute, provides hyperlink reference to a linked resource

Example:
`<a href="http://shayhowe.com/">Shay Howe</a>`

### Common HTML Setup:
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Hello World</title>
    </head>
    <body>
      <h1>Hello World</h1>
      <p>This is a web page.</p>
    </body>
  </html>


## CSS
See [CSS Zen Garden](http://www.csszengarden.com/) for cool CSS usage.

#### Selectors:
A selector designates exactly which element within the HTML to target an apply styles to.  Generally, they target an attribute value, or a type of element.

Within CSS, selectors are followed with curly brackets, which encompass the styles to be applied:

`p { ... }`

#### Properties
Once an element is selected a property determines the styles that will be applied to that element.
- `background`
- `color`
-  `font-size`
- `height`
- `width`

Example:

  p {
    color: ...;
    font-size: ...;
  }

#### Values
So far, we've selected an element with a selector and determined what style we'd like to apply with a property. Now, we can determine the behavior of that property with a value.

  p {
    color: orange;
    font-size: 16px;
  }
