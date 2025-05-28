<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h1 id="libs-and-frames">libraries and frameworks</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Libraries and Frameworks in Web Front-End Development (coursera)</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>UNDERSTANDING THE BENEFITS OF USING LIBRARIES AND FRAMEWORKS</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
JavaScript libraries and frameworks offer numerous benefits that can significantly 
impact your development process and the quality of your applications:
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ajax">What Is Ajax?</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Ajax (sometimes written AJAX) stands for Asynchronous JavaScript And XML. The 
“XML” part isn’t that important—you don’t have to use XML to use Ajax (more on 
that in a moment).
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>The “asynchronous” part is what matters.</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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
<h2 id="jquery">jQuery and Other Libraries</h2>
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
<h2 id="js-libs">JavaScript Libraries</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
“JavaScript libraries for _____________” and see what is available. Some
library categories include the following:
<ol start="1">
  <li>• Forms •</li>
  <li>• Animation •</li>
  <li>• Image carousels •</li>
  <li>• Games •</li>
  <li>• Information graphics •</li>
  <li>• Image and 3-D effects for the canvas element •</li>
  <li>• String and math functions •</li>
  <li>• Database handling •</li>
  <li>• Touch gestures •</li>
</ol>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="1-forms">• Number 1 Forms: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Forms.js</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Is an advanced, lightweight JavaScript library designed to ease form creation and management. 
Utilizing JSON for data input, it generates dynamic, user-centric forms, offering an 
unparalleled development experience.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>SurveyJS</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Automate forms workflow and retain full ownership of respondent data.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Parsley JS</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://parsleyjs.org/
Github: https://github.com/guillaumepotier/Parsley.js/
Demo: https://parsleyjs.org/doc/examples.html
Price and License: Free, MIT license
Type: Form validation library
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Form validation</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://formvalidation.io/
Github: https://github.com/formvalidation/formvalidation
Demo: https://formvalidation.io/guide/examples/
Price and License: Commercial, from $50 to $200
Type: Form validation library
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Validate JS</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://validatejs.org/
Github: https://github.com/ansman/validate.js
Demo: https://validatejs.org/examples.html
Price and License: Free, MIT
Type: Form validation library
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Formbuilder</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: http://dobtco.github.io/formbuilder/
Github: https://github.com/dobtco/formbuilder
Demo: http://dobtco.github.io/formbuilder/
Price and License: Free, MIT License
Type: Online tool with a graphical interface for building forms
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>React Form Libraries</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
In this section, we have presented the best React form libraries.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Formbuilder. dev</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://formbuilder.dev/
Github: –
Demo: https://formbuilder.dev/demo/
Price and License: Free
Type: Online form builder
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>React hook form</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://react-hook-form.com/
Github: https://github.com/react-hook-form/react-hook-form
Demo: https://react-hook-form.com/
Price and License: Free, MIT License
Type: Form builder and validation library
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Formik</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: https://jaredpalmer.com/formik
Github: https://github.com/jaredpalmer/formik
Demo: https://codesandbox.io/s/zKrK5YLDZ
Price and License: Free, MIT License
Type: React form builder and validation library

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="2-animation">• Number 2 Animation: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Cropper.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>JS image cropper.</p>
Website: https://fengyuanchen.github.io/cropperjs/v1/
GitHub: https://github.com/fengyuanchen/cropperjs/tree/v1
Demo: https://fengyuanchen.github.io/photo-editor/
Type: JavaScript image cropper.
A versatile library for image cropping and resizing directly in the browser.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Fabric.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
A powerful canvas library that allows you to manipulate images, draw shapes, and add text 
with ease.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>CamanJS:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
A library specializing in image filters and effects, providing a range of Instagram-like 
filters and adjustments.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>PixiJS:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
A fast 2D rendering library that can also be used for image manipulation and effects.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Three.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
The most popular 3D library for the web, offering a comprehensive set of tools for 
creating 3D scenes, animations, and effects.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Babylon.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Another powerful 3D engine, offering a slightly different approach to Three.js, with a 
focus on performance and ease of use.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Zdog:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
A lightweight library for creating flat, pseudo-3D designs with a designer-friendly API.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>A-Frame:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
A framework built on top of Three.js, making it easier to create WebVR experiences using 
HTML-like tags.
Website: 
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>More libraries/frameworks</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>1. jQuery:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
jQuery is a fast, lightweight, and feature-rich JavaScript library that simplifies HTML 
document traversal, event handling, and animation. It provides an intuitive and concise 
API that enables developers to manipulate the DOM, handle events, perform AJAX requests, 
create animations, and more. jQuery's popularity stems from its ability to abstract away 
the complexities of cross-browser compatibility and provide an easy-to-use interface for 
common JavaScript operations.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>2. React:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
React is a powerful JavaScript library developed by Facebook for building user 
interfaces. It adopts a component-based architecture, allowing developers to build 
reusable UI components and efficiently update and render them as the application's state 
changes. React leverages a virtual DOM, which minimizes actual DOM manipulations and 
optimizes performance. React's popularity is driven by its simplicity, performance, 
and thriving ecosystem.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>3. Vue.js:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Vue.js is a progressive JavaScript framework that excels in building user interfaces. It 
boasts a gentle learning curve, making it accessible to newcomers, while providing 
advanced features for seasoned developers. Vue.js embraces a component-based development 
approach, where complex user interfaces are constructed by composing self-contained and 
reusable components. It offers powerful features such as declarative rendering, two-way
data binding, computed properties, and a sophisticated reactivity system. Vue.js's 
versatility and ease of integration with existing projects have contributed to its 
popularity. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2>INTRODUCTION TO JQUERY, REACT, AND VUE.JS</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Let's dive deeper into the key features and benefits of three influential JavaScript 
libraries and frameworks: jQuery, React, and Vue.js. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>jQuery</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Simplified DOM Manipulation:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
jQuery provides a unified and streamlined API for DOM
manipulation, making it effortless to select and modify HTML elements, handle events, 
and traverse the DOM tree. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Cross-Browser Compatibility:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
jQuery abstracts away the differences in browser implementations,
ensuring consistent behavior and easing the pain of dealing with browser quirks and
inconsistencies. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>AJAX</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Support:
jQuery simplifies AJAX communication by providing a set of convenient methods for making 
asynchronous requests to servers, handling responses, and updating content on the webpage 
dynamically. Rich Plugin Ecosystem: jQuery boasts a vast ecosystem of plugins that extend 
its functionality. These plugins cover a wide range of use cases, from UI widgets and 
effects to data visualization and form validation.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>React Component-Based Architecture:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
React revolutionized the web development landscape with its component-based architecture.
Components encapsulate the logic and presentation of UI elements, allowing for modular 
development, code reusability, and easier testing.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Virtual DOM:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
React employs a virtual DOM, a lightweight in-memory representation of the
actual DOM. By using a virtual DOM, React optimizes rendering performance by selectively
updating only the necessary parts of the UI, resulting in efficient and responsive
applications.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Unidirectional Data Flow:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
React promotes a unidirectional data flow, where data flows from
parent components to child components. This one-way data binding simplifies debugging,
improves code predictability, and reduces side effects. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>React Native:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
React also offers React Native, a frameworkfor building cross-platform mobile
applications using JavaScript. With React Native, developers can write code once and deploy 
it on both iOS and Android platforms, saving time and effort. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Vue.js:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Approachable Learning Curve:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Vue.js stands out for its simplicity and ease of learning. 
Its gentle learning curve enables developers to quickly grasp its core concepts and start
building applications. The Vue CLI (Command Line Interface) provides a scaffold for 
setting up Vue.js projects with ease.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Flexible and Versatile:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Vue.js is designed to be flexible and adaptable to various 
project sizes and requirements. Whether you're building a small application or a 
large-scale single-page application, Vue.js provides the necessary tools and 
features to handle the task at hand. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Vue Router and Vuex:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Vue.js offers official plugins, such as Vue Router and Vuex, that seamlessly 
integrate with the framework. Vue Router facilitates navigation between different
views in a Vue.js application, while Vuex provides a state management pattern for
managing application-wide data. 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="3-image-carousels">• Number 3 Image Carousels: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="4-games">• Number 4 Games: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="5-info-graphics">• Number 5 Information Graphics: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="6-image-3d">• Number 6 Image and 3-D Effects for the canvas element: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="7-strings-math">• Number 7 Strings and Math Functions: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="8-database-handling">• Number 8 Database Handling: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="9-touch-gestures">• Number 9 Touch Gestures: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Website: 
GitHub: 
Demo: 
Type: 


<h7>Date Created: 5/27/2025 10:00p<br>
Date Last Editted: 5/27/2025 10:41p</h7>
