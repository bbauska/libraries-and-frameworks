<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!-- README.md of https://github.com/bbauska/libraries-and-frameworks -->
<h1 id="libs-and-frames">JavaScript libraries and frameworks</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2>Libraries and Frameworks in Web Front-End Development</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Benefits of using Libraries and Frameworks</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<ol type="1">
  <li><b>Increased Productivity</b>: Libraries and frameworks provide pre-built solutions 
    for common tasks, reducing development time and effort. They abstract away the 
    complexities, allowing developers to focus on building application-specific features 
    rather than reinventing the wheel.</li>
  <li><b>Code Maintainability and Organization</b>: Libraries and frameworks often 
    encourage best practices and provide guidelines for code organization. By following 
    their patterns and conventions, developers can create well-structured, modular, and 
    maintainable codebases.</li>
  <li><b>Improved Performance</b>: Many libraries and frameworks implement optimizations 
    and performance enhancements behind the scenes. For example, React's virtual DOM 
    efficiently updates the UI, reducing unnecessary re-rendering and enhancing 
    performance.</li>
  <li><b>Cross-Browser Compatibility</b>: Libraries and frameworks handle the nuances and
    inconsistencies across different browsers, ensuring that your code works consistently 
    across various platforms and versions. This saves valuable time spent on browser-
    specific troubleshooting.</li>
  <li><b>Thriving Communities and Ecosystems</b>: Popular libraries and frameworks have 
    vibrant communities and extensive ecosystems. This means you have access to abundant 
    resources, documentation, tutorials, and a supportive community to help you along 
    your development journey.</li>
 </ol>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ajax"><a href="https://www.geeksforgeeks.org/jquery/what-is-ajax/" 
target="_blank" rel="noopener noreferrer">What Is Ajax?</a></h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Ajax</mark></b> (sometimes written AJAX) stands for <b><mark>Asynchronous JavaScript 
And XML</mark></b>. The “XML” part isn’t that important—you don’t have to use XML to use 
Ajax (more on that in a moment). <a href="https://api.jquery.com/jQuery.ajax/" target="_blank" 
rel="noopener noreferrer">jQuery.ajax()</a>.</p>
<a href="https://dev.to/nikola/making-ajax-calls-in-pure-javascript-the-old-way-ed5" 
target="_blank" rel="noopener noreferrer">Making AJAX calls in pure JavaScript, the old 
fashioned way</a>.</p>
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
<h2 id="jquery"><a href="https://jquery.com/" target="_blank" rel="noopener noreferrer">
jQuery and Other Libraries</a></h2>
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

<p>Of course, jQuery isn’t the only library in town. Others include 
<b><mark>(<a href="https://mootools.net/" target="_blank" rel="noopener noreferrer">MooTools mootools.net</a>)</mark></b>, 
<b><mark><a href="https://dojotoolkit.org/" target="_blank" rel="noopener noreferrer">Dojo (dojotoolkit.org)</a></mark></b>, and 
<b><mark><a href="http://prototypejs.org/" target="_blank" rel="noopener noreferrer">Prototype (prototypejs.org)</a></mark></b>. 
As for smaller JS libraries that handle specialized functions, because they are being 
created and made obsolete all the time, I recommend doing a web search for it.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="js-libs">JavaScript Libraries</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>“JavaScript libraries for _____________” and see what is available. Some library 
categories include the following:</h3>
<h4>
<ol start="1">
  <li id="#1-forms">• Forms •</li>
  <li id="#2-animation">• Animation •</li>
  <li id="#3-image-carousels">• Image carousels •</li>
  <li id="#4-games">• Games •</li>
  <li id="#5-info-graphics">• Information graphics •</li>
  <li id="#6-image-3d-effects">• Image and 3-D effects for the canvas element •</li>
  <li id="#7-string-math">• String and math functions •</li>
  <li id="#8-db-handling">• Database handling •</li>
  <li id="#9-touch-gestures">• Touch gestures •</li>
</ol>
</h4>
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
    <td><a href="https://preview.keenthemes.com/jet-html-free/documentation/forms/formvalidation/basic.html" 
      target="_blank" rel="noopener noreferrer">
      formvalidation Demo</a></td>
    <td>JS, YAML</td>
  </tr>
  <!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <!--  <h4>ValidateJS</h4>  -->
  <!--    <td>Form validation library</td>  -->
  <!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://validatejs.org/" target="_blank" rel="noopener noreferrer">ValidateJS</a></b></td>
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
    <td><b><a href="https://formbuilder.online/" target="_blank" rel="noopener noreferrer">
	  Formbuilder</a></b></td>
    <td><a href="https://help.form.io/developers/form-development/form-builder" 
	  target="_blank" rel="noopener noreferrer">
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
  <!--  <h4>Formbuilder.dev</h4>  -->
  <!--    <td>Online form builder</td>  -->
  <!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
  <tr>
    <td><b><a href="https://formbuilder.online/" target="_blank" rel="noopener noreferrer">
      Formbuilder.dev</a></b></td>
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
    <td><b><a href="https://react-hook-form.com/" target="_blank" rel="noopener noreferrer">
      React Hook Form</a></b></td>
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
<!-- <p>A versatile library for image cropping and resizing directly in the browser.</p>  -->
<table style="width:75%">
  <tr>
    <th>Name</th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo</th>
    <th>Type</th>
  </tr>
  <tr>
    <td><b><a href="https://fengyuanchen.github.io/cropperjs/v1/" 
      target="_blank" rel="noopener noreferrer">Cropper.js</a></b></td>
    <td><a href="https://fengyuanchen.github.io/cropperjs/v1/" 
      target="_blank" rel="noopener noreferrer">Cropper.js</a></td>
    <td><a href="https://github.com/fengyuanchen/cropperjs" 
      target="_blank" rel="noopener noreferrer">Cropper.js GH</a></td>
    <td><a href="https://fengyuanchen.github.io/photo-editor/" 
      target="_blank" rel="noopener noreferrer">Cropper.js demo</a></td>
    <td><a href="">JavaScript image cropper</a></td>
  </tr>
  <tr>
    <td><b><a href="https://fabricjs.com/" 
	  target="_blank" rel="noopener noreferrer">Fabric.js</a></b></td>
	<td><a href="">website</a></td>
	<td><a href="">github website</a></td>
	<td><a href="">Demo</a></td>
	<td><a href="">Image manipulation</a></td>
  </tr>
  <tr>
    <td><b><a href="https://cdnjs.com/libraries/camanjs" 
      target="_blank" rel="noopener noreferrer">CamanJS</a><b></td>
	<td><a href="">website</a></td>
	<td><a href="https://github.com/meltingice/CamanJS" 
      target="_blank" rel="noopener noreferrer">GitHub</a></td>
	<td><a href="https://www.sitepoint.com/manipulating-images-web-pages-camanjs/" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href=""></a></td>
  </tr>
  <tr>
    <td><b><a href="https://pixijs.com/" 
      target="_blank" rel="noopener noreferrer"</a><b>PixiJS</td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">website</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">GH</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Image manipulation and effects</a></td>
  </tr>
  <tr>
    <td><b><a href="https://threejs.org/" 
      target="_blank" rel="noopener noreferrer">three.js</a></b></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">website</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">GH</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">3D scenes, animations, and effects</a></td>
  </tr>
  <tr>
    <td><b><a href="https://www.babylonjs.com/" 
      target="_blank" rel="noopener noreferrer">Babylon.js</a></b></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">website</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">GH</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">3d engine like three.js</a></td>
  </tr>
  <tr>
    <td><b><a href="https://zzz.dog/" 
      target="_blank" rel="noopener noreferrer">Zdog</a></b></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">website</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">GH</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">lightweight library of pseudo-3d designs</a></td>
  </tr>
  <tr>
    <td><b><a href="https://aframe.io/docs/1.7.0/introduction/" 
      target="_blank" rel="noopener noreferrer">A-Frame</a></b></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">website</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">GH</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">Demo</a></td>
	<td><a href="" 
      target="_blank" rel="noopener noreferrer">WebVR Experience maker</a></td>
  </tr>
</table>
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
<h3>1. <a href="https://jquery.com/" target="_blank" rel="noopener noreferrer">jQuery</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>jQuery</mark></b> is a fast, lightweight, and feature-rich JavaScript library that 
simplifies HTML document traversal, event handling, and animation. It provides an 
intuitive and concise API that enables developers to manipulate the DOM, handle events, 
perform AJAX requests, create animations, and more. jQuery's popularity stems from its 
ability to abstract away the complexities of cross-browser compatibility and provide an 
easy-to-use interface for common JavaScript operations.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>2. <a href="https://react.dev/" target="_blank" rel="noopener noreferrer">React</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> is a powerful JavaScript library developed by Facebook for building user 
interfaces. It adopts a component-based architecture, allowing developers to build 
reusable UI components and efficiently update and render them as the application's state 
changes. React leverages a virtual DOM, which minimizes actual DOM manipulations and 
optimizes performance. React's popularity is driven by its simplicity, performance, 
and thriving ecosystem.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>3. <a href="https://vuejs.org/" target="_blank" rel="noopener noreferrer">Vue.js</a>:</h3>
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
  <tr>
    <td><b>Swiper</b></td>
    <td><a href="https://swiperjs.com/" target="_blank" rel="noopener noreferrer">
      SwiperJS</a></td>
    <td><a href="https://github.com/nolimits4web/swiper" target="_blank" rel="noopener noreferrer">
      SwiperJS GH</a></td>
    <td><a href="https://swiperjs.com/demos" target="_blank" rel="noopener noreferrer">
      SwiperJS Demos</a></td>
    <td>Swiper is the most modern free mobile touch slider with hardware accelerated 
      transitions and amazing native behavior. It is intended to be used in mobile 
      websites, mobile web apps, and mobile native/hybrid apps. Swiper is not 
      compatible with all platforms, it is a modern touch slider which is focused only 
      on modern apps/platforms to bring the best experience and simplicity.</td>
  </tr>
  <tr>
    <td><b>Owl Carousel 2</b></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2</a></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2 GH</a></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/demos/demos.html" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2 Demo</a></td>
    <td>Touch enabled jQuery plugin that lets you create a beautiful responsive carousel 
      slider. Owl Carousel has been chosen as the number one jQuery plugin by hundreds 
      of developers. Now its time for a new version that comes with lots of new features 
      and an even more user-friendly API.</td>
  </tr>
  <tr>
    <td><b>Slick Slider</b></td>
    <td><a href="https://kenwheeler.github.io/slick/" target="_blank" rel="noopener noreferrer">
      Slick Slider</a></td>
    <td><a href="https://github.com/kenwheeler/slick" target="_blank" rel="noopener noreferrer">
      Slick Slider GH</a></td>
    <td><a href="https://kenwheeler.github.io/slick/" target="_blank" rel="noopener noreferrer">
      Slick Slider Demo</a></td>
    <td>Fully responsive. Scales with its container. Separate settings per breakpoint 
      Uses CSS3 when available. Fully functional when not. Swipe enabled. Or disabled, 
      if you prefer. Desktop mouse dragging Infinite looping. Fully accessible with 
      arrow key navigation Add, remove, filter & unfilter slides Autoplay, dots, arrows, 
      callbacks, etc...</td>
  </tr>
  <tr>
    <td><b>ItemSlider</b></td>
    <td><a href="https://github.com/codrops/ItemSlider" target="_blank" rel="noopener noreferrer">
      ItemSlider</a></td>
    <td><a href="https://github.com/codrops/ItemSlider" target="_blank" rel="noopener noreferrer">
      ItemSlider GH</a></td>
    <td><a href="https://smartslider3.com/sample-sliders/" target="_blank" rel="noopener noreferrer">
      Item Slider Demo</a></td>
    <td>A tutorial on how to create a simple category slider with a minimal design using 
      CSS animations and jQuery. The idea is to slide the items sequentially depending 
      on the slide direction.</td>
  </tr>
  <tr>
    <td><b>blueimp Gallery</b></td>
    <td><a href="https://blueimp.github.io/Gallery/" target="_blank" rel="noopener noreferrer">
      blueimp Gallery</a></td>
    <td><a href="https://blueimp.github.io/Gallery/"  target="_blank" rel="noopener noreferrer">
      blueimp Gallery GH</a></td>
    <td></td>
    <td>blueimp Gallery is a touch-enabled, responsive and customizable image & video 
      gallery, carousel and lightbox, optimized for both mobile and desktop web browsers. 
      It features swipe, mouse and keyboard navigation, transition effects, slideshow 
      functionality, fullscreen support, and on-demand content loading and can be 
      extended to display additional content types.</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="4-games">• Games #4 JavaScript libraries for Games: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Name:</h3>
<table style="width:75%">
  <caption>Games #4 JS Libraries for Games</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>Key Features</th>
    <th>Advantages</th>
    <th>Disadvantages</th>
    <th>Famous Projects</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>Phaser</b></td>
    <td>https://phaser.io/</td>
    <td>  <!-- key features -->
      <ul>
        <li>Version Control:<br>
          Host your code version in a Git-based repository. We can collaborate through pull 
          requests, code reviews, or just discussions. Project management: With automatic 
          problem tracking and project boards.</li>
	  </ul>
    </td>
	<td>  <!-- advantages -->
	  <ul>
        <li>Community:<br>
          Large following with documentation. Integrates with numerous development and 
          CI/CD tools. Free Plan: Free plan with an unlimited amount of public 
          repositories.</li>
	  </ul>
	</td>
	<td>  <!-- disadvantages -->
	  <ul>
        <li>Pricing:<br>
          This is a paid plan; it includes advanced features and private repositories.</li>
	    <li>Complexity: Can be complex for beginners to navigate.</li>
	  </ul>
    </td>
	<td>  <!-- famouse projects -->
	  <ul>
        <li>"Candy Crush Saga": Although not entirely built with Phaser, elements of the 
          game were created using it for web-based versions.<br>
		  "Slither.io": The online multiplayer game is known for its simple but engaging 
		  gameplay and was developed using Phaser.</li>
      </ul>
    </td>
	<td>  <!-- description -->
        Phaser is an open-source, free framework; it happens to be both fast and 
          allows a developer to create games in HTML5 on the Desktop and Mobile. 
          Including physics, sprite management, and animation systems, it provides one 
          with powerful suites of game development tools. It is heavily documented and 
          has a thriving user community so developers of all experience levels can use 
          it. Doing this depends a lot on WebGL and Canvas, so it can be a cause for 
          real performance issues on lower-end devices.
    </td>
  </tr>
  <tr>
    <td><b>Three.js</b></td>
    <td>https://threejs.org/</td>
    <td>
      <ul>  <!-- key features -->
        <li>3D Rendering:<br>
          It is designed to be user-friendly in making 3D scenes and objects.</li>
        <li>Camera Options:<br>
          In-game options for moving and interacting with the camera.</li>
        <li>Shaders:<br>
          Great support for writing custom shaders.</li>
        <li>Visual Quality:<br>
          This is referred to as high-quality 3D graphics and animations.</li>
        <li>Flexibility:<br>
          Very versatile to a wide range of different 3D projects' needs.</li>
        <li>Community support:<br>
          Good community, useful resources.</li>
      </ul>
    </td>
    <td>Learning Curve:<br>  <!-- disadvantages -->
    Demands good 3D mathematics. This may place a high demand on system resources, which could affect performance on lower-end devices.</td>
    <!-- famous projects -->
    <td>"A-Frame": A web framework for building virtual reality (VR) experiences. Many VR demos use Three.js as their rendering engine. "Google Chrome Experiments": Various projects and interactive experiences featured on the Chrome Experiments site leverage Three.js for stunning visuals.</td>
    <!-- description -->
    <td>Three.js is a JavaScript library that greatly eases working with WebGL, which is an API for low-level and complex graphics. Most importantly, it makes it possible to create real three-dimensional rich content directly in a browser without participation by plug-ins. Its features in composition make Three.js properly ideal for the creation of immersive 3D games with camera controls, lighting, and shading.</td>
  </tr>
  <tr>
    <td><b>Balyon.js</b></td>
    
    <td>https://www.babylonjs.com/</td>
    
    <td>Physics Engine: Integrated support for physics-based interactions. Audio Engine: Powerful sound for an immersive experience. Visual Editor: Integrated visual development environment.</td>
    
    <td>Performance: Engineered to offer peak performance in high. Feature-packed: Contains many features to develop advanced games. Documentation: It has extensive documentation and a large community.</td>
    <td>Complexity High: A firm grasp of 3D development is required. Resource Intensive: May be resource-heavy.</td>
    
    <td>"Gangs of Space": An online multiplayer space shooter game that utilizes Babylon.js for its 3D graphics. "The Legend of Zelda: Ocarina of Time" (3D project): A fan remake that showcases the capabilities of Babylon.js in creating immersive 3D environments.</td>
    
    <td>Another powerful 3-D engine in the hands of developers makes use of the potential of WebGL to create captivating real-time 3-D graphics within a web browser. It also includes robust tools for collision, physics, and audio. Babylon.js comes with its visual editor, speeding up development along with already fast development. One needs to have a pretty good grasp over 3-D mathematics in order to make full use of this. But that's kind of smoothed out by the fact that it offers comprehensive documentation and there is an active community to help you.</td>
  </tr>
  <tr>
    <td><b>PlayCanvas</b></td>
    <td></td>
    <td>Real Time Collaboration: Team based public SMART cloud workspaces. Visual Editor: Drag in anything to build 3D content. Cross-Platform: Development of several platforms.</td>
    <td>User Friendliness: From novice to pro, kindly expect an easy and user-friendly interface. Collaboration: Sharing and real-time collaboration. Performance: High status performed on an optimal level on various devices.</td>
    <td>Cost: Free, but with limited features; other features may be acquired by purchase. It could be hard to learn some advanced features.</td>
    <td>"Lumberjack": A 3D multiplayer game that showcases real-time collaboration features of PlayCanvas. "Gundam Battle": A browser-based game that utilizes PlayCanvas for its engaging 3D graphics and gameplay.</td>
    <td>PlayCanvas is a collaborative gamedev platform with a visual dev environment holding a powerful JavaScript framework. It allows developers to create high-performance 3D games directly in the browser, with maximum compatibility across all devices. Because of this cloud enablement, PlayCanvas allows real-time cooperation and serves excellently for teamwork. Of course, the free version has some of the features limited, but the broad set of opportunities of the platform is still available.</td>
  </tr>
  <tr>
    <td><b>PIXI.js</b></td>
    <td></td>
    <td>Quick Drawing: Full hardware acceleration enables the fastest possible rendering speed. Texture Mapping: Texturing capability mappings. Particle Effects: Built-in support for particle effects.</td>
    <td>Performance: 2 Proactive high yield. User-Friendly: Easy to use and simply combined with other tools. Widespread community backing and ample resource quantities.</td>
    <td>This places it only in 2D rendering and, depending on other libraries, extends its functionality. Complexity: Advanced features may require in-depth knowledge.</td>
    <td>"Super Mario 64 HD": A fan remake that utilizes PIXI.js to enhance its 2D graphics. "Frogger": Various iterations of the classic arcade game have been developed using PIXI.js for its smooth rendering capabilities.</td>
    <td>PIXI.js is a 2D render engine that allows you to create smooth and visually appealing applications. It renders very well by using hardware acceleration, resulting in very good performance for lots of game development features, such as texture mapping, particle effects, and sprite animations. For these reasons, the power of PIXI.js features is combined especially well with the realization of 2D games and interactive UI components. While it focuses only on rendering, it can be paired with other libraries for additional functionality.</td>
  </tr>
  <tr>
    <td><b>Coco2d-JS</b></td>
    <td></td>
    <td>Scene Management: Advanced tools of scene management. It supports skeletal animation, too. Physics: integrated physics engine.</td>
    <td>Versatile: It works for both 2D and 3D game development. Performance: Designed to perform mightily. Community: It is very active, with a helpful community and.</td>
    <td>Lack a few advanced features possibly for advanced projects. Learning and mastering it take time.</td>
    <td>"Clash of Kings": A popular mobile strategy game that uses Cocos2d-JS for its development, especially for 2D graphics. "Badland": A visually stunning action-adventure game that leverages the features of Cocos2d for its animation and gameplay.</td>
    <td>Cocos2d-JS is one of the frameworks for cross-platform game development in the Cocos2d family, supporting 2D and 3D game development, just as some of its features involve scene management, skeletal animations, and a physics engine. Especially, Cocos2d-JS has an excellent reputation for performance and ease of use, so it is generally preferred by mobile game developers. However, for really complex projects, it might not contain some functionalities other frameworks have.</td>
  </tr>
  <tr>
    <td><b>MelonJS</b></td>
    <td></td>
    <td>Collision Detection: Internal collision detection system. Sprite Management: Sprites and Animation Management Tools. Plugin: Wide range of plugin systems to get more features.</td>
    <td>Intuitive and excellent for basic-level users. Performance: lightweight and efficient. Flexibility: Highly customizable using plugins.</td>
    <td>Advanced Features: Limited advanced features pre-packaged with the software. Scalability: Not suitable for large, complex projects.</td>
    <td>"Grape Escape": A platformer game developed using MelonJS, showcasing its capabilities for creating 2D games. "Box2D": A physics-based game that utilizes MelonJS for its collision detection and sprite management features.</td>
    <td>HTML5 is something that the MelonJS game engine is, oriented to be simple and easy to use. It offers such features of 2D game development as collision detection, sprite management, and a powerful plugin system. Lightweight and lean, MelonJS allows effective development with web-based games. It is not very strong in features for developers in need of out-of-the-box functionality.</td>
  </tr>
</table>
<p><a href="https://www.geeksforgeeks.org/8-best-javascript-game-engines/" 
target="_blank" rel="noopener noreferrer">8 Best JS Game Engines</a>.</p>
<p><a href="https://www.geeksforgeeks.org/ways-to-make-an-api-call-in-javascript/" 
target="_blank" rel="noopener noreferrer">4 Ways to make an API call in JavaScript</a>.</p>
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
<h2 id="6-image-3d-effects">• Image &amp; 3-D Effects #6 JS libraries for Image and 3-D 
  Effects for the canvas element: •</h2>
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
    <td><b><a  href="https://themeselection.com/javascript-3d-library/?srsltid=AfmBOoqE0onQM6K-D6hFJAftUEq3m_22Z8lI8SaXa_8HUS0GYTLjQjKq#h-three-js" target="_blank" rel="noopener noreferrer">
      Three.js</a></b></td>
    <td><b><a href="https://henryegloff.com/awesome-examples-of-three-js/" 
      target="_blank" rel="noopener noreferrer">Three.js</a></b></td>
    <td><a href="https://discourse.threejs.org/t/drei-reveal-demo-full-source/22935" 
      target="_blank" rel="noopener noreferrer">Three.js GH</a></td>
    <td><a href="https://codesandbox.io/p/sandbox/drei-reflector-bfplr" target="_blank" 
      rel="noopener noreferrer">Sandbox Three.js</a></td>
    <td>JS</td>
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
    <td><a href="https://github.com/airbnb/lottie" target="_blank" rel="noopener noreferrer">
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
      ScrollReveal CodePen</a></td>
    <td><a href="https://anijs.github.io/examples/scrollreveal/" target="_blank" rel="noopener noreferrer">
      AniJS Examples</a></td>
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
<table>
  <tr>
    <th></th>
  </tr>
  <tr>
    <td><b>Typed.js</b></td>
    <td><a href="https://mattboldt.com/demos/typed-js/" target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="https://github.com/mattboldt/typed.js/" target="_blank" rel="noopener noreferrer">GitHub</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Library that types</td>
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
<h2 id="7-string-math">• String &amp; Math Functions #7 JavaScript libraries for Strings and Math 
  Functions: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Database Handling #8 JS Libraries for Database Handling</caption>
  <tr>
    <th><b>JS library Name</b></th>
    <th>Website:</th>
    <th>GitHub:</th>
    <th>Demo:</th>
    <th>Desc'n</th>
  </tr>
  <tr>
    <td>Math.js</td>
    <td></td>
    <td></td>
    <td></td>
    <td>Comprehensive JS library of Math functions &amp; operators</td>
  </tr>
  <tr>
    <td><b>Numeral.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Lightweight JS library to manipulate &amp; format numbers</td>
  </tr>
  <tr>
    <td><b>D3.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Popular Data visualization library</td>
  </tr>
  <tr>
    <td><b>Chart.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS library to create responsive charts</td>
  </tr>
  <tr>
    <td><b>MathJax</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS library to display math notation on web pages</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="8-db-handling">• DataBase Handling #8 JavaScript libraries for Database Handling: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Database Handling #8 JS Libraries for Database Handling</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo</th>
    <th>Short Desc'n</th>
  </tr>
  <tr>
    <td><b>SQL, query builders, and ORMs</b></td>
    <td><a href="https://github.com/brianc/node-postgres" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>ORM (Object-Relational Mapping) Libraries</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Description</td>
  </tr>
  <tr>
    <td><b>Sequelize</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Library with query builder. Supports PostgresSQL, MySQL, SQLite, & SQL Server</td>
  </tr>
  <tr>
    <td><b>TypeORM</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>ORM for TypeScript &amp; JS</td>
  </tr>
  <tr>
    <td><b>Bookshelf.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Built on Knex.js, supports SQL: MySQL,PostgresSQL &amp; SQLite</td>
  </tr>
  <tr>
    <td><b>Objection.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Minimal library w/TypeScript support</td>
  </tr>
  <tr>
    <td><b>Mongoose</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Most popular library for Node.js, MongoDB</td>
  </tr>
  <tr>
    <td><b>Prism</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>TypeScript-first ORM</td>
  </tr>
  <tr>
    <td><b>MikroORM</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>ORM library</td>
  </tr>
  <tr>
    <td><b>Waterline</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>default ORM for Sales.js, a Node.js framework</td>
  </tr>
  <tr>
    <td><b>Knex.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>query builder as base for ORMs</td>
  </tr>
  <tr>
    <td><b>Database-Specific Libraries</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Description</td>
  </tr>
  <tr>
    <td><b>sql.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>library to run SQLite using WebAssembly</td>
  </tr>
  <tr>
    <td><b>better-sqlite3</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>library for SQLite &amp; bun:sqlite for bun runtime</td>
  </tr>
  <tr>
    <td><b>General DB Libraries</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Description</td>
  </tr>
  <tr>
    <td><b>TaffyDB</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Fast queries &amp; cross-browser support</td>
  </tr>
  <tr>
    <td><b>RxDB</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Supports Rx.js and backends; CouchDB, GraphQL, Firestone &amp; more</td>
  </tr>
  <tr>
    <td><b>MongoDB</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>NoSQL dbms using JSON-like documents, often with Node.js</td>
  </tr>
  <tr>
    <td><b>Other Notables Libraries</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Description</td>
  </tr>
  <tr>
    <td><b>Chart.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS library for responsive data visualizations</td>
  </tr>
  <tr>
    <td><b>GOJS</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS library for building interative diagrams &amp; graphs</td>
  </tr>
  <tr>
    <td><b>Highcharts</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>A charting library written in pure JS</td>
  </tr>
  <tr>
    <td><b>Vue.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Library framework for building user interfaces</td>
  </tr>
  <tr>
    <td><b>Ember Data</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>DB library that comes with Ember.js</td>
  </tr>
  <tr>
    <td><b>Recharts</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Lightweight JS library for interactive charts</td>
  </tr>
  <tr>
    <td><b>amCharts</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Commercial JS library for interactive charts &amp; maps</td>
  </tr>
  <tr>
    <td><b>ApexCharts</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Charting library for responsive charts</td>
  </tr>
  <tr>
    <td><b>Backbone.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>A JS library for building web apps following M-V-P design</td>
  </tr>
  <tr>
    <td><b>C3.js</b></td>
    <td><a href="" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>A JS library for building reusable charts</td>
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
    <th>Short Desc'n</th>
  </tr>
  <tr>
    <td><b>Swiper</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Mobile touch slider</td>
  </tr>
  <tr>
    <td><b>Swiper</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Mobile touch slider</td>
  </tr>
  <tr>
    <td><b>PhotoSwipe</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS image gallery for mobile &amp; desktop</td>
  </tr>
  <tr>
    <td><b>hammer.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>JS library for multi-touch gestures</td>
  </tr>
  <tr>
    <td><b>fancyBox</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td><b>Discontinued</b>. jQuery lightbox scripts</td>
  </tr>
  <tr>
    <td><b>Slideout</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Touch slideout nav menu for mobile web apps</td>
  </tr>
  <tr>
    <td><b>Glide.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Dependency-free JS slider &amp; carousel</td>
  </tr>
  <tr>
    <td><b>Flickity</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Touch, responsive, flickable carousels</td>
  </tr>
  <tr>
    <td><b>bxSlider 4.2.14</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Responsive jQuery content slider</td>
  </tr>
  <tr>
    <td><b>Embla Carousel</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Lightweight carousel library w/fluid motion</td>
  </tr>
  <tr>
    <td><b>lightgallery.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
  <tr>
    <td><b>Splide</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
  <tr>
    <td><b>lightgallery.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Website shortcut</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2><a href="https://byby.dev/js-search-libraries" target="_blank" rel="noopener noreferrer">
Top 6 JavaScript SEARCH Libraries</a></h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>JavaScript search libraries are tools that enable you to perform full-text search on 
data using JavaScript, either on the browser or on the server. They can help you create 
fast and user-friendly search experiences for your web applications, without relying on 
external search services or databases.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://www.fusejs.io/getting-started/installation.html" 
target="_blank" rel="noopener noreferrer">1. Fuse.js</a></b> (17.6k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>— A powerful, lightweight fuzzy-search library, with zero dependencies. It allows you 
to perform approximate string matching on the client-side or the backend, without setting 
up a dedicated search service. You can use it to search through arrays of strings or 
objects, with different options for weighting, nesting, and extended search syntax.<br>
<a href="https://www.fusejs.io/examples.html" target="_blank" rel="noopener noreferrer">
  Fuse.js Examples</a>,<br>
<a href="https://medium.com/@gurunadhpukkalla/introduction-to-fuse-js-62bc856a2914" 
  target="_blank" rel="noopener noreferrer">
  Fuse.js Introduction</a>,<br>
<a href="https://github.com/krisk/Fuse" target="_blank" rel="noopener noreferrer">
  Fuse.js GitHub</a>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://listjs.com/" target="_blank" rel="noopener noreferrer">2. List.js</a></b> (11.2k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p> — A vanilla JavaScript library that adds search, sort, filters and flexibility to 
plain HTML lists, tables, or anything. It can work with existing HTML or create its own 
HTML from scratch. You can customize the options for value names, item templates, 
pagination and more.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://emersonbottero.github.io/flexsearch/" target="_blank" 
rel="noopener noreferrer">3. FlexSearch.js</a></b> (12k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p> — A next-generation full-text search library for Browser and Node.js with zero 
dependencies. It claims to be the web’s fastest and most memory-efficient search library, 
with features like contextual indexing, document indexing, web workers, and more.
FlexSearch Server is available here: https://github.com/nextapps-de/flexsearch-server</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://lunrjs.com/guides/searching.html" target="_blank" 
rel="noopener noreferrer">4. Lunr.js</a></b> (8.8k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>— A small, full-text search library for use in the browser or on the server with 
Node.js. It indexes JSON documents and provides a simple search interface for retrieving 
documents that best match text queries. It is designed to be easy to set up and use, 
without the need for external search services.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://orama.com/" target="_blank" rel="noopener noreferrer">5. Orama</a></b> (8.2k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>— A fast, batteries-included, full-text search engine entirely written in TypeScript, 
designed to work on any runtime and has no dependencies. Orama also supports plugins to 
extend its functionality and integrate with other frameworks.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><b><a href="https://lucaong.github.io/minisearch/classes/MiniSearch.MiniSearch.html" 
target="_blank" rel="noopener noreferrer">6. MiniSearch</a></b> (4.2k ⭐)</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>— A tiny but powerful in-memory fulltext search engine written in JavaScript. It is 
respectful of resources, and it can comfortably run both in Node and in the browser. 
MiniSearch addresses use cases where full-text search features are needed (e.g. prefix 
search, fuzzy search, ranking, boosting of fields…), but the data to be indexed can fit 
locally in the process memory.</p>


<h7>Date Created: 5/27/2025 10:00p<br>
Date Last Editted: 5/27/2025 10:41p<br>
Date Last Editted: 5/28/2025 12:35p<br>
Date Last Editted: 6/05/2025 4:19p<br>
Date Last Editted: 6/11/2025 12:32p</h7>
