Animation libraries & web sites

Animation makes us be able to tell stories and communicate emotions and ideas in a unique way. Here are 30 JavaScript animation libraries to use in your projects today.
1.	Greensock
https://greensock.com/
A JavaScript library for building high-performance animations that work in every major browser
2. VelocityJS
http://velocityjs.org/
Velocity is a lightweight animation engine with the same API as jQuery's $.animate()
3. Lax.js
https://github.com/alexfoxy/laxxx
Simple & lightweight vanilla javascript plugin to create smooth & beautiful animations when you scroll!
4. Rellax.js
https://github.com/dixonandmoe/rellax
A buttery smooth, super lightweight, vanilla javascript parallax library
5. three.js
https://github.com/mrdoob/three.js/
An easy to use, lightweight, 3D library with a default WebGL renderer.
6. wow.js
https://wowjs.uk/
Reveal Animations When You Scroll.
7. Chocolat.js
http://chocolat.insipi.de/
Free lightbox plugin.
8. Animate on Scroll
https://michalsnik.github.io/aos/
Animate on scroll library to reveal animations when You scroll.
9. TiltJS
https://gijsroge.github.io/tilt.js/
A tiny requestAnimationFrame powered 60+fps lightweight parallax hover tilt effect for jQuery.
10. Rough Notation
https://roughnotation.com/
Rough Notation is a small JavaScript library to create and animate annotations on a web page
11. tsParticles
https://particles.matteobruni.it/
A lightweight library for creating particles, an improved version of the abandoned and obsolete particles.js
12. Particles.js
https://vincentgarreau.com/particles.js/
A lightweight JavaScript library for creating particles
13. mo.js
https://mojs.github.io/
The motion graphics toolbelt for the web
14. Lightbox2
https://lokeshdhakar.com/projects/lightbox2/
A small JS library to overlay images on top of the current page.
15. Slick
https://kenwheeler.github.io/slick/
Fully responsive carousel
16. Barba.js
https://barba.js.org/
Create fluid and smooth transitions between your website’s pages.
17. Locomotive Scroll  
https://locomotivemtl.github.io/locomotive-scroll/
A simple scroll library that provides detection of elements in viewport & smooth scrolling with parallax.
18. Owl Carousel
https://owlcarousel2.github.io/OwlCarousel2/
Free responsive jQuery carousel
19. SwiperJS
https://swiperjs.com/
Free, Open Source, Modern Slider without jQuery. Available for Vanilla JS and all modern frameworks like React, Vue, Angular etc.
20. Splide
https://splidejs.com/
Free, pure JS library for carousels and sliders
21. Simple Parallax
https://simpleparallax.com/
The easiest way to get a parallax effect with javascript
23. Granim.js
https://sarcadass.github.io/granim.js/index.html
Create fluid and interactive gradient animations with this small javascript library.
24. Popmotion
https://popmotion.io/
Simple animation libraries for delightful user interfaces.
25. Vivus
https://maxwellito.github.io/vivus/
Vivus is a lightweight JavaScript class (with no dependencies) that allows you to animate SVGs, giving them the appearence of being drawn.
26. Typed.js
https://mattboldt.com/demos/typed-js/
A JavaScript Typing Animation Library.
27. Progress Bar JS
https://kimmobrunfeldt.github.io/progressbar.js/
Responsive and slick progress bars with animated SVG paths.
28. AnimeJS
https://animejs.com/
Lightweight JavaScript animation library with a simple, yet powerful API.
29. AniJS
https://anijs.github.io/
A Library to Raise your Web Design without Coding
30. Remotion
https://www.remotion.dev/
This is not an animation library per se but you can use this to make videos by writing Javascript code.
The types of JavaScript animation libraries
#1 – Three.js
https://stackdiary.com/javascript-animation-libraries/#three-js
#2 – Anime.js
https://stackdiary.com/javascript-animation-libraries/#anime-js

	https://www.youtube.com/watch?v=uRDLFXxihgc
To get started using Anime.js, download the library Anime.js website. Include the Anime.js JavaScript file in your HTML code.
<script src="path/to/anime.min.js"></script>
We can also use the Node Package Manager (npm). If you use npm, the script location will be node_modules/animejs/lib/anime.min.js
$ npm install animejs --save
Another alternative is to use the latest release of the library hosted on a CDN.
See the code below.
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.1/anime.min.js"></script>
Getting started with Anime.js
We use the anime() function to create the animations. The anime() function takes an object as an argument. The object holds the animation details. You can refresh your knowledge on Javascript Objects.
let animation = anime({
  /* animation details here*/
});
or
anime({
  /* animation details here */
});

In the animation details, we need to define targets, properties, property parameters, and animation parameters.
Target: This refers to the element to be animated. It can be any CSS selector, DOM Node, NodeList, JavaScript Object, or an array containing multiple targets. Examples are div, .classSelector, and #idSelector. Target tell anime how to find the elements on the web page.
Properties: This refers to the CSS Properties that can be animated: CSS Transforms, Object Properties, Dom Attributes, and SVG Attributes. They include translate, rotate, scale, skew, opacity, color, among others.
Property parameters: duration, delay, endDelay, easing, round, etc.
Animation Parameters: These are Direction, Loop, and Autoplay. Refer to Anime.js Documentation for more details.
https://animejs.com/documentation/#direction
In the next section, we will implement the above.
Follow the comments in the code.
Simple animations with Anime.js
Shapes animation
In this example, we’ll create a triangular shape inside a div identified by #triangle1. You require basic CSS knowledge to achieve this.
Javascript code:
<script type="text/javascript">
    //Create Anime object
    anime({
      //target
      targets: "#triangle1",
      //Properties
      rotateY: 360,
      scale: 0.5,
      translateX: 300,
      skew: 60,
      // Property Parameters
      duration: 1000,
      endDelay: 300,
      easing: "easeInOutSine",
      // Animation Parameters
      direction: 'alternate',
        loop: true,
    });
  </script>

Explanation In the JavaScript code example above the target is #triangle1. Four transformations are applied to the target all at once. The resulting animation is shown in the output.
rotateY: 360: Rotates the target along the Y-axis for 360°
scale: 0.5: Scales the target by a factor of 0.5.
translateX: 300: Moves the target 300 pixels along the X-axis.
skew: 60: Skews the target 60°.

#3 – Popmotion  - 
https://popmotion.io/#quick-start-animation
https://github.com/Popmotion/popmotion

#4 – mo.js  https://stackdiary.com/javascript-animation-libraries/#mo-js
#5 – p5.js  https://stackdiary.com/javascript-animation-libraries/#p5-js
#6 – Motion  https://stackdiary.com/javascript-animation-libraries/#framer-motion
#7 – GSAP  https://stackdiary.com/javascript-animation-libraries/#GSAP
#8 – Paper.js  https://stackdiary.com/javascript-animation-libraries/#paper-js
#9 – Web Animations  https://stackdiary.com/javascript-animation-libraries/#web-animations-api
#10 – Proton  https://stackdiary.com/javascript-animation-libraries/#proton


