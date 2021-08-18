# Class 8 - Reading Notes

## Layout (HTML) --- Repeat Read From Class 4 Reading

 For a webpage we can use either fixed width layouts or liquid layouts. Some disadvantages of each would be: 

 Fixed Width:
  - If the user has too big of a monitor, there can be large gaps and things won't proportionally increase in size making sometimes unreadable.
  - If the user sets font sizes on their own computer to be larger, the text can leak out of the element or disappear.
  - Longer page view to potentially scroll if everything isn't on one screen.

  Liquid:
  - Not controlling certain widths can cause gaps or things to be awkwardly smashed together when changing screen sizes.
  - For phones or like things where the screen is more of a narrow up and down, text can be split between lines very unappealingly.
  - If an element1 that has a fixed width is inside an element2 and that outside element2 was made too small to hold it, the element1 would then expand past the borders of element2 and leak onto other content.

  In webpages as time goes on, it becomes more increasingly likely the websites you visit will be setup in grid-type format. Just like a newspaper, fitting differently shaped 'boxes' of headlines and text together into an easily distinguishable flow that's both smooth and easy to comprehend.

  Multiple style sheets can be used on a webpage by two methods. One would be to put `@import url("stylename.css")` into the top of the css file you link for each additional stylesheet you'd like to link causing a chain of linking. The other would be to use multiple link tags one after another. Be aware though, that whichever stylesheets come later will override anything that is the same or lesser specificity in prior stylesheets and with the import method, those imports are read before the stylesheet you attach.


