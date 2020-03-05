# Javascript--Boostrap
       
              vaScript and Bootstrap
                     
               What is the DOM
              
                     iecst
              "Document Object Model"
        A tree of objects created by web browser, when a web page loads.
        The web browser uses the DOM to interpret the page and display it contents.

- Document
- Document Element <HTML>
- <head>, <title>
- <body>, <a>, <div>, <p>

- DOM
- Elements can have attributes and text content.
- Example:
- <a> element
- Attributes: href, target, id, alt
- href = "http://www.google.com"

- DOM
- We can change HTML elements, attributes, CSS styles, when different events are triggered.
- fe: a button is clicked or a page is loaded.

- Three methods of changing elements:
- By tag name (eg: <h1>)
- By id (eg: <p id="test">...</p>)
- By class name (eg: <li class="bullet1>)

- Javascript
- HTML & CSS - static programming language
- Javascript is Client-Side
- Communicates with Web Browser, not Web Server
- Javascript allows User-Web page interactivity

- cannot be forced onto users browser
- must be supported on clients browser
- most browser support javascript by default
- diff language from Java

- Rules for Javascript identifiers:
- names can contain letters, digits, underscores, and dollar signs
- names must begin with a letter
- names are case sensitive (y and Y are diff)
- reserved words (like JavaScript keywords) cannot be used as names

- var x = 10;
- var y = 10.5;
- var z = "John Smith"
- text values are knowns as strings

- Arithmetic Operators
- add +
- subtract -
- multiplication *
- division /
- modulus %
- increment ++
- decrement --

- javascript data types:
- numbers, strings, arrays, objects

- var age = 16; // number
- var lastname = "johnson"; // string
- var cars = ['acura', 'volvo', 'bmw']; // array
- var person = {firstname:'john', lasname:'smith', age:50, eyecolor:"blue"}; // object

- Comparison Operators
- equal to  ==
- equal value and equal type ===
- not equal !=
- not equal value or equal type !==
- greater than >
- less than <
- greater than or equal to  >=
- less than or equal to <==

- Boolean (truthy/falsy)

- real value = true

- For Loop
- just like C for loop
- for(count=3; count<=20; count++){
    document.write(count);
    document.write("<br/>");

}

- Javascript Events
- mouse clicks
- mouse overs
- mouse out
- key down
- document load
- ...
```

## Intro to Bootstrap

- Note: Render the <b>boots.html</b> to see the power of Bootstrap

```html
       <!-- bootstrap necessities -->
        <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <!-- jQuery -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <!-- compiled bootstrap -->
        <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
```

```iecst

- a framework that makes web development much more efficient
- framework includes: HTML & CSS based design templates for typography, forms, buttons, tables, navigation, modals, and image carousels.
- also includes optional Javascript plugins

- streamlines the development process
- has built-in components
- provides responsiveness, styling, and cross-browser functions already tested

- Key benefits:
- ease of use: basic understanding of HTML and CSS is enough to use Bootstrap
- Responsive Features: bootstrap layouts adjust for optimal viewing on all devices, including phones, tablets, and desktops.
- cross-browser compatibility: bootstrap is compatible with all modern browsers include Chrome, Firefox, Internet explorer, Safari, and Opera, Edge.

- Container Types:
- fixed with container
- fluid container

- Grid System
- col size sum must be 12 

- column size:
- xs (extra small) - for phones
- sm (small) - for tablets
- md (medium) - for laptops and desktops
- lg (large) - for larger desktops

- 3 column layouts
- will work on tablets in landscape mode without stacking.
- only if the tablets screen resolution is => 992px;


- .list-group-item-heading
- .list-group-item-text

- .navbar-fixed-top
- .navbar-fixed-bottom

- Form Layouts:
- Vertical (Default)
- Horizontal
- Inline

- Support all HTML5 input types
- text
- password
- datetime
- datetime-local
- date
- month
- time
- week
- number
- email
- url
- search
- tel
- color


```

## Bootstrap Features

```iecst
1.  Grid System
2.  Three Column Layouts
3.  Typography
4.  Tables
5.  Styling Images
6.  Jumbotron
7.  Wells
8.  Alerts
9.  Buttons
10.  Button Groups
11.  Justified Button Groups
12.  Glyphicons
13.  Badges and Labels
14.  Progress Bars
15.  Pagination
16.  Pager Pagination
17.  List Groups
18.  Panels
19.  Dropdown Menus
20.  Collapsibles
21.  Collapse Panel
22.  Collapse List Group
23.  Accordian
24.  Tab Menus
25.  Pill Menus
26.  Dynamic Tabs and Pills
27.  Navigation Bar
28.  Collapsible Navigation Bar
29.  Forms - Vertical and Inline
30.  Inputs
31.  Form Control States
32.  Input Sizing
33.  Carousel
34.  Modal
35.  Tooltip
36.  Popover
37.  Scrollspy
```

- [Bootstrap Themes](https://startbootstrap.com/)