# Class 6 - Reading Notes

## Object Literals (JS)

 Objects are a datatype of Javascript that have quite powerful data storage. Similar to HTML attributes and values being key value pairs, Objects have properties and values that are key value pairs. A property is essentially a variable linked to an object. 
 IE: If a car object were to need to specify number of doors, for a two door car it would be car.doors = 2; 
 This sets the doors property of the cars object to the value of 2. Further, objects can have functions, which are called methods. A car would have the ability to drive.
 IE:
 car.drive = function() {
   car.distance += speed;
 }
 car.drive();
 This would cause a position property to change each time the car is said to have been driving. So, we could call the drive function once per second for as long as the car is driving and it would update the distance traveled.

## Document Object Model (JS)

When a browser opens a webpage, it creates a model of that page called a DOM tree. There are four frequently used node types: document node, element node, text node, and comment node. If you want to change information on a webpage dynamically without the user refreshing, you can select the area of information by figuring out it's node then the text content, child elements or attributes you wish to modify. This will update as soon as you tell it what to update with no refresh needed. If a user does refresh, they will revert back to the original state. You can select a node by it's tagname, class name, id, or even all of an element type. In addition to editing elements, you can add new elements or delete current elements.