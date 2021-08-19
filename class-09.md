# Class 9 - Reading Notes

## Forms (HTML)

Html forms basically try to replicate the way a phsyical form is on a sheet of paper for the purpose of gathering data from the user. They provide fields that tell what data to type and give text input, password input, text area, radio buttons, checkboxes, and dropdown boxes to provide that data. Unlike physical forms though, they have submit buttons, next buttons, image buttons, upload buttons. Having a next button allows you to group data sets that you're taking from the customer into digestible chunks of related material rather than having them fill out a gigantic long-form. Submit buttons can cause some javascript to run to actually send the data to wherever you're storing it. Uploads allow users to upload images or whatever material you need of them. HTML forms also have a benefit over physical forms. We can make sure that users provide data within certain parameters. For instance, a password might need to have a certain strength to be acceptable. We can check that their password contains at least one capital, at least one special character, at least one number. Additionally, for a lot of fields including password, we can specify a minimum character count and a maximum character count. For fields that we want just plain text, we can disable the acceptance of special characters, which can prevent some form submitted malicious attack attempts to certain websites without back-end validation.

## Lists, Tables, & Forms (HTML)

With a little CSS, we can change bullet appearances for unordered lists to an image. We can use CSS rules to change the distance to and from the bullet and the text. On tables, we can target specifically `empty-cells` to give them a border, show them, or hide them depending on the look you're going for. We can also set border spacing and border collapse to alter the space between individual cells. Buttons and input fields can be moved around with alignment properties being changed within a form just like any other objects. Buttons can have their entire appearance re-defined through CSS.

## Events (JS)

In Javascript, we can set up event listeners to handle certain `events` happening. First, we need to select an element that we want to have cause some event. Then we want to choose what will cause this event to begin. It could be something like a hover or a click. Next, we want to state the code that we want to run when said event happens. There's three ways to create an event handler. HTML event handling, traditional dom e vent handling, and dom level 2 event listeners. The first is deprecated and considered bad practice. Submit buttons will often times have a `preventDefault()` used to prevent the default form submission and instead do some javascript code to submit a form in a different way as the default of a submit button will refresh the page. We can set events to trigger when a field gains focus or gains blur. This means when a field is selected to enter information ie `focus` then an focus event triggers, likewise if the user leaves that field, then it triggers a `blur` event. 