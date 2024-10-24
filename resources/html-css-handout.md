# HTML & CSS Cheatsheet

## HTML Documents

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
    <head>
        <meta charset="utf-8">
        <title>Site title</title>
    </head>
    <body>
      <h1>Welcome to my site!</h1>
    </body>
</html>
```

### HTML elements

```html
<p>Hello, World!</p>
```

- `<p>` Opening tag - angle brackets and element label (`p` for paragraph)

- `Hello, World!` : Element contents

- `</p>`: closing tag

Elements can be nested inside one another. The interior elements are said to be children of the parent element.

```html
<p>In this paragraph <em>some text is italicized</em> and some isn't.</p>
```

Attributes inside the opening tag provide functionality or metadata:

```html
<a href="https://www.brynmawr.edu/">Bryn Mawr College Website</a>
```

Some elements, such as `img` (an image) don't require closing tags

```html
<img src="/assets/images/pic.png" alt="a description of the image"/>
```

## CSS: Cascading Style Sheets

- Cascading: later rules override earlier ones

- Specificity: more specific selectors override less specific ones

- Inheritance: some CSS properties are inherited from parent elements

### CSS rulesets

```css
p {
  color: red;
  font-size: 42px;
}
```

- `p`  a selector -- tells which elements in the html this rule corresponds to

- `{ }` curly braces enclose the whole ruleset

- `color:`  a property, followed by a colon

- `red;` a value, followed by a semicolon

- `font-size: 42px;` each additional rule is on a new line

### CSS + HTML

To link your CSS to your html: in the 'head' section of the document, include a link that refers to the location of your stylesheet

```html
<link rel="stylesheet" type="text/css" href="style.css">
```

### Classes and IDs

You can make your elements easier to style by using classes and IDs. 

**Class** - a category of elements that can share style attributes: `.frogs`

**ID** - a single element, more specific than a class: `#poison-dart-frog`

Here's how class and ID selectors look in CSS:

```css
.frogs {  /* class */
  color: green;
}
#poison-dart-frog {    /* ID */
  color: blue;
}
```

In HTML, they are added as attributes:

```html
<p class="frogs">Frogs are interesting</p> <!-- class -->
<p id="poison-dart-frog">Some are poisonous</p> <!-- ID -->
```