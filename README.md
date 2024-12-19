# libraries-and-frameworks
Libraries and Frameworks in Web Front-End Development (coursera)

</div>
Our script would look something like this:
var parentDiv = document.getElementById("parent");
var removeMe = document.getElementById("remove-me");
22. Using JavaScript
Meet the DOM
629
parentDiv.removeChild( removeMe );
// Removes the div with the id "remove-me" from the page.
For Further Reading
That should give you a good idea of what DOM scripting is all about. Of
course, I’ve just barely scratched the surface of what can be done with the
DOM, but if you’d like to learn more, definitely check out the book DOM
Scripting: Web Design with JavaScript and the Document Object Model, Second
Edition, by Jeremy Keith and Jeffrey Sambells (Friends of Ed).
POLYFILLS
You’ve gotten familiar with a lot of new technologies in this book so far: new
HTML5 elements, new ways of doing things with CSS3, using JavaScript to
manipulate the DOM, and more. In a perfect world, all browsers would be
in lockstep, keeping up with the cutting-edge technologies and getting the
established ones right along the way (see the sidebar “The Browser Wars”).
In that perfect world, browsers that couldn’t keep up (I’m looking at you,
IE8) would just vanish completely. Sadly, that is not the world we live in, and
browser inadequacies remain the thorn in every developer’s side.
I’ll be the first to admit that I enjoy a good wheel reinvention. It’s a great
way to learn, for one thing. For another, it’s the reason our cars aren’t rolling
around on roundish rocks and sections of tree trunk. But when it comes to
dealing with every strange browser quirk out there, we don’t have to start
from scratch. Tons of people smarter than I am have run into these issues
before, and have already found clever ways to work around them and fix the
parts of JavaScript and the DOM where some browsers may fall short. We
can use JavaScript to fix JavaScript.
Polyfill is a term coined by Remy Sharp to describe a JavaScript “shim”
that normalizes differing behavior from browser to browser (remysharp.
com/2010/10/08/what-is-a-polyfill). Or, as Paul Irish put it, a polyfill is
A shim that mimics a future API providing fallback functionality to older
browsers.
There’s a lot of time travel going on in that quote, but basically what he’s say-
ing is that we’re making something new work in browsers that don’t natively
support it—whether that’s brand-new technology like detecting a user’s
physical location or fixing something that one of the browsers just plain got
wrong.
There are tons of polyfills out there targeted to specific tasks, such as making
old browsers recognize new HTML5 elements or CSS3 selectors, and new
ones are popping up all the time as new problems arise. I’m going to fill you
in on the most commonly used polyfills in the modern developer’s toolbox as
The Browser Wars
JavaScript came about during a
dark and lawless time, before the
web standards movement, when
all the major players in the browser
world were—for want of a better
term—winging it. It likely won’t come
as a major surprise to anyone that
Netscape and Microsoft implemented
radically different versions of the
DOM, with the prevailing sentiment
being “may the best browser win.”
I’ll spare you the gory details of the
Battle for JavaScript Hill, but the two
competing implementations were so
different that they were both largely
useless, unless you wanted to either
maintain two separate code bases
or add a “best viewed in Internet
Explorer/Netscape” warning label to
your sites.
Enter the web standards movement!
During this cutthroat time, the W3C
was putting together the foundations
for the modern-day standardized
DOM that we’ve all come to know
and love. Fortunately for us, Netscape
and Microsoft got on board with
the standards movement. The
standardized DOM is supported all
the way back to Internet Explorer
5 and Netscape Navigator 6.
Unfortunately, Internet Explorer’s
advancements in this area stagnated
for quite some time following IE6. As
a result, older versions of IE have a
few significant differences from the
modern-day DOM. Fortunately with
Internet Explorer 9 and later, they’re
catching right back up.
The trouble is, your project likely still
needs to support those users with
older versions of IE. It’s a pain, but
we’re up for it. We have an amazing
set of tools at our disposal, such as
polyfills and JavaScript libraries full
of helper functions, that normalize
the strange little quirks we’re apt to
encounter from browser to browser.
Part IV. JavaScript for Behavior
Polyfills
630
of the release of this book. You may find that new ones are necessary by the
time you hit the web design trenches. You may also find that some of these
techniques aren’t needed for the browsers you need to support.
HTML5 shim (or shiv)
You may remember seeing this one back in Chapter 5, Marking Up Text, but
let’s give it a little more attention now that you have some JavaScript under
your belt.
An HTML5 shim/shiv is used to enable Internet Explorer 8 and earlier to rec-
ognize and style newer HTML5 elements such as article, section, and nav.
There are several variations on the HTML5 shim/shiv, but they all work in
much the same way: crawl the DOM looking for elements that IE doesn’t
recognize, and then immediately replace them with the same element so they
are visible to IE in the DOM. Now any styles we write against those elements
work as expected. Sjoerd Visscher originally discovered this technique, and
many, many variations of these scripts exist now. Remy Sharp’s version is the
one in widest use today.
The shim must be referenced in the head of the document, in order to “tell”
Internet Explorer about these new elements before it finishes rendering the
page. The script is referenced inside an IE-specific conditional comment and
runs only if the browser is less than (lt) IE9—in other words, versions 8 and
earlier:
<!--[if lt IE 9]>
<script src="html5shim.js"></script>
<![endif]-->
The major caveat here is that older versions of Internet Explorer that have
JavaScript disabled or unavailable will receive unstyled elements. To learn
more about HTML5 shim/shiv, try these resources:
• The Wikipedia entry for HTML Shiv (en.wikipedia.org/wiki/HTML5_Shiv)
• Remy Sharp’s original post
(remysharp.com/2009/01/07/html5-enabling-script)
Selectivizr
Selectivizr (created by Keith Clark) allows Internet Explorer 6–8 to under-
stand complex CSS3 selectors such as :nth-child and ::first-letter. It uses
JavaScript to fetch and parse the contents of your style sheet and patch holes
where the browser’s native CSS parser falls short.
Selectivizr must be used with a JavaScript library (I talk about them in the
next section). The link to the script goes in an IE conditional comment after
the link to the library .js file, like so:
NOTE
If you don’t need to support IE8 and ear-
lier, you don’t need an HTML5 shim.
NOTE
If you don’t need to support IE8 and ear-
lier, you don’t need Selectivizr.
22. Using JavaScript
Polyfills
631
<script type="text/javascript" src="[JS library]"></script>
<!--[if (gte IE 6)&(lte IE 8)]>
<script type="text/javascript" src="selectivizr.js"></script>
<noscript><link rel="stylesheet" href="[fallback css]" /></noscript>
<![endif]-->
Because we’re forgoing the native CSS parser here, we may see a slight perfor-
mance hit in applicable browsers. See the Selectivizr site (selectivizr.com) for
more information.
Picturefill (A Responsive Image Polyfill)
Picturefill enables support for the picture element, srcset and sizes attri-
butes, and features related to delivering images based on viewport size and
resolution (also known as responsive images, as discussed in Chapter 7,
Adding Images). It was created by Scott Jehl of Filament Group and is main-
tained by the Picturefill group.
To use Picturefill, download the script and add it to the head of the document.
The first script creates a picture element for browsers that don’t recognize it.
The second script calls the Picturefill script itself and the async attribute tells
the browser it can load Picturefill asynchronously—that is, without waiting
for the script to finish before loading the rest of the document.
<head>
<script>
// Picture element HTML5 shiv
document.createElement( "picture" );
</script>
<script src="picturefill.js" async></script>
</head>
On the downside, browsers without JavaScript that also do not support the
picture element will see only alt-text for the image. Download Picturefill and
get information about its use at scottjehl.github.io/picturefill/.
JAVASCRIPT LIBRARIES
Continuing on the “you don’t have to write everything from scratch yourself”
theme, it’s time to take on JavaScript libraries. A JavaScript library is a collec-
tion of prewritten functions and methods that you can use in your scripts to
accomplish common tasks or simplify complex ones.
There are many JS libraries out there. Some are large frameworks that include
all of the most common polyfills, shortcuts, and widgets you’d ever need to
build full-blown Ajax web applications (see the sidebar “What Is Ajax?”). Some
are targeted at specific tasks, such as handling forms, animation, charts, or
math functions. For seasoned JavaScript-writing pros, starting with a library
is an awesome time-saver. And for folks like you who are just getting started,
a library can handle tasks that might be beyond the reach of your own skills.
Part IV. JavaScript for Behavior
JavaScript Libraries
632
What Is Ajax?
Ajax (sometimes written AJAX) stands for Asynchronous
JavaScript And XML. The “XML” part isn’t that important—you
don’t have to use XML to use Ajax (more on that in a moment).
The “asynchronous” part is what matters.
Traditionally, when a user interacted with a web page in a way
that required data to be delivered from the server, everything
had to stop and wait for the data, and the whole page needed
to reload when it was available. This made for a not especially
smooth user experience.
But with Ajax, because the page can get data from the server
in the background, you can make updates to the page based
on user interaction smoothly and in real time without the page
needing to be reloaded. This makes web applications feel more
like “real” applications.
You see this on a number of modern websites, although
sometimes it’s subtle. On Twitter, for example, scrolling to the
bottom of a page loads in a set of new tweets. Those aren’t
hardcoded in the page’s markup; they’re loaded dynamically as
needed. Google’s image search uses a similar approach. When
you reach the bottom of the current page, you’re presented with
a button that allows you to load more‚ but you never navigate
away from the current page.
The term “Ajax” was first coined by Jesse James Garrett in an
article “Ajax: A New Approach to Web Applications.” Ajax is not a
single technology, but rather a combination of HTML, CSS, the
DOM, and JavaScript, including the XMLHttpRequest object,
which allows data to be transferred asynchronously. Ajax may
use XML for data, but it has become more common to use JSON
(JavaScript Object Notation), a JavaScript-based and human-
readable format, for data exchange.
Writing web applications with Ajax isn’t the type of thing you
would do right out of the gate, but many of the JavaScript
libraries discussed in this chapter have built-in Ajax helpers and
methods that let you get started with significantly less effort.
The disadvantage of libraries is that because they generally contain all of
their functionality in one big .js file, you may end up forcing your users to
download a lot of code that never gets used. But the library authors are aware
of this and have made many of their libraries modular, and they continue to
make efforts to optimize their code. In some cases, it’s also possible to cus-
tomize the script and use just the parts you need.
jQuery and Other Libraries
As of this writing, the overwhelmingly dominant JavaScript library is jQuery
(jquery.com). Chances are, if you use a library, it will be that one (or at least
that one first). Written in 2005 by John Resig, jQuery has found its way into
over two-thirds of all websites. Furthermore, if a site uses a library at all, there
is a 97% chance that it’s jQuery.
It is free, it’s open source, and it employs a syntax that makes it easy to use if
you are already handy with CSS, JavaScript, and the DOM. You can supple-
ment jQuery with the jQuery UI library, which adds cool interface elements
such as calendar widgets, drag-and-drop functionality, expanding accordion
lists, and simple animation effects. jQuery Mobile is another jQuery-based
library that provides UI elements and polyfills designed to account for the
variety of mobile browsers and their notorious quirks.
Of course, jQuery isn’t the only library in town. Others include MooTools
(mootools.net), Dojo (dojotoolkit.org), and Prototype (prototypejs.org). As for
smaller JS libraries that handle specialized functions, because they are being
created and made obsolete all the time, I recommend doing a web search for
22. Using JavaScript
JavaScript Libraries
633
“JavaScript libraries for _____________” and see what is available. Some
library categories include the following:
• Forms
• Animation
• Image carousels
• Games
• Information graphics
• Image and 3-D effects for the canvas element
• String and math functions
• Database handling
• Touch gestures
