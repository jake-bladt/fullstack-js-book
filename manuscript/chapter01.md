# Chapter 1: Feral Javascript and how to tame it

## A Brief History of Javascript
Javascript was first released as a client-side scripting that ran in the beta version of Netscape Navigator 2.0 in September of 1995. Based on a seemingly impossible litany of management demands, language designer Brendan Eich created the entire language in ten days, drawing largely from SmallTalk and LISP and bolting on a syntax that looks like Java, but behaves in ways that are both subtly and grotesquely different from its namesake language.

As a result, for the last twenty years, everyone who writes or talks about Javascript feels the need at some point to say, "Javascript is not Java." In fact, it's not even close.

Considering its origins, Javascript should have been an unremarked-upon failure. But by 1995, developers were pushing the limits of server-side dynamic web programming and had an immediate appetite for any sort of behavior that didn't require the browser to call back to the web server and get a fresh page. Javascript wasn't pretty, but it was the language that launched a million drop-down menus (not to mention image swaps, hover effects, and overwrought "ferret pages.")

Instead of being a failure, Javascript is now a ubiquitous part of the online experience. It runs in every modern browser, on phones and set-top cable boxes, and even on the server. As Scott Hanselman famously noted, [Javascript has become the Assembly Language of the Web](http://www.hanselman.com/blog/JavaScriptIsAssemblyLanguageForTheWebSematicMarkupIsDeadCleanVsMachinecodedHTML.aspx).

That being said, Javascript is weird. If you approach it, thinking it's "like Java," you will spend hundreds of hours unlearning that preconception. The same is true if you think it's like any classically object-oriented language. For example, Javascript has a ```new()``` operator, but no concept of classes. It has objects, but they don't behave like Java objects or C++ objects. It has functions, but... well, it has functions in the way that the ocean has water.

Over the last twenty years, developers have wrestled with Javascript, building more and more complex client-side applications and, in the process, creating better and better tools for handling the language and its many idiosyncracies. In more recent years, they've built frameworks like jQuery, AngularJS and node that completely change both how we develop web applications and how we use the web.

This book is an introduction to the Javascript ecosystem - the patterns, tools, and libraries that are used to build some of the most successful web sites in the world.


