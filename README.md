# libraries-and-frameworks
Libraries and Frameworks in Web Front-End Development (coursera)

## What Is Ajax?

Ajax (sometimes written AJAX) stands for Asynchronous
JavaScript And XML. The “XML” part isn’t that important—you
don’t have to use XML to use Ajax (more on that in a moment).

### The “asynchronous” part is what matters.

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

## jQuery and Other Libraries

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

## JavaScript Libraries

“JavaScript libraries for _____________” and see what is available. Some
library categories include the following:
<ul>
  <li>• Forms</li>
  <li>• Animation</li>
  <li>• Image carousels</li>
  <li>• Games</li>
  <li>• Information graphics</li>
  <li>• Image and 3-D effects for the canvas element</li>
  <li>• String and math functions</li>
  <li>• Database handling</li>
  <li>• Touch gestures</li>
</ul>




