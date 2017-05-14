## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?
  Simliar to asset pipeline and equally enigmatic, it's a module bundler
2. When do you want to use event delegation?
  when you want to attach an event listener for elements that exist now or in the future; i.e. our delete foods functionality
3. What's one difference between ES5 and ES6?
  function() vs =>; `${}` vs " " + " "
4. What's the deal with semi-colons in JavaScript?
  optional unless line begins with ()
5. How are you using the MVC design pattern in your Quantified Self project?
  pulling foods, meals, and meal_foods out into models and controllers in the backend
6. How do you execute raw SQL in node?  
  .raw(SQL QUERY)
7. What is CORS?
  overriding the same origin policy; adding headers to your server to tell your browser `hey, it's gonna be ok`
8. What are some steps to avoid CORS?
  Express CORS middleware package
  Rack

#### Review  

9. Why do people say "HTTP is stateless"?
  because it's not stored; close your eyes for a moment and the moment's gone, all they are is dust in the wind mmmhhhmmmmhhhmm
10. What is a RESTful API?
  an api that uses HTTP verbs GET, PUT, POST, PATCH, DELETE
11. What are some main characteristics of a team following an agile workflow?
  working in iterations, producing a minimum viable product
12. What are some advantages/disadvantages to using OAuth to authenticate a user?
  passes the buck to your OAuth provider but all of your data is also potentially at risk if they get hacked
