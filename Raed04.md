# JAVASCRIPT

![js](https://cdn.lynda.com/course/417077/417077-637453753723998874-16x9.jpg)

### HOW A BROWSER SEES A WEB PAGE
In order to understand how you can change the content of an HTML page using JavaScript, you need to know how a browser interprets the HTML code and applies styling to it:
* RECEIVE A PAGE AS HTML CODE
* CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
* USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN

**All major browsers use a JavaScript interpreter to translate your
instructions (in JavaScript) into instructions the computer**

#### **HOW HTML, CSS & JAVASCRIPT FIT TOGETHER**

Before diving into the JavaScript language, you need to know how it will fit together with the HTML and CSS in your web pages.

* CONTENT LAYER
  * html files
This is where the content of the page lives. The HTML gives the page structure and adds semantics.

* PRESENTATION LAYER
  * css files
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

* BEHAVIOR LAYER
   * js files
This is where we can change how the page behaves, adding interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.


### CREATING A BASIC JAVASCRIPT:
1. Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right. A JavaScript fi le is just a text file (like HTML and CSS files are) but it has a . j s file extension, so save this file with the name add-content . j s Don't worry about what the code means yet. for now we will focus on how the script is created and how it fits with an HTML page.

2. Get the CSS and images for this example from the website that accompanies the book: www.javascriptbook. com To keep the files organized, in the same way that CSS files often live in a folder ca lled styles or css, your JavaScript files can live in a folder called scripts,javascript,orjs. In this case, save your file in a folder called js

3. In your code editor, enter the HTML shown on the left. Save this file with the name add-content.html The HTML <script> element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created. This tells the browser to find and load the script file (just like the src attribute on an <img> tag).

4. Open the HTML file in your browser. You should see that the JavaScript has added a greeting (in this case, Good Afternoon!) to the page. (These greetings are coming from the JavaScript file; they are not in the HTML file.) Please note: Internet Explorer sometimes prevents JavaScript running when you open a page stored on your hard drive. If this affects you, please try Chrome, Firefox, Opera, or Safari instead.

5. f) Once you have tried the example in your browser, view the source code for the page. (This option is usually under the View, Tools or Develop menu of the browser.)

6. The source of the web page does not actually show the new element that has been added into the page; it just shows the link to the JavaScript file. As you move through the book, you will see most of the scripts are added just before the closing </body> tag 


**To read more [click here](https://ltuc-asac.slack.com/files/USMATJALV/F01TTSXQT5M/javascript_and_jquery_interactive_jon_du.pdf)**