# JavaScript

**this book explain how we can use javaScript in browsers to make websits**
 
## How javaScript makes web pages more interactive:

1. **ACCESS CONTENT**

You can use JavaScript to select any element, attribute, or text from an HTML page. For example:
* Select the text inside all of the (hl) elements on a page
* Select any elements that have a c1ass attribute with a value of note
* Find out what was entered into a text input whose id attribute has a value of emai1  

2. **MODIFY CONTENT**

You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example:
* Add a paragraph of text after the first (hl) element
* Change the value of c 1 ass attributes to trigger new CSS rules for those elements
* Change the size or position of an (img) element 

3. **PROGRAM RULES**

You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the
content of a page. For example:
* A gallery script could check which image a user clicked on and display a larger version of that image.
* A mortgage calculator could collect values from a form, perform a calculation, and display repayments.
* An animation could check the dimensions of the browser window and move an image to the bottom
of the viewable area (also known as the viewport). 

4. **REACT TO EVENTS**
You can specify that a script should run when a specific event has occurred. For example, it could be run when:
* A button is pressed
* A link is clicked (or tapped) on
* A cursor hovers over an element
* Information is added to a form
* An interval of time has passed
* A web page has finished loading

now let us talk about **THE STRUCTURE OF THIS BOOK**:

this book divided two sections:
1. **Core concepts**

like chapter 1 ,2 ,4,5

2. **PRACTICAL A PPLICATIONS** 

like chapter 10 , 11 , 12 , 13

## WRITING A SCRIPT

To write a script, you need to first state your goal and then list the tasks that need to be completed in
order to achieve it. 

## Start with the big picture of what you want to achieve, and break that down into smaller steps

1. DEFINE THE GOAL

2. DESIGN THE SCRIPT

3. CODE EACH STEP

## EXPRESSIONS

An expression evaluates into (results in) a single value. Broadly speaking
there are two types of expressions. 

## OPERATORS 

Expressions rely on things called operators; they allow programmers to
create a single value from one or more values.

**This figure below shows some of arithmetic operators**

(Arthmatic Ope)[https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Arithmatic-Operators.png]

This example display a personalized welcome message on the page using javaScript. 

var greeting= 'Howdy ';
var name= 'Mol ly' ;
c02/js/string-opera tor.js
var welcomeMessage = greeting+ name+ '!';
var el = document.getElementByld('greeting');
el .textContent = welcomeMessage;

## Function

Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements). 

To create a function , you give it name and then write the statements needed to achieve its task inside the curly braces.
for example :
function sayHello()
{
decument.write('Hello');

to call the function just put the name of function like : sayHello();
}



