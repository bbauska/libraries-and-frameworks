<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!-- REAME.md of https://github.com/bbauska/libraries-and-frameworks -->
<h1 id="libs-and-frames">libraries and frameworks</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Libraries and Frameworks in Web Front-End Development</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Benefits of using Libraries and Frameworks</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<ol type="1">
  <li>Increased Productivity: Libraries and frameworks provide pre-built solutions for common tasks,
   reducing development time and effort. They abstract away the complexities, allowing developers
   to focus on building application-specific features rather than reinventing the wheel.</li>
  <li>Code Maintainability and Organization: Libraries and frameworks often encourage best
   practices and provide guidelines for code organization. By following their patterns and
   conventions, developers can create well-structured, modular, and maintainable codebases.</li>
  <li>Improved Performance: Many libraries and frameworks implement optimizations and performance 
   enhancements behind the scenes. For example, React's virtual DOM efficiently updates the UI, 
   reducing unnecessary re-rendering and enhancing performance.</li>
  <li>Cross-Browser Compatibility: Libraries and frameworks handle the nuances and inconsistencies
   across different browsers, ensuring that your code works consistently across various 
   platforms and versions. This saves valuable time spent on browser-specific troubleshooting.</li>
  <li>Thriving Communities and Ecosystems: Popular libraries and frameworks have vibrant 
   communities and extensive ecosystems. This means you have access to abundant resources, 
   documentation, tutorials, and a supportive community to help you along your development 
   journey.</li>
 </ol>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ajax">What Is Ajax?</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Ajax</mark></b> (sometimes written AJAX) stands for <b><mark>Asynchronous JavaScript 
And XML</mark></b>. The “XML” part isn’t that important—you don’t have to use XML to use 
Ajax (more on that in a moment).</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>The “asynchronous” part is what matters.</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Traditionally, when a user interacted with a web page in a way that required data to 
be delivered from the server, everything had to stop and wait for the data, and the 
whole page needed to reload when it was available. This made for a not especially smooth 
user experience.</p>

<p>With <b><mark>Ajax</mark></b>, because the page can get data from the server in the 
background, you can make updates to the page based on user interaction smoothly and in 
real time without the page needing to be reloaded. This makes web applications feel 
more like “real” applications.</p>

<p>You see this on a number of modern websites, although sometimes it’s subtle. On 
Twitter, for example, scrolling to the bottom of a page loads in a set of new tweets. 
Those aren’t hardcoded in the page’s markup; they’re loaded dynamically as needed. 
Google’s image search uses a similar approach. When you reach the bottom of the current 
page, you’re presented with a button that allows you to load more‚ but you never 
navigate away from the current page.</p>

<p>The term <b><mark>“Ajax”</mark></b> was first coined by Jesse James Garrett in an article 
“Ajax: A New Approach to Web Applications.” Ajax is not a single technology, but 
rather a combination of HTML, CSS, the DOM, and JavaScript, including the XMLHttpRequest 
object, which allows data to be transferred asynchronously. Ajax may use XML for data, 
but it has become more common to use JSON (JavaScript Object Notation), a JavaScript-
based and human-readable format, for data exchange.</p>

<p>Writing web applications with Ajax isn’t the type of thing you would do right out of 
the gate, but many of the JavaScript libraries discussed in this chapter have built-in 
Ajax helpers and methods that let you get started with significantly less effort. The 
disadvantage of libraries is that because they generally contain all of their 
functionality in one big .js file, you may end up forcing your users to download a lot 
of code that never gets used. But the library authors are aware of this and have made 
many of their libraries modular, and they continue to make efforts to optimize their 
code. In some cases, it’s also possible to customize the script and use just the parts 
you need.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="jquery">jQuery and Other Libraries</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>As of this writing, the overwhelmingly dominant JavaScript library is <b><mark>jQuery 
(jquery.com)</mark></b>. Chances are, if you use a library, it will be that one (or at least 
that one first). Written in 2005 by John Resig, jQuery has found its way into over 
two-thirds of all websites. Furthermore, if a site uses a library at all, there is a 97% 
chance that it’s jQuery.</p>

<p>It is free, it’s open source, and it employs a syntax that makes it easy to use if you are 
already handy with CSS, JavaScript, and the DOM. You can supplement jQuery with the jQuery UI 
library, which adds cool interface elements such as calendar widgets, drag-and-drop functionality, 
expanding accordion lists, and simple animation effects. jQuery Mobile is another jQuery-based
library that provides UI elements and polyfills designed to account for the variety of mobile 
browsers and their notorious quirks.</p>

<p>Of course, jQuery isn’t the only library in town. Others include <b><mark>MooTools 
(mootools.net)</mark></b>, <b><mark>Dojo (dojotoolkit.org)</mark></b>, and <b><mark>Prototype 
(prototypejs.org)</mark></b>. As for smaller JS libraries that handle specialized functions, 
because they are being created and made obsolete all the time, I recommend doing a web 
search for it.</p>
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
<h2 id="1-forms">• Forms #1 JavaScript libraries for <b>Forms</b>: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h3>Forms.js</h3>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p>Is an advanced, lightweight JavaScript library designed to ease form 
creation and management. Utilizing JSON for data input, it generates dynamic, 
user-centric forms, offering an unparalleled development experience.</p>
-->
<table style="width:75%">
  <tr>
    <th>Name</th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type</th>
  </tr>
  <tr>
    <td><b><a href="https://demo.bpmn.io/form/" target="_blank" rel="noopener noreferrer">
	  Forms.js</a></b></td>
    <td><a href="https://bpmn.io/toolkit/form-js/" target="_blank" rel="noopener noreferrer">
	  form-js</a></td>
    <td><a href="https://demo.bpmn.io/form/" target="_blank" rel="noopener noreferrer">
	  demo form</a></td>
    <td><a href="https://forum.bpmn.io/t/form-js-examples/8773" target="_blank" rel="noopener noreferrer">
	  Form-js Examples</a></td>
    <td>JSON</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>SurveyJS</h4>  -->
<!--    <td>Automate forms workflow and retain full ownership of respondent data.</td>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://surveyjs.io/" target="_blank" rel="noopener noreferrer">
	  SurveyJS</a></b></td>
    <td><a href="https://surveyjs.io/" target="_blank" rel="noopener noreferrer">
	  SurveyJS.io</a></td>
    <td><a href="https://github.com/surveyjs" target="_blank" rel="noopener noreferrer">
	  SurveyJS GH</a></td>
    <td><a href="https://surveyjs.io/documentation" target="_blank" rel="noopener noreferrer">
	  SurveyJS Doc'n</a></td>
    <td>JSON</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>Parsley JS</h4>  -->
<!-- <td>Form validation library</td>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://parsleyjs.org" target="_blank" rel="noopener noreferrer">
	  parsleyJS.org</a></b></td>
	<td><a href="https://parsleyjs.org/" target="_blank" rel="noopener noreferrer">
	  parsleyjs.org</a></td>
	<td><a href="https://github.com/guillaumepotier/Parsley.js/" target="_blank" rel="noopener noreferrer">
	  ParsleyJS GH</a></td>
    <td><a href="https://parsleyjs.org/doc/examples.html" target="_blank" rel="noopener noreferrer">
	  Example ParsleyJS</a></td>
    <td>JS</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>Form validation</h4>  -->
<!--    <td>Form validation library</td>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://formvalidation.io/" target="_blank" rel="noopener noreferrer">
	  formvalidation.io</a></b></td>
    <td><a href="https://formvalidation.io/guide/examples/" target="_blank" rel="noopener noreferrer">
	  formvalidation.io</a></td>
    <td><a href="https://github.com/anujsoft/formvalidation.io" target="_blank" rel="noopener noreferrer">
	  formvalidation.io GH</a></td>
    <td><a href="https://preview.keenthemes.com/jet-html-free/documentation/forms/formvalidation/basic.html" target="_blank" rel="noopener noreferrer">
	  formvalidation Demo</a></td>
    <td>JS, YAML</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>ValidateJS</h4>  -->
<!--    <td>Form validation library</td>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b>ValidateJS</b></td>
    <td><a href="https://validatejs.org/" target="_blank" rel="noopener noreferrer">
	  ValidateJS</a></td>
	<td><a href="https://github.com/ansman/validate.js" target="_blank" rel="noopener noreferrer">
	  ValidateJS GH</a></td>
    <td><a href="https://validatejs.org/examples.html" target="_blank" rel="noopener noreferrer">
	  ValidateJS Demo</a></td>
	<td>JS</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>Formbuilder</h4>  -->
<!--    <p>Type: Online tool with a graphical interface for building forms</p>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b>Formbuilder</b></td>
    <td><a href="http://dobtco.github.io/formbuilder/" target="_blank" rel="noopener noreferrer">
	  Formbuilder</a></td>
    <td><a href="https://github.com/dobtco/formbuilder" target="_blank" rel="noopener noreferrer">
	  Formbuilder GH</a></td>
    <td><a href="https://demo.formengine.io/" target="_blank" rel="noopener noreferrer">
	  Formbuilder Demo</a></td>
    <td>JSON</p>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>React Form Libraries</h4>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <p>In this section, we have presented the best React form libraries.</p>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>Formbuilder. dev</h4>  -->
<!--    <td>Online form builder</td>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b>Formbuilder.dev</b></td>
    <td><a href="https://formbuilder.dev/" target="_blank" rel="noopener noreferrer">
	  Formbuilder.dev</a></td>
    <td><a href="https://github.com/optimajet/formbuilder" target="_blank" rel="noopener noreferrer">
	  Formbuilder.dev GH</a></td>
    <td><a href="https://formbuilder.dev/demo/" target="_blank" rel="noopener noreferrer">
	  Formbuilder.dev Demo</a></td>
    <td>React</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>React hook form</h4>  -->
<!--  <p>Type: Form builder and validation library</p>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b>React Hook Form</b></td>
    <td><a href="https://react-hook-form.com/" target="_blank" rel="noopener noreferrer">
	  React Hook Form</a></td>
    <td><a href="https://github.com/react-hook-form/react-hook-form" target="_blank" rel="noopener noreferrer">
	  ReactHookForm GH</a></td>
    <td><a href="https://codesandbox.io/examples/package/react-hook-form" target="_blank" rel="noopener noreferrer">
	  React Hook Form Demo</a></td>
    <td>React</td>
  </tr>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--  <h4>Formik</h4>  -->
<!--  <p>Type: React form builder and validation library</p>  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://jaredpalmer.com/formik" target="_blank" rel="noopener noreferrer">formik</a></b></td>
    <td><a href="https://jaredpalmer.com/formik" target="_blank" rel="noopener noreferrer">formik</a></td>
    <td><a href="https://github.com/stackworx/formik-mui" target="_blank" rel="noopener noreferrer">Formik GH</a></td>
    <td><a href="https://codesandbox.io/s/zKrK5YLDZ" target="_blank" rel="noopener noreferrer">Formik Demo</a></td>
    <td>React</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="2-animation">• Animation #2 JavaScript libraries for Animation: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Cropper.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>JS image cropper.</p>
Website: <b>https://fengyuanchen.github.io/cropperjs/v1/</b>
GitHub: https://github.com/fengyuanchen/cropperjs/tree/v1
Demo: https://fengyuanchen.github.io/photo-editor/
Type: JavaScript image cropper.
<p>A versatile library for image cropping and resizing directly in the browser.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Fabric.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A powerful canvas library that allows you to manipulate images, draw shapes, and add text 
with ease.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>CamanJS:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A library specializing in image filters and effects, providing a range of Instagram-like 
filters and adjustments.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>PixiJS:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A fast 2D rendering library that can also be used for image manipulation and effects.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Three.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>The most popular 3D library for the web, offering a comprehensive set of tools for 
creating 3D scenes, animations, and effects.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Babylon.js:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Another powerful 3D engine, offering a slightly different approach to Three.js, with a 
focus on performance and ease of use.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>Zdog:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A lightweight library for creating flat, pseudo-3D designs with a designer-friendly API.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h4>A-Frame:</h4>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A framework built on top of Three.js, making it easier to create WebVR experiences using 
HTML-like tags.</p>
<b>Website:</b>
GitHub: 
Demo: 
Type: 
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>More libraries/frameworks</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>In this chapter, we will embark on a comprehensive exploration of JavaScript libraries 
and frameworks.</p>

<p>JavaScript libraries and frameworks are invaluable tools that simplify and enhance the 
development process, enabling developers to build robust and efficient web applications.
We will delve into an in-depth overview of popular JavaScript libraries and frameworks, 
including jQuery, React, and Vue.js. By the end of this chapter, you will possess a solid 
understanding of these tools and how they can revolutionize your JavaScript development 
workflow.</p>

<p>JavaScript libraries and frameworks are widely adopted in web development due to their 
ability to streamline development tasks, improve code maintainability, and enhance user 
experience. Let's take a closer look at some of the most influential JavaScript libraries 
and frameworks available today:</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>1. jQuery:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>jQuery</mark></b> is a fast, lightweight, and feature-rich JavaScript library that 
simplifies HTML document traversal, event handling, and animation. It provides an 
intuitive and concise API that enables developers to manipulate the DOM, handle events, 
perform AJAX requests, create animations, and more. jQuery's popularity stems from its 
ability to abstract away the complexities of cross-browser compatibility and provide an 
easy-to-use interface for common JavaScript operations.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>2. React:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> is a powerful JavaScript library developed by Facebook for building user 
interfaces. It adopts a component-based architecture, allowing developers to build 
reusable UI components and efficiently update and render them as the application's state 
changes. React leverages a virtual DOM, which minimizes actual DOM manipulations and 
optimizes performance. React's popularity is driven by its simplicity, performance, 
and thriving ecosystem.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>3. Vue.js:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Vue.js</mark></b> is a progressive JavaScript framework that excels in building user 
interfaces. It boasts a gentle learning curve, making it accessible to newcomers, while 
providing advanced features for seasoned developers. Vue.js embraces a component-based 
development approach, where complex user interfaces are constructed by composing self-
contained and reusable components. It offers powerful features such as declarative 
rendering, two-way data binding, computed properties, and a sophisticated reactivity 
system. Vue.js's versatility and ease of integration with existing projects have 
contributed to its popularity.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2>Introduction to jQuery, React, and Vue.js</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Let's dive deeper into the key features and benefits of three influential JavaScript 
libraries and frameworks: <b><mark>jQuery, React, and Vue.js</mark></b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>jQuery</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Simplified DOM Manipulation:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>jQuery provides a unified and streamlined API for <b><mark>DOM manipulation</mark></b>, 
making it effortless to select and modify HTML elements, handle events, and traverse the 
DOM tree.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Cross-Browser Compatibility:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>jQuery abstracts away the differences in browser implementations, ensuring consistent behavior 
and easing the pain of dealing with browser quirks and inconsistencies.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>AJAX</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>jQuery simplifies <b><mark>AJAX</mark></b> communication by providing a set of convenient 
methods for making asynchronous requests to servers, handling responses, and updating 
content on the webpage dynamically. Rich Plugin Ecosystem: jQuery boasts a vast 
ecosystem of plugins that extend its functionality. These plugins cover a wide range of 
use cases, from UI widgets and effects to data visualization and form validation.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>React Component-Based Architecture:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>React revolutionized the web development landscape with its <b><mark>component-based 
architecture</mark></b>. Components encapsulate the logic and presentation of UI elements, 
allowing for modular development, code reusability, and easier testing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Virtual DOM:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>React employs a <b><mark>virtual DOM</mark></b>, a lightweight in-memory representation of the
actual DOM. By using a virtual DOM, React optimizes rendering performance by selectively
updating only the necessary parts of the UI, resulting in efficient and responsive
applications.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Unidirectional Data Flow:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> promotes a <b><mark>unidirectional data flow</mark></b>, where data flows 
from parent components to child components. This one-way data binding simplifies 
debugging, improves code predictability, and reduces side effects.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>React Native:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>React also offers <b><mark>React Native</mark></b>, a framework for building cross-platform 
mobile applications using JavaScript. With React Native, developers can write code once 
and deploy it on both iOS and Android platforms, saving time and effort.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Vue.js:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Approachable Learning Curve:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Vue.js</mark></b> stands out for its simplicity and ease of learning. Its gentle 
learning curve enables developers to quickly grasp its core concepts and start building 
applications. The <b><mark>Vue CLI (Command Line Interface)</mark></b> provides a scaffold for 
setting up Vue.js projects with ease.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Flexible and Versatile:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Vue.js</mark></b> is designed to be flexible and adaptable to various project sizes 
and requirements. Whether you're building a small application or a large-scale single-
page application, Vue.js provides the necessary tools and features to handle the task 
at hand.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Vue Router and Vuex:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Vue.js offers official plugins, such as Vue Router and Vuex, that seamlessly integrate 
with the framework. Vue Router facilitates navigation between different views in a Vue.js 
application, while Vuex provides a state management pattern for managing application-wide data.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="3-image-carousels">• Image Carousels #3 JavaScript libraries for Image Carousels: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Image Carousel #3 JS Libraries for Image Carousels</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type</th>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="4-games">• Games #4 JavaScript libraries for Games: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Games #4 JS Libraries for Games</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type</th>
  </tr>
</table>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="5-info-graphics">• Info Graphics #5 JavaScript libraries for Information Graphics: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Info Graphics #5 JS Libraries for Information Graphics</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type</th>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="6-image-3d">• Image &amp; 3-D Effects #6 JS libraries for Image and 3-D Effects for the canvas element: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Image &amp; 3-D Effects #6 JavaScript Libraries for Image and 3-D Effects for the canvas element</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type</th>
  </tr>
  <tr>
<!-- Three.js 
A popular JavaScript library used for creating and displaying 3D 
computer graphics on the web. It provides a high-level API that abstracts away the 
complexities of WebGL, a low-level graphics API, making it easier for developers to 
work with 3D graphics in the browser. 
-->
    <td><b><a href="https://themeselection.com/javascript-3d-library/?srsltid=AfmBOoqE0onQM6K-D6hFJAftUEq3m_22Z8lI8SaXa_8HUS0GYTLjQjKq#h-three-js" target="_blank" rel="noopener noreferrer">
	  Three.js</a></b></td>
    <td><a href="https://henryegloff.com/awesome-examples-of-three-js/" target="_blank" rel="noopener noreferrer">
	  Three.js</a>
    <td><a href="https://discourse.threejs.org/t/drei-reveal-demo-full-source/22935" target="_blank" rel="noopener noreferrer">
	  Three.js GH</a></td>
    <td><a href="https://codesandbox.io/p/sandbox/drei-reflector-bfplr" target="_blank" rel="noopener noreferrer">
	  Sandbox Three.js</a></td>
    <td>JS</td>
<!--  https://threejs.org/manual/  -->
  </tr>
  <tr>
    <td><b>Anime.js</b></td>
<!--
A lightweight library with a simple API that can animate HTML, CSS, JS, SVG and DOM 
attributes. It has a built-in staggering system, callbacks and controls, and various 
easing and animation effects.
-->
    <td><b><a href="https://animejs.com/" target="_blank" rel="noopener noreferrer">
	  Anime.js</a></b></td>
    <td><a href="https://github.com/topics/animejs?l=vue&o=desc&s=" target="_blank" rel="noopener noreferrer">
	  Anime.js GH</a></td>
    <td><a href="https://freefrontend.com/anime-js-examples/" target="_blank" rel="noopener noreferrer">
	  Anime.js Demo</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>Lottie</b></td>
<!--
A library that renders Adobe After Effects animations exported as JSON with the 
Bodymovin plugin. It allows you to use complex animations created by designers 
without coding them manually.
-->
    <td><b><a href="https://airbnb.io/lottie/#/" target="_blank" rel="noopener noreferrer">
	  Lottie</a></b></td>
    <td><a href="https://github.com/airbnb/lottie" target="_blank" rel="noopener noreferrer">
	  Lottie GH</a></td>
    <td><a href="https://lottiefiles.com/free-animations/demo" target="_blank" rel="noopener noreferrer">
	  Lottie Demo</a></td>
    <a href="https://github.com/airbnb/lottie" target="_blank" rel="noopener noreferrer">
	  JS</a></td>
  </tr>
  <tr>
    <td><b>ScrollReveal</b></td>
<!--
A library for easily animating elements as they enter/leave the viewport. It was 
designed to be robust and flexible, but hopefully you’ll be surprised below at how 
easy it is to pick up.
-->
    <td><b><a href="https://scrollrevealjs.org/" target="_blank" rel="noopener noreferrer">
	  ScrollReveal</a></b></td>
    <td><a href="https://github.com/topics/scrollreveal?l=javascript&o=desc&s=forks" target="_blank" rel="noopener noreferrer">
	  ScrollReveal GH</a></td>
    <td><a href="https://codepen.io/whatthephuc/pen/LjPBZa" target="_blank" rel="noopener noreferrer">
	  ScrollReveal Demo</a></td>
    <td><a href="https://anijs.github.io/examples/scrollreveal/" target="_blank" rel="noopener noreferrer">
	  AniJS Demo</a></td>
<!--  https://github.com/jlmakes/scrollreveal  -->
  </tr>
  <tr>
    <td><b>Popmotion</b></td>
<!--
Tiny animator's toolbox supports keyframe and spring animations for numbers, colors and complex strings.
-->
    <td><b><a href="https://popmotion.io/" target="_blank" rel="noopener noreferrer">
	  Popmotion</a></b></td>
    <td><a href="https://github.com/Popmotion/popmotion" target="_blank" rel="noopener noreferrer">
	  Popmotion GH</a></td>
    <td><a href="https://popmotion.io/pose/examples/accordion/" target="_blank" rel="noopener noreferrer">
	  Pose Examples</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>Mo.js</b></td>
<!--
Motion graphics library provides built-in components to start animating from scratch 
like html, shape, swirl, burst and stagger, but also bring you tools to help craft 
your animation in a most natural way.
-->
    <td><b><a href="https://mojs.github.io/" target="_blank" rel="noopener noreferrer">
	  Mo.js</a></b></td>
    <td><a href="https://github.com/mojs" target="_blank" rel="noopener noreferrer">
	  Mo.js GH</a></td>
    <td><a href="https://codemyui.com/tag/mo-js/" target="_blank" rel="noopener noreferrer">
	  Mo.js Demo</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>Velocity.js</b></td>
<!--
A library that combines the best of jQuery and CSS transitions. It can animate colors, 
transforms, loops, easings, SVGs and more. It can work with or without jQuery and has 
a high performance.
Accelerated JavaScript animation.
-->
    <td><b><a href="http://velocityjs.org/" target="_blank" rel="noopener noreferrer">
	  Velocity.js</a></b></td>
    <td><a href="https://github.com/cohenerickson/Velocity" target="_blank" rel="noopener noreferrer">
	  Velocity GH</a></td>
    <td><a href="https://codemyui.com/tag/velocity-js/" target="_blank" rel="noopener noreferrer">
	  Velocity Demo</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>GSAP</b></td>
<!--
GreenSock Animation Platform - A library for building high-performance animations that work in every major browser. It can animate anything on the web, including CSS, SVG, canvas, React, Vue and more. It has advanced features like motion paths, physics, morphing and more.
-->
    <td><b><a href="https://gsap.com/" target="_blank" rel="noopener noreferrer">
	  GSAP.com</a></b></td>
    <td><a href="https://github.com/greensock/GSAP" target="_blank" rel="noopener noreferrer">
	  GSAP GH</a></td>
    <td><a href="https://codepen.io/GreenSock/collections/" target="_blank" rel="noopener noreferrer">
	  GSAP Examples</a></td>
    <td><a href="https://gsap.com/demos/" target="_blank" rel="noopener noreferrer">
	  GSAP Demos</a></td>
  </tr>
  <tr>
    <td><b>ScrollMagic</b></td>
<!--
A library for creating scroll interactions with JavaScript and CSS. It can trigger animations based on scroll position and pin elements within the viewport. It has over 11K stars on GitHub.
-->
    <td><b><a href="https://scrollmagic.io/" target="_blank" rel="noopener noreferrer">
	  ScrollMagic.io</a></b></td>
    <td><a href="https://github.com/ANSHPG/SCROLL-MAGIC" target="_blank" rel="noopener noreferrer">
	  ScrollMagic GH</a></td>
    <td><a href="https://scrollmagic.io/examples/" target="_blank" rel="noopener noreferrer">
	  ScrollMagic Examples</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>Typed.js</b></td>
<!--
A library that types. Enter in any string, and watch it type at the speed you've set, 
backspace what it's typed, and begin a new sentence for however many strings you've set.
-->
    <td><b><a href="https://github.com/mattboldt/typed.js" target="_blank" rel="noopener noreferrer">
	  Typed.js</a></b></td>
    <td><a href="https://github.com/mattboldt/typed.js" target="_blank" rel="noopener noreferrer">
	  Typed.js GH</a></td>
    <td><a href="https://codepen.io/merb/pen/yOwJjj" target="_blank" rel="noopener noreferrer">
	  Typed.js Codepen</a></td>
    <td>JS</td>
  </tr>
</table>

<h5><b>Three.js</b> (99.1k ⭐)</h5>
<p>— A popular JavaScript library used for creating and displaying 3D 
computer graphics on the web. It provides a high-level API that abstracts away the 
complexities of WebGL, a low-level graphics API, making it easier for developers to 
work with 3D graphics in the browser.</p>

<h5><b>Anime.js</b> (48.8k ⭐)</h5>
<p>— A lightweight library with a simple API that can animate HTML, 
CSS, JS, SVG and DOM attributes. It has a built-in staggering system, callbacks and 
controls, and various easing and animation effects.</p>

<h5><b>Lottie</b> (29.7k ⭐)</h5>
<p>— A library that renders Adobe After Effects animations exported 
as JSON with the Bodymovin plugin. It allows you to use complex animations created 
by designers without coding them manually.</p>

<h5><b>ScrollReveal</b> (22.1k ⭐)</h5>
<p>— A library for easily animating elements as they enter/leave 
the viewport. It was designed to be robust and flexible, but hopefully you’ll be 
surprised below at how easy it is to pick up.</p>

<h5><b>Popmotion</b> (19.8k ⭐)</h5>
<p>— Tiny animator's toolbox supports keyframe and spring animations 
for numbers, colors and complex strings.</p>

<h5><b>Mo.js</b> (18.3k ⭐)</h5>
<p>— Motion graphics library provides built-in components to start 
animating from scratch like html, shape, swirl, burst and stagger, but also bring 
you tools to help craft your animation in a most natural way.</p>

<h5><b>Velocity.js</b> (17.3k ⭐)</h5>
<p>— A library that combines the best of jQuery and CSS transitions.
It can animate colors, transforms, loops, easings, SVGs and more. 
It can work with or without jQuery and has a high performance.</p>

<h5><b>GSAP</b> (18.7k ⭐)</h5>
<p>— A library for building high-performance animations that work in 
every major browser. It can animate anything on the web, including CSS, SVG, canvas, 
React, Vue and more. It has advanced features like motion paths, physics, morphing 
and more.</p>

<h5><b>ScrollMagic</b> (14.8k ⭐)</h5>
<p>— A library for creating scroll interactions with JavaScript 
and CSS. It can trigger animations based on scroll position and pin elements within 
the viewport. It has over 11K stars on GitHub.</p>

<h5><b>Typed.js</b> (14.8k ⭐)</h5>
<p>— A library that types. Enter in any string, and watch it type 
at the speed you've set, backspace what it's typed, and begin a new sentence for 
however many strings you've set.</p>

<table>
  <tr>
    <th></th>
  </tr>
  <tr>
    <td><b>name</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GitHub</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS</td>
  </tr>
</table>
<h2 id="svg">Top 10 SVG Pattern Generators</h2>
<p>An SVG pattern generator is a tool that creates unique and customizable patterns using 
Scalable Vector Graphics (SVG). The generator allows you to adjust parameters such as 
color, size, shape, and pattern density to create a pattern that fits specific needs.</p>

<h3><b>Hero Patterns</b>:</h3>
<p>A collection of repeatable SVG background patterns for you to use on your web projects.</p>
<h3><b>Softr</b>:</h3>
<p>A free tool made by Softr for creating random organic-looking shapes that can be used 
to add a nice touch to your landing page design, video thumbnail, social media banner, 
or any other visual.</p>
<h3><b>BGJar</b>:</h3>
<p>Free svg background generator for your websites, blogs and app.</p>
<h3><b>fffuel</b>:</h3>
<p>A collection of color tools and free SVG generators for gradients, patterns, textures, 
shapes & backgrounds.</p>
<h3><b>SVG Doodles!</b>:</h3>
<p>A free collection of 50 different editable SVG’s to spice up your online and offline designs.</p>
<h3><b>PatternPad</b>:</h3>
<p>It generates graphical patterns based on a variety of parameters. This results in an 
endless number of variations. You can choose from popular styles or create your own 
individual pattern.</p>
<h3><b>SVGeez</b>:</h3>
<p>Totally awesome, well-stretched CSS svg background patterns, free for download.</p>
<h3><b>VISIWIG</b>:</h3>
<p>This tool allows users to customize seamless patterns, change the size, rotation, 
color, and stroke width of the patterns.</p>
<h3><b>Pattern Monster</b>:</h3>
<p>A simple online pattern generator to create repeatable SVG patterns. Perfect for 
website backgrounds, apparel, branding, packaging design and more.</p>
<h3><b>Super Designer</b>:</h3>
<p>This tool lets you create Doodle-like patterns using a tile system.</p>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="7-strings-math">• Strings &amp; Math #7 JavaScript libraries for Strings and Math Functions: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Database Handling #8 JS Libraries for Database Handling</caption>
  <tr>
	<th><b>JS library Name</b></th>
	<th>Website:</th>
	<th>GitHub:</th>
    <th>Demo:</th>
    <th>Type of library/framework:</th>
  </tr>
  <tr>
    <td>Data1</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="8-database-handling">• DataBase Handling #8 JavaScript libraries for Database Handling: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Database Handling #8 JS Libraries for Database Handling</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type/language</th>
  </tr>
  <tr>
    <td><b>Name of website</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="9-touch-gestures">• Touch Gestures #9 JavaScript libraries for Touch Gestures: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Touch Gestures #9 JS Libraries for Touch Gestures</caption>
  <tr>
    <th><b>Name</b></th>
	<th>Website</th>
	<th>GitHub</th>
	<th>Demo</th>
	<th>Type/language</th>
  </tr>
  <tr>
    <td><b>Name of website</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2><a href="https://byby.dev/js-search-libraries">Top 6 JavaScript SEARCH Libraries</a></h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>JavaScript search libraries are tools that enable you to perform full-text search on 
data using JavaScript, either on the browser or on the server. They can help you create 
fast and user-friendly search experiences for your web applications, without relying on 
external search services or databases.</p>

<h3><b>Fuse.js</b> (17.6k ⭐)</h3>
<p>— A powerful, lightweight fuzzy-search library, with zero dependencies. It allows you 
to perform approximate string matching on the client-side or the backend, without setting 
up a dedicated search service. You can use it to search through arrays of strings or 
objects, with different options for weighting, nesting, and extended search syntax.</p>

<h3><b>List.js</b> (11.2k ⭐)</h3>
<p> — A vanilla JavaScript library that adds search, sort, filters and flexibility to 
plain HTML lists, tables, or anything. It can work with existing HTML or create its own 
HTML from scratch. You can customize the options for value names, item templates, 
pagination and more.</p>

<h3><b>FlexSearch.js</b> (12k ⭐)</h3>
<p> — A next-generation full-text search library for Browser and Node.js with zero 
dependencies. It claims to be the web’s fastest and most memory-efficient search library, 
with features like contextual indexing, document indexing, web workers, and more.</p>

<h3><b>Lunr.js</b> (8.8k ⭐)</h3>
<p>— A small, full-text search library for use in the browser or on the server with 
Node.js. It indexes JSON documents and provides a simple search interface for retrieving 
documents that best match text queries. It is designed to be easy to set up and use, 
without the need for external search services.</p>

<h3><b>Orama</b> (8.2k ⭐)</h3>
<p>— A fast, batteries-included, full-text search engine entirely written in TypeScript, 
designed to work on any runtime and has no dependencies. Orama also supports plugins to 
extend its functionality and integrate with other frameworks.</p>

<h3><b>MiniSearch</b> (4.2k ⭐)</h3>
<p>— A tiny but powerful in-memory fulltext search engine written in JavaScript. It is 
respectful of resources, and it can comfortably run both in Node and in the browser. 
MiniSearch addresses use cases where full-text search features are needed (e.g. prefix 
search, fuzzy search, ranking, boosting of fields…), but the data to be indexed can fit 
locally in the process memory.</p>


<h7>Date Created: 5/27/2025 10:00p<br>
Date Last Editted: 5/27/2025 10:41p</h7>
Date Last Editted: 5/28/2025 12:35p</h7>
