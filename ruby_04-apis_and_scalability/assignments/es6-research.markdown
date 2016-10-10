Length   | Points | Week
--- | --- | ---
15 minutes | 5 | Week 1

## ES6 Research

Throughout the module (and your journey to Google enlightenment while working on IdeaBox2.0) you may notice a few different ways that JavaScript code is being written.

That might have something to do with something called `ES6` and `ES5`

### Deliverable

  - Fork This Gist
  - Respond in your forked gist with answers to the following questions
    - What is `ES6`?
      ES6 is the updated syntax used for JavaScript designed to alleviate some of the flaws that ES5 had present. Becuause
      JS is backwards compatible, the devs behind these decisions can't exactly deprecate the ES5 syntax, so they present ES6 
      as the new standard for writing modern JavaScript.
      
    - What is Transpilation and how does it relate to `ES6`?
      Transpilation is the process of translating code written in one language/syntax and translate it into another format.
      Transpilers have only arrived out of preference from the developer. With a transpiler, a dev can wrote a more convenient,
      easier to write/read sytax (ie ES6), without causing any breaking changes to the process that the code carries out.
      
    - Looking at the ES6 Features link below, discuss one update from `ES5` and if it seems useful/superfluou
      I think the most useful change from ES5 to ES6 is what was done with ES5 functions. It seems that the devs behind these
      decisions took the two primary uses for ES5 functions (object constructor, and computational processes), and split them       out into ES6 classes - which uses the constructor() function to bind attributes to the instance, and arrow functions - 
      which are anonymous (no auto-binding this), short-hand functions for running computational processes. I
      especially embrace this change as someone initially confused by the different uses of a function in ES5. Classes and
      arrow functions open up a lot of opportunities for a dev that is new to JS to pick up when coming from another language.
  - You can use the resources below or your own Google-fu

### Resources

- [ES6 Features](https://github.com/lukehoban/es6features)
- [Understanding ES6](https://github.com/sgaurav/understanding-es6)
- [Using ES6 with Rails](https://babeljs.io/docs/setup/#rails)
- [Using ES6 with Rails Slides](https://speakerdeck.com/stevekinney/using-javascript-from-the-future-in-your-rails-application-today?slide=145)
- [ES6 Compatibility](http://kangax.github.io/compat-table/es6/)
