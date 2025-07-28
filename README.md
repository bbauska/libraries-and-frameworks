<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~ README.md of https://github.com/bbauska/libraries-and-frameworks ~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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
(jquery.com)</mark></b>. Chances are, if you use a library, it will be that one (or at 
least that one first). Written in 2005 by John Resig, jQuery has found its way into over 
two-thirds of all websites. Furthermore, if a site uses a library at all, there is a 97% 
chance that it’s jQuery.</p>

<p>It is free, it’s open source, and it employs a syntax that makes it easy to use if you 
are already handy with CSS, JavaScript, and the DOM. You can supplement jQuery with the 
jQuery UI library, which adds cool interface elements such as calendar widgets, drag-
and-drop functionality, expanding accordion lists, and simple animation effects. jQuery 
Mobile is another jQuery-based library that provides UI elements and polyfills designed 
to account for the variety of mobile browsers and their notorious quirks.</p>

<p>Of course, jQuery isn’t the only library in town. Others include 
<b><mark>(<a href="https://mootools.net/" target="_blank" rel="noopener noreferrer">
MooTools mootools.net</a>)</mark></b>, 
<b><mark><a href="https://dojotoolkit.org/" target="_blank" rel="noopener noreferrer">
Dojo (dojotoolkit.org)</a></mark></b>, and <b><mark><a href="http://prototypejs.org/" 
target="_blank" rel="noopener noreferrer">Prototype (prototypejs.org)</a></mark></b>. 
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
<!-- Forms.js  -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--
<p>Is an advanced, lightweight JavaScript library designed to ease form 
creation and management. Utilizing JSON for data input, it generates dynamic, 
user-centric forms, offering an unparalleled development experience.</p>
-->
<table style="width:75%" border="!">
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
  <!-- SurveyJS - Automate forms workflow and retain full ownership of respondent data.  -->
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
  <!-- Parsley JS - Form validation library  -->
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
  <!-- Form validation - Form validation library  -->
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
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="3-image-carousels">• Image Carousels #3 JavaScript libraries for Image Carousels: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Image Carousel #3 JS Libraries for Image Carousels</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo/Example</th>
    <th>Desc'n</th>
  </tr>
  <tr>
    <td><b>Swiper</b></td>
    <td><a href="https://swiperjs.com/" target="_blank" rel="noopener noreferrer">
      SwiperJS</a></td>
    <td><a href="https://github.com/nolimits4web/swiper" target="_blank" rel="noopener noreferrer">
      SwiperJS GH</a></td>
    <td><a href="https://swiperjs.com/demos" target="_blank" rel="noopener noreferrer">
      SwiperJS Demos</a></td>
    <td>Swiper is the most modern free mobile touch slider</td>
  </tr>
  <tr>
    <td><b>Owl Carousel 2</b></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2</a></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2 GH</a></td>
    <td><a href="https://owlcarousel2.github.io/OwlCarousel2/demos/demos.html" target="_blank" rel="noopener noreferrer">
      Owl Carousel 2 Demo</a></td>
    <td>Touch enabled jQuery plugin</td>
  </tr>
  <tr>
    <td><b>Slick Slider</b></td>
    <td><a href="https://kenwheeler.github.io/slick/" target="_blank" rel="noopener noreferrer">
      Slick Slider</a></td>
    <td><a href="https://github.com/kenwheeler/slick" target="_blank" rel="noopener noreferrer">
      Slick Slider GH</a></td>
    <td><a href="https://kenwheeler.github.io/slick/" target="_blank" rel="noopener noreferrer">
      Slick Slider Demo</a></td>
    <td>Fully responsive</td>
  </tr>
  <tr>
    <td><b>ItemSlider</b></td>
    <td><a href="https://github.com/codrops/ItemSlider" target="_blank" rel="noopener noreferrer">
      ItemSlider</a></td>
    <td><a href="https://github.com/codrops/ItemSlider" target="_blank" rel="noopener noreferrer">
      ItemSlider GH</a></td>
    <td><a href="https://smartslider3.com/sample-sliders/" target="_blank" rel="noopener noreferrer">
      Item Slider Demo</a></td>
    <td>CSS animations and jQuery</td>
  </tr>
  <tr>
    <td><b>blueimp Gallery</b></td>
    <td><a href="https://blueimp.github.io/Gallery/" target="_blank" rel="noopener noreferrer">
      blueimp Gallery</a></td>
    <td><a href="https://blueimp.github.io/Gallery/"  target="_blank" rel="noopener noreferrer">
      blueimp Gallery GH</a></td>
    <td>blueimp Example/Demo</td>
    <td>Touch-enabled, responsive and customizable image &amp; video gallery</td>
  </tr>
  <tr>
    <td><b>Phaser</b></td>
    <td><a href="https://phaser.io/">phaser.io</a></td>
    <td><a href="">GH</a></td>
    <td>"Candy Crush Saga" &amp; Phaser</td>
    <td>Desc'n</td>
  </tr>
  <tr>
    <td><b>Three.js</b></td>
    <td><a href="https://threejs.org/">threejs.org</a></td>
    <td><a href="">GH</td>
    <td>"A-Frame" &amp; "Google Chrome Experiments"</td>
    <td>Eases working with WebGL</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="4-games">• Games #4 JavaScript libraries for Games: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Games #4 JavaScript Libraries for Games</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo/Example</th>
    <th>Desc'n</th>
  </tr>
  <tr>
    <td><b>Balyon.js</b></td>
    <td><a href="https://www.babylonjs.com/">babylonjs.com</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td>"Gangs of Space" &amp; "The Legend of Zelda: Ocarina of Time"</td>
    <td>Another powerful 3-D engine</td>
  </tr>
  <tr>
    <td><b>PlayCanvas</b></td>
    <td>PlayCanvas</td>
    <td>GH</td>
    <td>"Lumberjack" &amp; "Gundam Battle"</td>
    <td></td>
  </tr>
  <tr>
    <td><b>Coco2d-JS</b></td>
    <td>Coco2d-JS</td>
    <td>GH</td>
    <td>"Clash of Kings" &amp; "Badland"</td>
    <td>Cocos2d-JS</td>
  </tr>
  <tr>
    <td><b>MelonJS</b></td>
    <td>MelonJS</td>
    <td>GH</td>
    <td>"Grape Escape" &amp; "Box2D"</td>
    <td></td>
  </tr>
  <tr>
    <td><b>Phaser</b></td>
    <td></td>
    <td>GH</td>
    <td>"Candy Crush Saga"-partially, "Slither.io"</td>
    <td></td>
  </tr>
  <tr>
    <td><b>Three.js</b></td>
    <td></td>
    <td>GH</td>
    <td>"A-Frame", "Google Chrome Experiments"</td>
    <td></td>
  </tr>
  <tr>
    <td><b>PlayCanvas</b></td>
    <td></td>
    <td>GH</td>
    <td>"Lumberjack","Gundam Battle"</td>
    <td></td>
  </tr>
  <tr>
    <td><b>PIXI.js</b></td>
    <td></td>
    <td>GH</td>
    <td>"Super Mario 64 HD", "Frogger"</td>
    <td></td>
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
    <th>Demo/Example</th>
    <th>Desc'n</th>
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
    <td><a href="https://henryegloff.com/awesome-examples-of-three-js/" 
      target="_blank" rel="noopener noreferrer">Three.js</a></td>
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
    <td><a href="https://animejs.com/" target="_blank" rel="noopener noreferrer">
      Anime.js</a></td>
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
    <td><a href="https://github.com/topics/scrollreveal?l=javascript&o=desc&s=forks" target="_blank" rel="noopener noreferrer">ScrollReveal GH</a></td>
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
    <td><a href="https://popmotion.io/" target="_blank" rel="noopener noreferrer">
      Popmotion</a></td>
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
    <td><a href="https://mojs.github.io/" target="_blank" rel="noopener noreferrer">
      Mo.js</a></td>
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
    <td><a href="http://velocityjs.org/" target="_blank" rel="noopener noreferrer">
      Velocity.js</a></td>
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
    <td><a href="https://gsap.com/" target="_blank" rel="noopener noreferrer">
      GSAP.com</a></td>
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
    <td><a href="https://scrollmagic.io/" target="_blank" rel="noopener noreferrer">
      ScrollMagic.io</a></td>
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
    <td><a href="https://github.com/mattboldt/typed.js" target="_blank" rel="noopener noreferrer">
      Typed.js</a></td>
    <td><a href="https://github.com/mattboldt/typed.js" target="_blank" rel="noopener noreferrer">
      Typed.js GH</a></td>
    <td><a href="https://codepen.io/merb/pen/yOwJjj" target="_blank" rel="noopener noreferrer">
      Typed.js Codepen</a></td>
    <td>JS</td>
  </tr>
  <tr>
    <td><b>Three.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Short Desc'n</td>
  </tr>
<!-- Three.js (99.1k ⭐)— A popular JavaScript library used for creating and displaying 3D 
computer graphics on the web. It provides a high-level API that abstracts away the 
complexities of WebGL, a low-level graphics API, making it easier for developers to 
work with 3D graphics in the browser.</p>
-->
  <tr>
    <td><b>Anime.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>3d computing graphics</td>
  </tr>
<!-- Anime.js (48.8k ⭐) — A lightweight library with a simple API that can animate HTML, 
CSS, JS, SVG and DOM attributes. It has a built-in staggering system, callbacks and 
controls, and various easing and animation effects.
-->
  <tr>
    <td><b>Lottie</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Renders Adobe After Effects</td>
  </tr>
<!-- Lottie (29.7k ⭐) — A library that renders Adobe After Effects animations exported 
as JSON with the Bodymovin plugin. It allows you to use complex animations created 
by designers without coding them manually.
-->
  <tr>
    <td><b>Three.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Short Desc'n</td>
  </tr>
<!-- ScrollReveal (22.1k ⭐) — A library for easily animating elements as they enter/leave 
the viewport. It was designed to be robust and flexible, but hopefully you’ll be 
surprised below at how easy it is to pick up.
-->
  <tr>
    <td><b><b>Three.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Short Desc'n</td>
  </tr>
  <tr>
    <td><b><b>Popmotion</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Tiny toolbox for keyframe and sprint animations</td>
  </tr>
<!-- Popmotion (19.8k ⭐) — Tiny animator's toolbox supports keyframe and spring animations 
for numbers, colors and complex strings.
-->
    <td><b><b>Mo.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Animate from scatch, html, shape, swirl, burst, swagger</td>
  </tr>
<!-- Mo.js (18.3k ⭐)— Motion graphics library provides built-in components to start 
animating from scratch like html, shape, swirl, burst and stagger, but also bring 
you tools to help craft your animation in a most natural way.
-->
  <tr>
    <td><b><b>Velocity.js</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Animate colors, transforms, loops, easings, SVGs, more...</td>
  </tr>
<!-- Velocity.js</b> (17.3k ⭐) — A library that combines the best of jQuery and CSS transitions.
It can animate colors, transforms, loops, easings, SVGs and more. 
It can work with or without jQuery and has a high performance.
-->
  <tr>
    <td><b><b>GSAP</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Animate CSS,SVG,canvas,React,Vue,more...</td>
  </tr>
<!-- GSAP (18.7k ⭐) — A library for building high-performance animations that work in 
every major browser. It can animate anything on the web, including CSS, SVG, canvas, 
React, Vue and more. It has advanced features like motion paths, physics, morphing 
and more.
-->
  <tr>
    <td><b><b>ScrollMagic</b></td>
    <td><a href="">Website name</a></td>
    <td><a href="">GH</a></td>
    <td><a href="">Example/Demo</a></td>
    <td>Scroll interactions w/JS</td>
  </tr>
<!-- ScrollMagic (14.8k ⭐) — A library for creating scroll interactions with JavaScript 
and CSS. It can trigger animations based on scroll position and pin elements within 
the viewport. It has over 11K stars on GitHub.
-->
  <tr>
    <td><b>Typed.js</b></td>
    <td><a href="https://mattboldt.com/demos/typed-js/" target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="https://github.com/mattboldt/typed.js/" target="_blank" rel="noopener noreferrer">GitHub</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Library that types</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="6-image-3d-effects">• Image and 3-D effects for the canvas element #6 JavaScript 
libraries for Image and 3-D Effects for the Canvas Element: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Image and 3-D Effects for the Canvas Element #6 JS Libraries for Image and 3-D 
    Effects for the Canvas Elemnent</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo/Example</th>
    <th>Desc'n</th>
  </tr>
  <tr>
    <td><b>Chart.js</b></td>
    <td><a href="https://www.monterail.com/blog/javascript-libraries-data-visualization#ten" 
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
<h2 id="7-string-math">• String &amp; Math Functions #7 JavaScript libraries for Strings and Math 
  Functions: •</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>String &amp; Math Functions #7 JS String and Math Functions</caption>
  <tr>
    <th><b>JS library Name</b></th>
    <th>Website:</th>
    <th>GitHub:</th>
    <th>Demo:</th>
    <th>Desc'n</th>
  </tr>
  <tr>
    <td><b>Math.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Math.js</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Math GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Exaple</td>
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
    <td><a href="https://www.monterail.com/blog/javascript-libraries-data-visualization#first" 
      target="_blank" rel="noopener noreferrer">Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Popular Data visualization library</td>
  </tr>
  <tr>
    <td><b>Chart.js</b></td>
    <td><a href="https://www.monterail.com/blog/javascript-libraries-data-visualization#ten" 
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
    <td><a href="https://swiperjs.com/" target="_blank" rel="noopener noreferrer">
      SwiperJS Website</a></td>
    <td><a href="https://github.com/nolimits4web/swiper" target="_blank" rel="noopener noreferrer">
      SwiperJS GH</a></td>
    <td><a href="https://swiperjs.com/demos" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Mobile touch slider</td>
  </tr>
  <tr>
    <td><b>PhotoSwipe</b></td>
    <td><a href="https://photoswipe.com/" target="_blank" rel="noopener noreferrer">
      PhotoSwipe Website</a></td>
    <td><a href="https://github.com/dimsemenov/PhotoSwipe" target="_blank" rel="noopener noreferrer">
      PhotoSwipe GH</a></td>
    <td><a href="https://github.com/min30327/photoswipe-simplify" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>JS image gallery for mobile &amp; desktop</td>
  </tr>
  <tr>
    <td><b>hammer.js</b></td>
    <td><a href="https://hammerjs.github.io/" target="_blank" rel="noopener noreferrer">
      Hammer.js Website</a></td>
    <td><a href="https://github.com/hammerjs/hammer.js/" target="_blank" rel="noopener noreferrer">
      Hammer GH</a></td>
    <td><a href="https://hammerjs.github.io/tips/" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>JS library for multi-touch gestures</td>
  </tr>
  <tr>
    <td><b>fancyBox</b></td>
    <td><a href="http://fancybox.net/" target="_blank" rel="noopener noreferrer">
	  fancybox.net</a></td>
    <td><a href="https://github.com/fancyapps/fancybox" target="_blank" rel="noopener noreferrer">
	  fancyBox GH</a></td>
    <td><a href="https://fancyapps.com/fancybox/getting-started/" target="_blank" 
	  rel="noopener noreferrer">
	  Get Started</a></td>
    <td><a href="https://fancyapps.com/" target="_blank" rel="noopener noreferrer">
	  <b>Discontinued</b>. jQuery lightbox scripts</a></td>
  </tr>
  <tr>
    <td><b>Slideout</b></td>
    <td><a href="https://slideout.js.org/" target="_blank" rel="noopener noreferrer">Slideout Website</a></td>
    <td><a href="https://github.com/Mango/slideout" target="_blank" rel="noopener noreferrer">Slideout GH</a></td>
    <td><a href="https://dev.to/chrismademe/create-a-simple-slideout-menu-using-vanilla-js-2g14" 
      target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Touch slideout nav menu for mobile web apps</td>
  </tr>
  <tr>
    <td><b>Glide.js</b></td>
    <td><a href="https://glidejs.com/" target="_blank" rel="noopener noreferrer">
      Glide.js Website</a></td>
    <td><a href="https://github.com/glidejs/glide" target="_blank" rel="noopener noreferrer">
      Glide.js GH</a></td>
    <td><a href="https://codesandbox.io/examples/package/@glidejs/glide" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Dependency-free JS slider &amp; carousel</td>
  </tr>
  <tr>
    <td><b>Flickity</b></td>
    <td><a href="https://flickity.metafizzy.co/" target="_blank" rel="noopener noreferrer">
      Flickity Website</a></td>
    <td><a href="https://github.com/metafizzy/flickity" target="_blank" rel="noopener noreferrer">
      Flickity GH</a></td>
    <td><a href="https://codesandbox.io/examples/package/flickity" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Touch, responsive, flickable carousels</td>
  </tr>
  <tr>
    <td><b>bxSlider 4.2.14</b></td>
    <td><a href="https://bxslider.com/" target="_blank" rel="noopener noreferrer">
      bxSlider Website</a></td>
    <td><a href="https://github.com/stevenwanderski/bxslider-4" target="_blank" rel="noopener noreferrer">
      bxSlider GH</a></td>
    <td><a href="https://bxslider.com/examples" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Responsive jQuery content slider</td>
  </tr>
  <tr>
    <td><b>Embla Carousel</b></td>
    <td><a href="https://www.embla-carousel.com/" target="_blank" rel="noopener noreferrer">
      Embla Carousel Website</a></td>
    <td><a href="https://github.com/davidjerleke/embla-carousel" target="_blank" rel="noopener noreferrer">
      Embla Carousel GH</a></td>
    <td><a href="https://www.embla-carousel.com/examples/" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Lightweight carousel library w/fluid motion</td>
  </tr>
  <tr>
    <td><b>lightgallery.js</b></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">lightgallery Website</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">GH</a></td>
    <td><a href="" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
  <tr>
    <td><b>Splide</b></td>
    <td><a href="https://splidejs.com/" target="_blank" rel="noopener noreferrer">
      Splide Website</a></td>
    <td><a href="https://github.com/Splidejs/splide" target="_blank" rel="noopener noreferrer">
      Splide GH</a></td>
    <td><a href="https://splidejs.com/tutorials/" target="_blank" rel="noopener noreferrer">
      Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
  <tr>
    <td><b><a href="https://www.youtube.com/watch?v=jm0K2UELFsk&ab_channel=CodingShiksha" target="_blank" rel="noopener noreferrer">
      lightgallery.js</a></b></td>
    <td><a href="https://www.lightgalleryjs.com/" target="_blank" rel="noopener noreferrer">
      lightGallery Website</a></td>
    <td><a href="https://github.com/sachinchoolur/lightGallery" target="_blank" rel="noopener noreferrer">
      lightGallery GH</a></td>
    <td><a href="https://cdnjs.com/libraries/lightgallery" target="_blank" rel="noopener noreferrer">Demo/Example</a></td>
    <td>Full featured JS image &amp; video gallery</td>
  </tr>
</table>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2><a href="https://byby.dev/js-search-libraries" target="_blank" rel="noopener noreferrer">
Top 6 JavaScript SEARCH Libraries</a></h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<table style="width:75%">
  <caption>Top 6 JavaScript SEARCH Libraries</caption>
  <tr>
    <th><b>Name</b></th>
    <th>Website</th>
    <th>GitHub</th>
    <th>Demo</th>
    <th>Short Desc'n</th>
  </tr>
  <tr>
    <td><b><a href="https://www.fusejs.io/getting-started/installation.html" 
      target="_blank" rel="noopener noreferrer">
      1. Fuse.js</a></b></td>
    <td><a href="https://www.fusejs.io" target="_blank" rel="noopener noreferrer">
      Fuse.js Website</a></td>
<!--
<p>JavaScript search libraries are tools that enable you to perform full-text search on 
data using JavaScript, either on the browser or on the server. They can help you create 
fast and user-friendly search experiences for your web applications, without relying on 
external search services or databases.</p>
<p>— A powerful, lightweight fuzzy-search library, with zero dependencies. It allows you 
to perform approximate string matching on the client-side or the backend, without setting 
up a dedicated search service. You can use it to search through arrays of strings or 
objects, with different options for weighting, nesting, and extended search syntax.<br>
-->
    <td><a href="https://github.com/krisk/Fuse" target="_blank" rel="noopener noreferrer">
      Fuse.js GitHub</a>.</td>
    <td><a href="https://www.fusejs.io/examples.html" target="_blank" rel="noopener noreferrer">
      Fuse.js Examples</a></td>
    <td><a href="https://medium.com/@gurunadhpukkalla/introduction-to-fuse-js-62bc856a2914" target="_blank"
      rel="noopener noreferrer" target="_blank" rel="noopener noreferrer">
      Fuse.js Introduction</a></td>
  </tr>
  <tr>
    <td><b><a href="https://listjs.com/" target="_blank" rel="noopener noreferrer">
      2. List.js</a></b></td>
    <td><a href="https://listjs.com/docs/" target="_blank" rel="noopener noreferrer">
      listjs.com</a></td>
<!--(11.2k ⭐) — A vanilla JavaScript library that adds search, sort, filters and flexibility to 
plain HTML lists, tables, or anything. It can work with existing HTML or create its own 
HTML from scratch. You can customize the options for value names, item templates, 
pagination and more.
-->
    <td><a href="https://github.com/javve/list.js/blob/master/README.md" 
      target="_blank" rel="noopener noreferrer">
      List.js GitHub</a></td>
    <td><a href="https://themesbrand.com/velzon/docs/html/listjs.html" target="_blank" 
      rel="noopener noreferrer">
      LISTJS Docs</a></td>
    <td><a href="https://listjs.com/examples/existing-list/" target="_blank" rel="noopener noreferrer">
      Apply list.js HTML</a></td>
  </tr>
  <tr>
    <td><b><a href="https://emersonbottero.github.io/flexsearch/" target="_blank" 
      rel="noopener noreferrer">
      3. FlexSearch.js</a></b></td>
    <td><a href="https://github.com/nextapps-de/flexsearch" target="_blank" rel="noopener noreferrer">
      flexsearch</a></td>
<!-- (12k ⭐)</td> — A next-generation full-text search library for Browser and Node.js with zero 
dependencies. It claims to be the web’s fastest and most memory-efficient search library, 
with features like contextual indexing, document indexing, web workers, and more.
-->
    <td><a href="https://github.com/nextapps-de/flexsearch-server" target="_blank" rel="noopener noreferrer">
      FlexSearch GH Server</a></td>
    <td><a href="https://github.com/sormy/flex-js" target="_blank" rel="noopener noreferrer">
      flex-js GitHub</a></td>
    <td><a href="https://www.infoq.com/news/2019/03/flexsearch-fast-full-text-search/" 
      target="_blank" rel="noopener noreferrer">
      FlexSearch.js</a></td>
  </tr>
  <tr>
    <td><b><a href="https://lunrjs.com/guides/searching.html" target="_blank" rel="noopener noreferrer">
      4. Lunr.js</a></b></td>
    <td><a href="https://lunrjs.com/" target="_blank" rel="noopener noreferrer">
      Lunrjs.com</a></td>
<!-- (8.8k ⭐)</h3> A small, full-text search library for use in the browser or on the server with 
Node.js. It indexes JSON documents and provides a simple search interface for retrieving 
documents that best match text queries. It is designed to be easy to set up and use, 
without the need for external search services.
-->
    <td><a href="https://github.com/olivernn/lunr.js" target="_blank" rel="noopener noreferrer">
      lunr.js GitHub</a></td>
    <td><a href="https://olivernn.github.io/moonwalkers/" target="_blank" rel="noopener noreferrer">
      Demo</a></td>
    <td><a href="https://lunrjs.com/guides/getting_started.html" target="_blank" rel="noopener noreferrer">
      Getting Started</a></td>
  </tr>
  <tr>
    <td><b><a href="https://orama.com/" target="_blank" rel="noopener noreferrer">
      5. Orama</a></b></td>
    <td><a href="https://docs.orama.com/open-source/" target="_blank" rel="noopener noreferrer">
      Welcome to Orama!</a></td>
<!-- (8.2k ⭐) — A fast, batteries-included, full-text search engine entirely written in TypeScript, 
designed to work on any runtime and has no dependencies. Orama also supports plugins to 
extend its functionality and integrate with other frameworks.
-->
    <td><a href="https://github.com/oramasearch/orama" target="_blank" rel="noopener noreferrer">
      GH Orama.com</a></td>
    <td><a href="https://docs.orama.com/cloud" target="_blank" rel="noopener noreferrer">
      Getting Started</a></td>
    <td><a href="https://nearform.com/insights/advanced-javascript-code-search-with-orama/" 
      target="_blank" rel="noopener noreferrer">
      Advanced Code Search</a></td>
  </tr>
  <tr>
    <td><b><a href="https://lucaong.github.io/minisearch/classes/MiniSearch.MiniSearch.html" 
      target="_blank" rel="noopener noreferrer">
      6. MiniSearch</a></b></td>
    <td><a href="https://makerkit.dev/docs/next-fire/blog-and-docs/search" 
      target="_blank" rel="noopener noreferrer">
      MiniSearch makerkit</a></td>
<!-- (4.2k ⭐) — A tiny but powerful in-memory fulltext search engine written in JavaScript. It is 
respectful of resources, and it can comfortably run both in Node and in the browser. 
MiniSearch addresses use cases where full-text search features are needed (e.g. prefix 
search, fuzzy search, ranking, boosting of fields…), but the data to be indexed can fit 
locally in the process memory.
-->
    <td><a href="https://lucaong.github.io/minisearch/" target="_blank" rel="noopener noreferrer">
      GH MiniSearch</a></td>
    <td><a href="https://lucaongaro.eu/blog/2019/01/30/minisearch-client-side-fulltext-search-engine.html"
      target="_blank" rel="noopener noreferrer">
      Search Engine</a></td>
    <td><a href="https://www.skybluetrades.net/blog/2021/05/2021-05-31-full-text-search-minisearch-alpinejs.html"
     target="_blank" rel="noopener noreferrer">
     Search MiniSearch</a></td>
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
<p><b><mark>jQuery</mark></b> is a fast, lightweight, and feature-rich JavaScript library 
that simplifies HTML document traversal, event handling, and animation. It provides an 
intuitive and concise API that enables developers to manipulate the DOM, handle events, 
perform AJAX requests, create animations, and more. jQuery's popularity stems from its 
ability to abstract away the complexities of cross-browser compatibility and provide an 
easy-to-use interface for common JavaScript operations.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>2. <a href="https://react.dev/" target="_blank" rel="noopener noreferrer">React</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> is a powerful JavaScript library developed by Facebook for 
building user interfaces. It adopts a component-based architecture, allowing developers 
to build reusable UI components and efficiently update and render them as the application's 
state changes. React leverages a virtual DOM, which minimizes actual DOM manipulations and 
optimizes performance. React's popularity is driven by its simplicity, performance, and 
thriving ecosystem.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>3. <a href="https://vuejs.org/" target="_blank" rel="noopener noreferrer">Vue.js</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>Vue.js</mark></b> is a progressive JavaScript framework that excels in 
building user interfaces. It boasts a gentle learning curve, making it accessible to 
newcomers, while providing advanced features for seasoned developers. Vue.js embraces a 
component-based development approach, where complex user interfaces are constructed by 
composing self-contained and reusable components. It offers powerful features such as 
declarative rendering, two-way data binding, computed properties, and a sophisticated 
reactivity system. Vue.js's versatility and ease of integration with existing projects 
have contributed to its popularity.</p>
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
<p><b><mark>jQuery</mark></b> provides a unified and streamlined API for 
<b><mark>DOM manipulation</mark></b>, making it effortless to <b><mark>select and modify 
HTML elements, handle events, and traverse the DOM tree</mark></b>.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Cross-Browser Compatibility:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>jQuery</mark></b> abstracts away the differences in browser implementations, 
ensuring consistent behavior and easing the pain of dealing with browser quirks and 
inconsistencies.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>AJAX:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>jQuery</mark></b> simplifies <b><mark>AJAX</mark></b> communication by 
providing a set of convenient methods for making asynchronous requests to servers, 
handling responses, and updating content on the webpage dynamically.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Rich Plugin Ecosystem:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>jQuery</mark></b> boasts a vast ecosystem of plugins that extend its 
functionality. These plugins cover a wide range of use cases, from UI widgets and 
effects to data visualization and form validation.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>React Component-Based Architecture:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> revolutionized the web development landscape with its 
<b><mark>component-based architecture</mark></b>. Components encapsulate the logic and 
presentation of UI elements, allowing for modular development, code reusability, and 
easier testing.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Virtual DOM:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> employs a <b><mark>virtual DOM</mark></b>, a lightweight 
in-memory representation of the actual DOM. By using a virtual DOM, React optimizes 
rendering performance by selectively updating only the necessary parts of the UI, 
resulting in efficient and responsive applications.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Unidirectional Data Flow:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b><mark>React</mark></b> promotes a <b><mark>unidirectional data flow</mark></b>, 
where data flows from parent components to child components. This one-way data binding 
simplifies debugging, improves code predictability, and reduces side effects.</p>
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
<p><b><mark>Vue.js</mark></b> offers official plugins, such as <b><mark>Vue Router</mark></b> and 
<b><mark>Vuex</mark></b>, that seamlessly integrate with the framework. Vue 
Router facilitates navigation between different views in a Vue.js application, 
while Vuex provides a state management pattern for managing application-wide data.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="8-js-game-engines"><a href="https://www.geeksforgeeks.org/8-best-javascript-game-engines/" 
target="_blank" rel="noopener noreferrer">8 Best JS Game Engines</a>.</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="4-ways-api-call"><a href="https://www.geeksforgeeks.org/ways-to-make-an-api-call-in-javascript/" 
target="_blank" rel="noopener noreferrer">4 Ways to make an API call in JavaScript</a>.</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="svg">Top 10 SVG Pattern Generators</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>An SVG pattern generator is a tool that creates unique and customizable patterns using 
Scalable Vector Graphics (SVG). The generator allows you to adjust parameters such as 
color, size, shape, and pattern density to create a pattern that fits specific needs.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://heropatterns.com/" target="_blank" rel="noopener noreferrer">Hero Patterns</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A collection of repeatable SVG background patterns for you to use on your web projects.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://www.softr.io/" target="_blank" rel="noopener noreferrer">Softr</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A free tool made by Softr for creating random organic-looking shapes that can be used 
to add a nice touch to your landing page design, video thumbnail, social media banner, 
or any other visual.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://bgjar.com/" target="_blank" rel="noopener noreferrer">BGJar</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Free svg background generator for your websites, blogs and app.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://www.fffuel.co/" target="_blank" rel="noopener noreferrer">fffuel</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A collection of color tools and free SVG generators for gradients, patterns, textures, 
shapes & backgrounds.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://svgdoodles.com/" target="_blank" rel="noopener noreferrer">SVG Doodles!</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A free collection of 50 different editable SVG’s to spice up your online and offline designs.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://patternpad.com/" target="_blank" rel="noopener noreferrer">PatternPad</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>It generates graphical patterns based on a variety of parameters. This results in an 
endless number of variations. You can choose from popular styles or create your own 
individual pattern.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://www.svgeez.com/" target="_blank" rel="noopener noreferrer">SVGeez</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Totally awesome, well-stretched CSS svg background patterns, free for download.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://www.visiwig.com/patterns/" target="_blank" rel="noopener noreferrer">VISIWIG</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>This tool allows users to customize seamless patterns, change the size, rotation, 
color, and stroke width of the patterns.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://pattern.monster/" target="_blank" rel="noopener noreferrer">
SVG Pattern Monster</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>A simple online pattern generator to create repeatable SVG patterns. Perfect for 
website backgrounds, apparel, branding, packaging design and more.</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3><a href="https://superdesigner.co/tools/patterns" target="_blank" rel="noopener noreferrer">
Super Designer</a>:</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>This tool lets you create Doodle-like patterns using a tile system.</p>

<h2><a href="https://www.monterail.com/blog/javascript-libraries-data-visualization#a:How-to-Choose-the-Right-JavaScript-Data-Visualization-Library" target="_blank" rel="noopener noreferrer">
18 Top JS Graph Visualization Libraries 2025</a></h2>
<h6>Date Created: 5/27/2025 10:00p<br>
Date Last Editted: 5/27/2025 10:41p<br>
Date Last Editted: 5/28/2025 12:35p<br>
Date Last Editted: 6/05/2025 4:19p<br>
Date Last Editted: 6/11/2025 12:32p<br>
Date Last Editted: 6/15/2025 10:41p<br>
Date Last Editted: 6/19/2025 3:39p</h6>
