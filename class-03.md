# Class 03 - Reading Notes

## Lists (HTML)

  There are various types of lists to use:
  - Unordered Lists which have bullet points <ul>
  - Ordered lists which are numbered <ol>
  - Definition lists which are aligned differently <dl>
  - Nested lists which are lists inside of lists

## How CSS Handles Elements - Boxes (CSS)
  
  Every element on the page is treated like a box. These boxes have properties that can be manipulated with CSS for orientation on the page:
  - Width and Height controls what you'd think they'd control
  - Min-width and Max-Width control the maximum dimensions as contents may cause the box to shrink or expand without values assigned here
  - Min-height and Max-Height have similar use to Min-Width and Max-Width
  - Overflow prevents overlapping on the page when a user may adjust text sizes for their browser
  - Border, Padding, and Margin controls the outline of the element (border,) space from the elements surrounding it (margin,) and space from the border to the contents inside (margin)
  
## Arrays (Javascript)
  
  Arrays are a variable type that in javascript is one of the most common storages of lists. In javascript, you don't need to specify the size of the array as it can be changed whenever. Values are seperated by commas and can be varied variable types. Arrays can be instantiated with values and/or have values added at anytime. Values are accessed by their index starting with 0 and going until there are no more values. Values can also be changed by index.
  
## Conditional Statements (Javascript)
  
  The Else part of an If/Then statement can be used as a catchall for anything that didn't have a truthy value for the previous ifs. A switch statement is similar to an If/Then statement in many ways and both can achieve the same goal with the same information. The final part of the switch statement, default is similar to an Else statement. Leaving out the break will cause all lines within the switch statement after the first truthy value to be run until it finds a break or the end of the switch statement. 
  
## Loops (Javascript)
  There are a few types of loops, to include For loops, While loops and Do While loops. The more common of the loops is the for loop, but while and do while loops do have their uses and places. A instantiates a counter variable and sets it's value, then sets the max or min value for the counter before the loop ends, then sets the increment or decrement of that variable. For a while loop, you'll need the variable declared ahead of time. In a while loop, you can use an expression or even use the true/false value directly. Putting an If/Then in the while loop for a certain condition and then using the break command will cause the loop to end even though the loop may be While (true) which is always true. The do while loop is almost exactly like the while loop, except that it will always run the code once and then evaluate the expression afterwards to decide on continuing. 
