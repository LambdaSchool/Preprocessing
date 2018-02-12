# Preprocessing
Preprocessing extends the ability of CSS by adding abstractions and making CSS easier to use. There are many flavors of preprocessors but the one we will focus on will be LESS (Leaner Style Sheets).  

LESS is a language extension for CSS.  It fits nicely into almost every type of development stack and has been ported to JavaScript among many other programming languages. http://lesscss.org/

## Project 1 - Get the compiler working and convert a CSS project into a LESS project.

Lets get LESS working on an existing CSS project so we can see the power this new tool offers us. If you look closer at the project on this repo you will notice there is a new LESS folder that you haven't seen before.  This is where we will store our .less files.  Remember that the LESS files **compile** into CSS files.  Once you open the project please open the index.html file in your browser.  You will notice the CSS is not working!  That is because the CSS will be generated by our LESS file once you complete task 1.  And thus begins our journey.  You MUST complete the prerequisites for this to work.  Good luck!

## Prerequisites

1. Node, npm, and LESS have been installed globally on your machine
2. LESS Watch Compiler has been installed globally on your machine

## Task 1 - Set up your LESS compiler

* Fork and clone this repo to get started.
* Once you have the repo on your local machine open terminal or git bash and ```cd``` into the project's root folder.
* Now that you are in the projects root folder run ```less-watch-compiler less css index.less```.  **If you get errors here it is most likely because you didn't finish the prerequisites section.  Please make sure you installed your LESS watch compiler globally.**
* At this point, the compiler should be up and running with a message in your terminal that says ```Watching directory for file changes.```.  This means your index.less file is now active and producing an index.css file after compiling.  Great work!  Go check out that index.html file now and your CSS should be working again.  

## Task 2 - Convert the existing CSS project into a LESS project

You might be asking, "Wait, I don't get it, it's just CSS in an index.less file that's compiling out to an index.css file..."  You're 100% correct!  We just needed to prime the pump and get LESS set up before we actually dig into some LESS syntax.  Here are some tasks to convert that plain old CSS into something new:

* Convert all of the current seletor chains into nested selectors.  Do this for every commented section that you see.
* Find a way to use at least two different operators like + or * to do something to the layout.
* Convert all the block comments into single line comments.
* Introduce a new color scheme that you control using variables (this is more open ended so be creative with your ideas here).
* Introduce media queries from last week's projects with the nested @media rules.  

## Stretch Task - Find something we didn't cover in the LESS documentation and see if you can implement it in your project.  Be sure to use comments to call out what you are doing.
##