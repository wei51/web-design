**Web Design for Everybody: Basics of Web Development & Coding Specialization**
div
span

#### Course 1:Introduction to HTML5
* <head></head>
  <body></body>
  <footer></footer>
#### Course 2:Introduction to CSS3

<details>
<summary> Course 3 : Interactivity with JavaScript </summary>
<pre>

#### Week one: introduction to JavaScript

* Scripting languages (JavaScript)
    * API (Application programming interface)
    * read and write HTML
    * <script>
        alert();
        prompt(); ask for input
        document.write(Hello world!);
        element.innerHTML = " ";
        console.log(); for debugging
    </script>
* Variables: 
    * var name = " ";
    * var date = Date();
    * var loca = window.location();
* Data type:
    * Numeric: var width = window.innerWidth;
    * String:  var loca = window.location();
    * Boolean: var windowStatus = window.closed;
    * Object:  var topic = document.getElementById('ID');  ex: return a tag
    * Array:   var links = document.getElementsByTagName('a');

#### Week two: reacting to your audience
* Functions: function name(parameters){};
* Place in external files:
    ```html
    <head>
        <script src="js/xxx.js"></script>
    </head>
    ```
* Folder structure:
    ```html
    <link rel="stylesheet" href="css/style.css"> 
    <script src="js/function.js"></script>
    <img src="img/image1.png"> 
    ```
* Events:
    * Mouse events: onclick, ondblclick, onmousedown ...
    * Keyboard events: onkeydown, onkeypress ...
    * Frame events: onload, onresize, onscroll, onerror ...
    [] events, this

#### Week four: 

* Forms: <form>, <label>, <input>
* Input validation: <pattern={using regular expression}> , <required>
* Comparing two inputs: ex: input same password
* Checkboxes and radio buttons: <label><input type="checkbox"></label>

</pre></details>



<details>
<summary> Course 4 : Advance styling with responsive design </summary>
<pre>

#### Week 1: Introdution to responsive design

* Responsive design:
    * Media queries - detecting the viewport size
    * Flexible grid-based layout for relative sizing
    * Flexible images
* Test Responsiveness of website:
    * ami.responsivedesign.is
    * Chrome-inspect-toggle device toolbar
* Fluid measurements:
    * Absolute measurement: px, mm, cm, in, pt, pc
    * Relative measurement (based on parents, root, neighbor or screen size): %, em(font size of element), rem, vw(view width), vh(view width) 

#### Week 2: Basic concepts

* Media queries: allow the style depend upon the media properties
    * Two query components:
        * Media types: all, print, screen, speech
        * Media features
    * Implement media queries:
        * Use the @import rule
        * Put median query directly in the style sheet
        ``` css
        @media screen and (min-width:500px){
            
        }
        ```
        * Include query in the link
* Wireframes: provide a visula representation of your layout (coding after design)
    * Layout
    * Functionality
    * Sketch v.s Wireframe

* Breakpoints: sizes that define a change in your site layout or comment

* Mobile first

* Media queries 2:
    * Step1: Grab information. The meta viewport tag tells mobile browser's viewport how to behave
    ```html
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    ```
    * Step2: Fluid layout
    * Step3: Media queries. It is important to order rules

#### Week 3/ Week 4: Use existing frameworks: bootstrap

* Framework: Bootstrap
* xs-(480px), sm-(720px), md-(992px), lg-(1200px)
* Responsive images: 
    * In CSS: width:100%, max-width:750px, min_width:200px, set height to auto
    * Bootstrap: img-responsive, img-rounded, img-circle, img-thumbnail


</pre>
</details>



<details>
<summary> Others: jQuery </summary>
<pre>

* jQuery起手式
    ``` js
    $(document).ready(function(){

    });

    (function($){

    })(jQuery);
    ```
* var $demo =  $("#demo1"); //得到 JQuery 物件
* var demo = document.getElementById('demo1');   // 得到 DOM 物件

</pre>
</details>
