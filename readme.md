#Interview Prep

(Partially from https://github.com/h5bp/Front-end-Developer-Interview-Questions)

Go through all of the following questions and think about how you would respond to each. You should be able to answer many of the questions from memory, but you may have to research a few of them.

**Copy this md file to your homework folder and add a short answer under each item.** You should try to be as concise as possible, and list any handy resources you used to answer the question. This will be useful for studying for interviews after class.

## General Questions

* What did you learn yesterday/this week?
I learned about Angular: routing, services, directives, filters, animations. It's cool stuff.
* What excites or interests you about coding?
I love that I can build things, that I am learning a language, that there are so many challenges and so much more to learn.
* What is a recent technical challenge you experienced and how did you solve it? 
* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site? I focus on password encryption, api key security, 
* Talk about your preferred development environment. I've become very comfortable with Sublime Text editor and git/github.
* Which version control systems are you familiar with? Git/github.
* Can you describe your workflow when you create a web page? Visualize/create wireframes, build out the database structure (if applicable), create database tables and relationships and pages as needed.
* If you have 5 different stylesheets, how would you best integrate them into the site? I would check to see if any of the styling could be consolidated, and then apply the sheets that are left in the html doc.
* Can you describe the difference between progressive enhancement and graceful degradation?
* Describe how you would create a simple slideshow page, without any frameworks (HTML/CSS/JS only).
* If you could master one technology this year, what would it be? Python
* Explain the importance of standards and standards bodies. Standards organizations ensure that consistency and quality is upheld across the World Wide Web. 

## HTML Questions

* What does a `doctype` do? It lets the doc know what type of doc we are working with (html etc).
* What's the difference between HTML and XHTML? They are almost identical except that xhtml is stricter and can prevent “bad” html from being written on a page.
* What are `data-` attributes good for? Data attributes allow you to store more information in an html element. 
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`. They are all client storage solutions. Sessionstorage only holds data for the session, whereas localstorage can persist outside of the browser session. 
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions? Because of the order in which they load - it affects the time to load.

## CSS Questions

* What is the difference between classes and IDs in CSS? Ids are unique, whereas classes can be applied to many elements. 
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
* Describe Floats and how they work. CSS float is a position property that allows text and other elements of a page to wrap or float around an element. 
* Describe z-index and how stacking context is formed.
* Have you ever used a grid system, and if so, what do you prefer? Yes, and I prefer Materializes grid system laying out into columns and rowss.
* Have you used or implemented media queries or mobile specific layouts/CSS? Yes.
* How do you optimize your webpages for print? As in paper? I haven't.
* What are the advantages/disadvantages of using CSS preprocessors? 
  * Describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector.
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block? Inline has elements to the left and right, but does not respect height and width, whereas inline-block can have height and width set.
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage? 
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them? I’ve used Bootstrap and Materialize. I would make bootstrap more easily customizable if I could improve it. 
* Have you played around with the new CSS Flexbox or Grid specs? Yes, flex box.
* Have you ever worked with retina graphics? If so, when and what techniques did you use? Not yet
* Explain some of the pros and cons for CSS animations versus JavaScript animations. Cuss animations are simpler/use less resources.

## JS Questions

* Explain event delegation
* Explain how `this` works in JavaScript. It applies to the current element at stake.
* Explain how prototypal inheritance works. Inheritance is a process of reusing established object behavior by cloning objects.
* Why is it called a Ternary expression, what does the word "Ternary" indicate? The ternary operator is the only operator that takes 3 inputs, and ternary itself means composed of three parts.
* What's the difference between a variable that is: `null`, `undefined` or `undeclared`? Null is the state of having no value; undefined is the state of having value not yet defined (as in calling a variable that has not yet been assigned a value); and undeclared is a variable that is called without using var.
  * How would you go about checking for any of these states? By checking for the value of the variable.
* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* What's the difference between `.call` and `.apply`?
* Explain `Function.prototype.bind`.
* What's the difference between feature detection, feature inference, and using the User Agent string?
* Explain AJAX in as much detail as possible.
* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"?
* Why is extending built-in JavaScript objects not a good idea?
* What is the difference between `==` and `===`? They both test if two items are equal, but the === additionaly tests if it is the same value type, whereas == is more flexible.
* Explain the same-origin policy with regards to JavaScript.
* What is the extent of your experience with Promises and/or their polyfills?
* What are the pros and cons of using Promises instead of callbacks?
* What tools and techniques do you use debugging Javascript code?
* What language constructions do you use for iterating over object properties and array items?

## Database Questions

* Design a database schema for Facebook, with at least 4 models, a complete set of attributes for each model, a 1:M association, and a M:M association.

## Ruby/Rails
* What are ruby gems?
* What is the difference between a symbol and a string?
* What is the difference between a class method and an instance method?
* What is the difference between local variables, instance variables, and class variables?
* What is a range?
* In ruby, what does attr_accessor do?  
* What is the purpose of environment files under the config folder in Rails? (development, test, production)
* What is the purpose of the application.rb file in Rails?
* How can you define a constant?
* What is the purpose of `yield`?
* How do you store API keys when creating an app?
* How do I send parameters through a url?
* Explain MVC
* What is a `before_action`? When would you use it?
* What do controllers do in rails?
* What is RESTful routing?
* What is a polymorphic association?
* What are params?
* How do I make a migration to add a column in Rails?
* What is CSRF? How does Rails protect an app against this?
* What's the difference between `User.find_by_id(1)` and `User.find(1)`?
* What's are classes in Ruby? What are modules? And what's the difference?

## Testing Questions

* What are some advantages/disadvantages to testing your code? Advantages: helps you tell if your code works. Disadvantage: takes time and resources 
* What tools would you use to test your code's functionality?
* What is the difference between a unit test and a functional/integration test?
* What is the purpose of a code style linting tool?
* What is End-to-end (E2E) testing? How can it be implemented in frameworks like Angular and Rails?

## Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20'; 1020
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

## Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?
* How do you like your coffee?



