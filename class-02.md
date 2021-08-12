# Class 02 - Reading Notes

## Text (HTML)

  Text in html has many types of ways to 'markup' or 'tag' sections of text to help with how the text is displayed
  - `<h1>, <h2>, .., <h6>` - there are six rankings of heading tags, though the first two are the most used. h1's are main headings and h2's are subheadings
  - `<p>` - paragraph tags without any modification display text in the browser on a new line
  - `<b>, <i>` - these tags can surround one character or limitless characters and have default appearance looks. The <b> will bold and the <i> will italicize text
  - `<sup>, <sub>` - these tags are used to create superscript and subscript numbers easily on a page
  - `whitespace` - the browser will automatically eliminate more than two whitespace characters in a row and will also treat a new line without a new line specific character as a single space
  - `<br />, <hr />` - as described in the whitespace explanation, the `<br />` will create a line break. `<hr />` will create a horizontal line divider to seperate sections
  
 In addition to those types of markup, there are semantic tags, which add more information to your page
  - `<strong>, <em>` - `<strong>` will bold text, but also cause a text reader to read more strongly the text within. `<em>` will italicize and cause a text reader to emphacize the text within.
  - `<blockquote>, <q>` - blockquote will indent text as is commonly seen in quotes. `<q>` will add quotation marks around text within, except in the case of internet explorer.

## Introducing CSS (CSS)
  
  CSS manipulates the way HTML elements are vied on the page. There are two parts of CSS, the selector and the declaration. There can be multiple selectors and multiple declaration in the same CSS rule. CSS is more acceptably placed within it's own document, a stylesheet with the extension .css. When placed into it's own sheet, they are placed into a link tag inside the head tag. Selectors can be elements, classes, ids, and several other things. There's a whole slew of declarations.  
  
## Decisions (JS)
  
  Decisions on which code to run can be made utilizing expressions made up of two values or more values, which can be variables, and evaluating them with comparison operators.
  - == - Loosely equal to. Doesn't guarantee type equality
  - === - Strict equal to. Guarantees type equality
  - != - Loosely is not equal to. Doesn't guarantee type inequality
  - !== - Strict is not equal to. Guarantees type inequality
  - > - Greater than. Returns true or false relating to if the left is greater than the right
  - < - Less than. Returns true or false relating to if the left is smaller than the right
  - >= - Greater than or equal to. Returns true or false relating to if the left is greater than or equal to the right
  - <= - Less than or equal to. Returns true or false relating to if the left is smaller than or equal to the right
       
  Logical Operators allow comparison of multiple expressions to handle even more advanced situations.
  - && - Logical And. Returns only true if both left and right evaluate to true
  - || - Logical Or. Returns true if either side or both sides evaluate to true, but not if both evaluate to false
  - ! - Logical Not. Returns true if whatever to the left of the bang (!) is false
