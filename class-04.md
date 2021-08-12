# Class 04 - Reading Notes

## Links (HTML)

  Links are elements that allow a user to go to another page, section of the page, another website, or even open up an email program with a pre-determined email address. Links have an href attribute which determines the method of this. The following are href values to do different things.
  - "https://www.google.com" - this would take you to the website google in the same window as you are in
  - "new-page.html" - this would take you to the new-page html file within the same website
  - "mailto:admin@mysite.com" - this would take you to your default email program with admin@mysite.com pre-filled as the recipient
  - "https://www.codefellows.com" target="_blank" - adding the target attribute will open codefellows.com in a new window
  - "#bio" - this would take you to the element on the page with the id of bio
  - "https://www.codefellows.com/#footer" - this would take you to the codefellows website and then scroll down to their footer element

## Layout (CSS)

CSS considers every element on the page to be a block. There are two types of blocks, block-level and inline. Block-level elements will appear below the proceeding element, while inline elements will allow other things such as text to surround it without automatically going to a new line. Elements have relationships to one another, for instance a paragraph inside of a section would be the child of the section. The section in that same example would be the parent of the paragraph. There are several types of positioning for elements, such as in my about me page, I used a fixed position to keep the header at the top of the page as the user scrolls down. Conversely, if I had set an absolute position, the element would've remained at the time. 

Another important factor that css handles is screen size. Nowdays you'll have people viewing your website from a computer with a 40 inch tv as a monitor, a 24 inch monitor, a laptop with a 13 inch monitor, an ipad/tablet, or even mobile phone. It used to be that different websites were created for mobile and pc, but now that it's more common for viewing from various devices and the number of possibilities, there are css rules for both using percentages of width and height as well as even entirely creating new style sets for elements based on screen size. For example, you may have an element that is 50% of the width of the screen, which will be viewed differently on a small mobile phone versus a 40 inch tv. In this case, you can make text smaller for a smaller screen, while retaining normal styling for the larger screen. You can also make elements break to a new line or change types of nav bars with such. Similar to how a newspaper is designed, you can give your website a grid-type layout allowing different sized elements to puzzle piece together for better appearance. This allows elements to have varied widths and still flow.

## Functions (JS)

A function is a reusable block of code to avoid repeating code. Functions can take in any number of parameters or no parameter at all. Functions can also return a value, although they can also just perform the code and return an undefined value. To call a function, you use it's name followed by parenthesis, including any values you wish to pass in inside the parenthesis. Further, functions have their own scope for variables declared in them. Once the function has exited, that variable and value no longer exist unless you returned it in which case the value survives.
