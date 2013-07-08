Dump Method - http://netgrow.com.au/

The Dump method is based on one of the tags available in Coldfusion ( <cfdump>) providing the ability to display simple and complex variables in a user friendly way that is perfect for debugging/inspecting data. There is no way to do this with javascript and often I had wanted a method to do this. This method will do just that allowing for an infinite amount of data nesting complete with color coding for different data types, the ability to show/hide the data's type (String/Number/Boolean/Object/Array/Function), expandable and collapsible tables/keys and cross browser support.

Click on the buttons bellow to see some examples in action, toggle the Show Data Types box to see javascript data typing in action (not possible in Coldfusion).

Browser Support

Internet Explorer 6, Internet Explorer 7, Firefox 1.5, Opera 8, Safari 1.2 (Mac), Firefox (Mac) - all tested, should also work in most other browsers

Usage

dump(value, [showTypes]) 
@ param value (Any) value to dump 
@ param [showTypes] (Boolean) optional to display each key/value's type 
@ return (Void) returns nothing
