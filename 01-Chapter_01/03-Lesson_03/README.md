# UD001 - HTML Syntax - `Lesson03`

#### Tags

* Author:      : AH Uyekita
* Chapter      : CSS Syntax
* Start        : 21/12/2018
* Course Title : Intro to HTML and CSS
* COD          : UD001
    * **Instructor:** James Parkes
    * **Instructor:** Cameron Pittman

#### Resources

This is a site with good content about CSS: [CSS Tricks][css_tricks]

[css_tricks]: https://css-tricks.com

********************************************************************************

## Cascading Style Sheets (CSS)

CSS is all about style. It is a powerful way to customize any site, using a separated document.

The CSS has a rule set.

**Example:**
```{css}
div{
text-align: right;
}
```

Where:

* `div`: Is called selector, this is the element you want to customize;
* `{ }`: The declaration block is everything inside of the curly brackets.


#### Adding comments

Adding any comments to a HTML file, you might use the `<!-- This is a comment -->`.

**Example:** HTML file
```html
<!-- This is a comment -->
<div class="example">Words, words, words.</div>
```

Adding a comment to the CSS file, it is quite similar to the SQL comments.

**Example:** CSS file
```css
p {
    color: blue;
}
/* add CSS here */
h1 {
    color: red;
}
```

### Attributes Selector

This stand to the `id` and `class` attributes which some tags could have.

#### `id`

This kind of attribute is only used once per document.

```html
#site-description {
  color: red;
}
```

#### `class`

This attribute could be used several times in the page.

```html
.book-summary {
  color: blue;
}
```
Bear in mind, the class attribute could be "stacked".

**Example:** This example has 3 class attributes in the paragraph tag.
```html
<p class=" teste teste2 book-summary"> My Text! </p>
```

### CSS Units

In CSS there are two kinds of units.

* Absolute: Refer to a fixed unit (pixels);
* Relative: Refer to unit in comparison to another (percentages, em, vh, vw).

### CSS Colors

The colors in CSS are defined by the use the RGB, Hex, etc.

#### RGB

* R: red 0 - 255
* G: green 0 - 255
* B: blue 0 - 255

**Example:**
body {
  background-color: rgb(255, 0, 255);
}

The example above change the background color of the body to green.

#### Hexadecimal

* R: red 00 - FF
* G: green 00 - FF
* B: blue 00 - FF

**Example:**
body {
  background-color: #ff00ff;
}
