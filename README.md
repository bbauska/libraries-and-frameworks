<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
# libraries and frameworks
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Libraries and Frameworks in Web Front-End Development (coursera)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## What Is Ajax?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## jQuery and Other Libraries
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## JavaScript Libraries
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
“JavaScript libraries for _____________” and see what is available. Some
library categories include the following:
<ol start="1">
  <li>Forms •</li>
  <li>Animation •</li>
  <li>Image carousels •</li>
  <li>Games •</li>
  <li>Information graphics •</li>
  <li>Image and 3-D effects for the canvas element •</li>
  <li>String and math functions •</li>
  <li>Database handling •</li>
  <li>Touch gestures •</li>
</ol>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

### Number 1 Forms:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
#### Forms.js
Is an advanced, lightweight JavaScript library designed to ease form creation and management. 
Utilizing JSON for data input, it generates dynamic, user-centric forms, offering an 
unparalleled development experience.
#### SurveyJS
Automate forms workflow and retain full ownership of respondent data.
#### Parsley Js
Website: https://parsleyjs.org/
Github: https://github.com/guillaumepotier/Parsley.js/
Demo: https://parsleyjs.org/doc/examples.html
Price and License: Free, MIT license
Type: Form validation library
#### Form validation
Website: https://formvalidation.io/
Github: https://github.com/formvalidation/formvalidation
Demo: https://formvalidation.io/guide/examples/
Price and License: Commercial, from $50 to $200
Type: Form validation library
#### Validate JS
Website: https://validatejs.org/
Github: https://github.com/ansman/validate.js
Demo: https://validatejs.org/examples.html
Price and License: Free, MIT
Type: Form validation library
#### Formbuilder
Website: http://dobtco.github.io/formbuilder/
Github: https://github.com/dobtco/formbuilder
Demo: http://dobtco.github.io/formbuilder/
Price and License: Free, MIT License
Type: Online tool with a graphical interface for building forms
#### React Form Libraries
In this section, we have presented the best React form libraries.
#### Formbuilder. dev
Website: https://formbuilder.dev/
Github: –
Demo: https://formbuilder.dev/demo/
Price and License: Free
Type: Online form builder
#### React hook form
Website: https://react-hook-form.com/
Github: https://github.com/react-hook-form/react-hook-form
Demo: https://react-hook-form.com/
Price and License: Free, MIT License
Type: Form builder and validation library
#### Formik
Website: https://jaredpalmer.com/formik
Github: https://github.com/jaredpalmer/formik
Demo: https://codesandbox.io/s/zKrK5YLDZ
Price and License: Free, MIT License
Type: React form builder and validation library
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Number 2 Animation:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

### Number 6 Image and 3-D Effects:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
#### Cropper.js:
A versatile library for image cropping and resizing directly in the browser.
#### Fabric.js:
A powerful canvas library that allows you to manipulate images, draw shapes, and add text 
with ease.
#### CamanJS:
A library specializing in image filters and effects, providing a range of Instagram-like 
filters and adjustments.
#### PixiJS:
A fast 2D rendering library that can also be used for image manipulation and effects.
#### Three.js:
The most popular 3D library for the web, offering a comprehensive set of tools for 
creating 3D scenes, animations, and effects.
#### Babylon.js:
Another powerful 3D engine, offering a slightly different approach to Three.js, with a 
focus on performance and ease of use.
#### Zdog:
A lightweight library for creating flat, pseudo-3D designs with a designer-friendly API.
#### A-Frame:
A framework built on top of Three.js, making it easier to create WebVR experiences using 
HTML-like tags.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### More libraries/frameworks
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
In this chapter, we will embark on a comprehensive exploration of JavaScript libraries 
and frameworks.

JavaScript libraries and frameworks are invaluable tools that simplify and enhance the 
development process, enabling developers to build robust and efficient web applications.
We will delve into an in-depth overview of popular JavaScript libraries and frameworks, 
including jQuery, React, and Vue.js. By the end of this chapter, you will possess a solid 
understanding of these tools and how they can revolutionize your JavaScript development 
workflow.

JavaScript libraries and frameworks are widely adopted in web development due to their 
ability to streamline development tasks, improve code maintainability, and enhance user 
experience. Let's take a closer look at some of the most influential JavaScript libraries 
and frameworks available today:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### 1. jQuery: 
jQuery is a fast, lightweight, and feature-rich JavaScript library that simplifies HTML 
document traversal, event handling, and animation. It provides an intuitive and concise 
API that enables developers to manipulate the DOM, handle events, perform AJAX requests, 
create animations, and more. jQuery's popularity stems from its ability to abstract away 
the complexities of cross-browser compatibility and provide an easy-to-use interface for 
common JavaScript operations.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### 2. React: 
React is a powerful JavaScript library developed by Facebook for building user 
interfaces. It adopts a component-based architecture, allowing developers to build 
reusable UI components and efficiently update and render them as the application's state 
changes. React leverages a virtual DOM, which minimizes actual DOM manipulations and 
optimizes performance. React's popularity is driven by its simplicity, performance, 
and thriving ecosystem.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### 3. Vue.js:
Vue.js is a progressive JavaScript framework that excels in building user interfaces. It 
boasts a gentle learning curve, making it accessible to newcomers, while providing 
advanced features for seasoned developers. Vue.js embraces a component-based development 
approach, where complex user interfaces are constructed by composing self-contained and 
reusable components. It offers powerful features such as declarative rendering, two-way
data binding, computed properties, and a sophisticated reactivity system. Vue.js's 
versatility and ease of integration with existing projects have contributed to its 
popularity. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## INTRODUCTION TO JQUERY, REACT, AND VUE.JS
Let's dive deeper into the key features and benefits of three influential JavaScript 
libraries and frameworks: jQuery, React, and Vue.js. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### jQuery
### Simplified DOM Manipulation: 
jQuery provides a unified and streamlined API for DOM
manipulation, making it effortless to select and modify HTML elements, handle events, 
and traverse the DOM tree. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Cross-Browser Compatibility: 
jQuery abstracts away the differences in browser implementations,
ensuring consistent behavior and easing the pain of dealing with browser quirks and
inconsistencies. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### AJAX
Support:
jQuery simplifies AJAX communication by providing a set of convenient methods for making 
asynchronous requests to servers, handling responses, and updating content on the webpage 
dynamically. Rich Plugin Ecosystem: jQuery boasts a vast ecosystem of plugins that extend 
its functionality. These plugins cover a wide range of use cases, from UI widgets and 
effects to data visualization and form validation.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### React Component-Based Architecture:
React revolutionized the web development landscape with its component-based architecture.
Components encapsulate the logic and presentation of UI elements, allowing for modular 
development, code reusability, and easier testing.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Virtual DOM: 
React employs a virtual DOM, a lightweight in-memory representation of the
actual DOM. By using a virtual DOM, React optimizes rendering performance by selectively
updating only the necessary parts of the UI, resulting in efficient and responsive
applications.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Unidirectional Data Flow: 
React promotes a unidirectional data flow, where data flows from
parent components to child components. This one-way data binding simplifies debugging,
improves code predictability, and reduces side effects. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### React Native: 
React also offers React Native, a frameworkfor building cross-platform mobile
applications using JavaScript. With React Native, developers can write code once and deploy 
it on both iOS and Android platforms, saving time and effort. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Vue.js:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Approachable Learning Curve: 
Vue.js stands out for its simplicity and ease of learning. 
Its gentle learning curve enables developers to quickly grasp its core concepts and start
building applications. The Vue CLI (Command Line Interface) provides a scaffold for 
setting up Vue.js projects with ease.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Flexible and Versatile: 
Vue.js is designed to be flexible and adaptable to various 
project sizes and requirements. Whether you're building a small application or a 
large-scale single-page application, Vue.js provides the necessary tools and 
features to handle the task at hand. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### Vue Router and Vuex: 
Vue.js offers official plugins, such as Vue Router and Vuex, that seamlessly 
integrate with the framework. Vue Router facilitates navigation between different
views in a Vue.js application, while Vuex provides a state management pattern for
managing application-wide data. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
### UNDERSTANDING THE BENEFITS OF USING LIBRARIES AND FRAMEWORKS
JavaScript libraries and frameworks offer numerous benefits
that can significantly impact your development process and
the quality of your applications:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
1. Increased Productivity: Libraries and frameworks provide pre-built solutions for common tasks,
  reducing development time and effort. They abstract away the complexities, allowing developers
  to focus on building application-specific features rather than reinventing the wheel.
  
2. Code Maintainability and Organization: Libraries and frameworks often encourage best
  practices and provide guidelines for code organization. By following their patterns and
  conventions, developers can create well-structured, modular, and maintainable codebases.
  
3. Improved Performance: Many libraries and frameworks implement optimizations and performance 
  enhancements behind the scenes. For example, React's virtual DOM efficiently updates the UI, 
  reducing unnecessary re-rendering and enhancing performance.
  
4. Cross-Browser Compatibility: Libraries and frameworks handle the nuances and inconsistencies
  across different browsers, ensuring that your code works consistently across various 
  platforms and versions. This saves valuable time spent on browser-specific troubleshooting.

5. Thriving Communities and Ecosystems: Popular libraries and frameworks have vibrant 
  communities and extensive ecosystems. This means you have access to abundant resources, 
  documentation, tutorials, and a supportive community to help you along your development 
  journey.

