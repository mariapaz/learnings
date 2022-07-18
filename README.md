# learnings
## Git 
Why do we use Git?  
To have version control of our code. To better collaborate in a team of developers.  

What’s the difference between Git and GitHub?  
Git is the a version control system to track code and its changes and versions. Github is a cloudsystem to host repositories and by using Git enable version control. Gitub provides an interface, and a social platform to find and follow programmers.  

What happens when you clone a repository?  
You are downloading a copy of the files included in that repository.  

What happens when we do git pull origin main  
You are downloading the files of the main branch into an already cloned local directory.  

How do we create a new branch on our local machine?  
git checkout -b 'name-of-branch'  

How do we control which changes will be included in the next commit?  
By adding a file by its name.  

When might git add . be inappropriate?  
When you don't want to commit all the files.  

How do we make sure our local changes don’t conflict with main?  
git status will tell you if you are behind main. Also after a PR the person reviewing can check for conflicts.  

What does git push origin [branch-name] do? 
Uploads the branch-name as a new branch if it doesn't exist, or udates branch-name with the local files.  

Why do we make pull requests instead of just changing main directly?  
Because main is the last stable version. It is important to signal changes in the code by naming branches to be able to revert changes and branches.  

Why should you review your teammates’ pull requests?  
Because there could be errors in the code, or a better approach could be suggested.  

## HTML 
Why is accessibility important?  
Accessibility ensures the web is for everyone, so everyone can access content regradless of a disablity, age, digital education, and so on.  

How can you quickly find simple accessibility problems?  
Using lighthouse report.  

What is semantic HTML?  
Is the use of html tags that are meaningful to the content they are displaying.  

Why is it important to use the “correct” semantic element?  
So screenreaders can navigate a page more accurately, and also robots can better index context.  

What is the <form> element used for?  
  To submit information.  
  
  
## CSS 
How would you use CSS variables to make a reusable colour palette?
How would you use flexbox to make elements sit on a single line?
How would you use grid to make a layout that automatically adds columns as the screen gets wider?
Why is it important to create a responsive design?
How would you structure your CSS to make it “mobile-first”?
## Javascript 
Why should we avoid using
var
to define variables?
How might you make a long, complex chunk of code easier to read?
What is a “callback”?
## Array methods 
How would you use
array.map()
to create a new array with transformed values?
How would you use
array.filter()
to create a new array with certain values removed?
How would you use
array.find()
to get a single value from an array?
## Promises & fetch 
What is a promise?
How do promises help manage asynchronous code?
What does a promise’s
.then
method return?
How could you chain promises together to avoid “callback hell”?
How would you handle a
fetch
request that failed to get a response from the server?
How would you handle a
fetch
request that received a
404
response from the server?
## HTTP 
What is an HTTP request?
What kind of request is sent when you click a link in your browser?
What kind of request is sent when you submit a form in your browser?
What is an HTTP response?
What does the status code of an HTTP response tell us?
What are some common status codes?
What are HTTP methods for?
What kind of request should have a
GET
method?
What kind of request should have a
POST
method?
What kind of request should have a
PUT
method?
What kind of request should have a
DELETE
method?
What is the “body” of an HTTP
request
for?
What is the “body” of an HTTP
response
for?
## DOM 
How would you get a reference to a DOM element in your JS?
How would you get references to multiple DOM elements at once in your JS?
How would you update properties of a DOM element?
What’s the difference between a “property” and an “attribute”?
What are some different ways to add content inside a DOM element?
When might the
<template>
element be useful?
What are the different ways to add event handlers to elements?
Why is
addEventListener
the safest way to add an event handler?
How can you access submitted form values in your JS?
## Testing 
Why are tests useful?
What is the difference between unit and integration tests?
What kind of code is easier to test?
Why should your tests be isolated from each other?
What is Test Driven Development (TDD)?
When might TDD be a useful process to follow?
## Debugging 
What process would you take to find out why your code isn’t working?
What tools do JS/dev tools have to help debug your code?
At what point should you ask for someone else’s help?
