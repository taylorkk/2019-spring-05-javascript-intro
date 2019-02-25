# CoderBabez

##  Week Five - Intro to Javascript

### Objectives
Complete your first full project - use your html, css styling and css layout skills to create a portfolio page for yourself.

### Vocab
* Javascript
* Libraries
* JQuery

### Review
* What do we use HTML for?
* What do we use CSS for?
* How do we connect our CSS to our HTML file?

### Lesson

##### What is Javascript?

JavaScript is a programming language used to make web pages interactive. It allows us to manipulate the HTML after the webpage has loaded.
QUESTION: Can you think of any real website examples where we're probably using javascript?

Just like CSS, if we want to connect javascript to our page, we need to add a tag within the <head>. This looks a little different than CSS:  
```html
<script src="./script.js"></script>
```

##### What is JQuery?

JQuery is a javascript library that we're going to use heavily in this class.
Libraries are files of code that another developer has already written and shared with the world. You can find libraries that help with just about everything. Jquery in particular is a library that makes it very easy for us to manipulate the HTML document.

Because javascript is a separate file of code, we need to link it to our HTML file just like we did with our own javascript file.

```html
<script src="https://code.jquery.com/jquery-3.1.0.js"></script>
```

##### Planning Ahead with Pseudo Code

Silly exercise: Imagine making a peanut butter and jelly sandwich. Imagine how you would explain to a friend how to make that sandwich. Now imagine explaining how to make that sandwich to a robot - a robot that doesn't understand how to open a jar or use a butter knife. How much more precise do your instructions have to be?

When we talk to computers we need be extremely clear and specific. Writing instructions that specific takes a lot of practice. Before we write any code today, we're going to practice writing specific instructions in english first. This will help us plan out the logic of our program without worrying about syntax. We call this pseudo code.

Psuedo Code Format:
```
WHEN ACTION X HAPPENS...

TO HTML ELEMENT X...

EXECUTE THE FOLLOWING ACTIONS...
```

Psuedo Code Example:
Task: Make an alert pop up when a user clicks ok.
```
WHEN the user clicks on...

the html element with id "myButton"...

EXECUTE THE FOLLOWING ACTIONS...
  find the html element with id "myAlert"
  and hide that element
```

##### Creating a Click Handler

Here's the javascript code that executes the pseudo code listed above. Can you point to the parts of the code that match our pseudo code?

```javascript
$("#myButton").click(function(){
  $("#myAlert").hide();
});
```

### Practice Together
1. Open the practice folder in Atom.
2. In the HTML, link your javascript file
3. In the HTML, link jQuery
3. In the Javascript file, follow the instructions in the comments to create a toggled menu.

### Project: Practice on Your Own
Open the puppy funhouse hoemwork repo to practice your event handlers!! 
