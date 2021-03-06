![CF](https://i.imgur.com/7v5ASc8.png)  Class 4: Templating
=======
## Overview
<!-- Provide a general overview of the daily concepts and processes that will be covered in lectures and labs -->

*Templates have some advantages over direct DOM manipulation. Leverage those strengths in the blog by adding in a templating library! We use templating to abstract away the tiresome work of DOM rendering, and this practice is applied in many front-end libraries and frameworks.*

## Daily Plan

**Code review: Let's take a deep look at the previous lab assignment (45-50 minutes; Allie, JB, me)**

  ```10 minute break```

**Regular Expresions (10-15 minutes, JB)**

- [*MDN: "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec and test methods of RegExp, and with the match, replace, search, and split methods of String. This chapter describes JavaScript regular expressions."*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
- [**Eloquent Javascript**'s take on RegEx](http://eloquentjavascript.net/09_regexp.html)

**ES6 arrow functions (30-40 minutes, JB)**

**Typography (5-10 minutes; Allie)**

  ```10 minute break```

**Templating (slides, 10 minutes; Allie)**

- What is an HTML templating system?
- Why use templating? How is a templating system useful?

**Templating with [Handlebars.js](http://handlebarsjs.com/) (30 minutes; Allie)**

- How did we do templating on Days 2 & 3? Used jQuery to pull HTML from the DOM that we then repurposed.
- Now by putting the template in the `<head>` means there's no concern with it displaying and no need to manage that any longer.
- Handlebars lets us get rid of a lot of the "[brittle](http://lmgtfy.com/?q=brittle+code)" jQuery.
- Look at the [tryhandlebarsjs.com](http://tryhandlebarsjs.com/) demos!
- [Code demo](https://github.com/codefellows/301-04-handlebars-demo) for us to hack together!

**Lab prep (15 minutes; Sam)**

- Let's review the lab README!
- The skinny: you're getting rid of the old jQuery templating and replacing it with Handlebars!
- 'Staches FTW = **{{WIN}}**

## Learning Objectives
<!--
ABCD:
  Audience: Program participants
  Behavior: Expected learning/behavior changes/results
  Condition:
    Circumstances that lead to change/result
    When change/result are expected to occur
  Degree: How much change occurs (%) for how many participants (#)
-->

* Identify different approaches to reusable HTML templates

* Effectively use templates to present user-entered (or server-provided) data (methods on the Handlebars object).

* Distinguish between the different Handlebars expression types ( **{{}}** vs **{{{}}}** ).

* Modify and style typographic components (**serif, san-serif fonts, font-size, font-family, color, font-weight**, etc)

## Readings
<!-- List of readings required for this content; readings being completed by the start of this lecture -->

* [Handlebars.js Official Documentation](http://handlebarsjs.com/) (Reference)

* [Learn Handlebars.js in 10 Minutes tutorial](http://tutorialzine.com/2015/01/learn-handlebars-in-10-minutes/) (Essential)
