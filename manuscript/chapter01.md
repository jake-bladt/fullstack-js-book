# Chapter 1: Feral Javascript and how to tame it

## A (Very) Brief History of Javascript
Javascript was first released as a client-side scripting that ran in the beta version of Netscape Navigator 2.0 in September of 1995. Based on a seemingly impossible litany of management demands, language designer Brendan Eich created the entire language in ten days, drawing largely from SmallTalk and LISP and bolting on a syntax that looks like Java, but behaves in ways that are both subtly and grotesquely different from its namesake language.

As a result, for the last twenty years, everyone who writes or talks about Javascript feels the need at some point to say, "Javascript is not Java." In fact, it's not even close.

Considering its origins, Javascript should have been an unremarked-upon failure. But by 1995, developers were pushing the limits of server-side dynamic web programming and had an immediate appetite for any sort of behavior that didn't require the browser to call back to the web server and get a fresh page. Javascript wasn't pretty, but it was the language that launched a million drop-down menus (not to mention image swaps, hover effects, and overwrought "ferret pages.")

Instead of being a failure, Javascript is now a ubiquitous part of the online experience. It runs in every modern browser, on phones and set-top cable boxes, and even on the server. As Scott Hanselman famously noted, [Javascript has become the Assembly Language of the Web](http://www.hanselman.com/blog/JavaScriptIsAssemblyLanguageForTheWebSematicMarkupIsDeadCleanVsMachinecodedHTML.aspx).

That being said, Javascript is weird. If you approach it, thinking it's "like Java," you will spend hundreds of hours unlearning that preconception. The same is true if you think it's like any classically object-oriented language. For example, Javascript has a ```new()``` operator, but no concept of classes. It has objects, but they don't behave like Java objects or C++ objects. It has functions, but... well, saying that Javascript has functions is like saying that the ocean is a bit damp.

Over the last twenty years, developers have wrestled with Javascript, building more and more complex client-side applications and, in the process, creating better and better tools for handling the language and its many idiosyncracies. In more recent years, they've built frameworks like jQuery, AngularJS and node that completely change both how we develop web applications and how we use the web.

This book is an introduction to the Javascript ecosystem - the patterns, tools, and libraries that are used to build some of the most successful web sites in the world.

## Hello, Hidden World
At this point, most books about Javascript would provide you with a step-by-step explanation for how to use Javascript to make your browser either write "Hello, world" to a web page or to show a pop-up with that same message.

The shortcoming of this approach is that pop-ups are generally a method of last resort for communicating with an end user in Javascript and, with a proliferation of top-notch libraries and frameworks for handling DOM manipulation, only a madman (or madwoman) would do so in raw, feral Javascript. Besides being verbose and uninituitive, DOM manipulation in raw Javascript can be a bit of a black art because of differences in browser implementation. Later, we'll see how libraries like jQuery use CSS selectors to tame the DOM and render remarkable results.

(If you feel ill-used for the lack of a "Hello, World" example at this point, you can try one [here](http://javascript.info/tutorial/hello-world). Go ahead. I'll wait.)

T> **Protip**: One of the many pain points of working with Javascript is that different browsers implement Javascript and the DOM (the in-memory representation of the current web page differently) even though both are supposed to based on publicly agreed-upon standards.

T> For a time, all browser makers seemed to believe they could corner the market by "embracing and extending" Javascript. This was known as the browser wars. Like most wars, nobody really won. In recent years (and with the advent of HTML5,) the differences have become less and less, but they're still there. Several of the libraries described in this book arose out of a need to address cross-browser compatability issues.

Instead of diving head-first into code, let's look at a couple of tools that will be your fast friends and boon companions as you learn and use Javascript.

**Chrome Developer Tools**  
One category of tools that have evolved alone with Javascript are in-browser developer tools. For a long time, [Firebug](http://getfirebug.com/) was the de facto standard for web development, but the current champion is [Chrome Developer Tools](https://developer.chrome.com/devtools).

In the interest of full disclosure, Microsoft provides [F12 Developer Tools](http://msdn.microsoft.com/en-us/library/ie/gg589507(v=vs.85).aspx) for Internet Explorer as well. For the most part, I'll be focused on working in Chrome. As the tip above mentioned, different browsers handle things differently and IE is more different than most, creating the most headaches for web developers. While Microsoft has greatly improved IE's adherence to open standards in later versions, calling IE "reformed" would be pushing it more than a little.

Even if IE were ever to become 100% standards compliant, don't expect the developer community to embrace it with open arms. Most of us bear deep, disfiguring scars from working with Internet Explorer 6. Comparably, IE 11 is a joy to work with. But IE6 was the Joffrey Baratheon of web browsers - the worst of a bad line, making us forever doubt future issue.

TODO: Enough description of CDT to use the console


**Hello Console**  
Lorem ipsum


## Testing your Javascript with Jasmine
Lorem ipsum

**Passing functions to functions**  
...anonymous, first-class functions.... what Jasmine does with these functions.

**Test-first development in Jasmine**
Test first, red-green-refactor... When Javascript breaks, sometimes it really breaks.
