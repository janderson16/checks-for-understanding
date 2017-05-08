## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
  JS basics
2. What are some tools to help debug JavaScript code?
  debugger, pryjs
3. What are some tools you need in order to unit test your JavaScript?
  chai, mocha
4. What is the syntax for invoking a function?
  function(withParens)
5. What's the difference between `==` and `===` in JavaScript?
  equal vs strictEqual
6. What's the difference between asynchronous and synchronous JavaScript? 
  sync waits for a response to move on the next thing, async can fire many different actions without waiting
7. What's a callback function and what are some reasons when we use/need callback functions?
  packaged up code to be used in the future, used pass one function to another
8. What's the biggest difference between a promise and a callback?
  you don't know what order callbacks will be executed in, promises are done in order
9. How do we setup a route when creating an API with Node and Express?
  
10. What's `npm` and what do we use it for?
  node package manager, similar to gems for ruby

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
  Model-View-Controller, request comes into controller, then sent to model for instructions, info then passed back up to         controller which renders the correct view
12. What is AJAX? What are some benefits of using AJAX?
  async javascript and XML, can change content dynamically without having to reload the page
13. What's a background worker? When would we want to use a background worker?
  creates a separate setup to run certain tasks in the background, used to avoid performance bottlenecks
