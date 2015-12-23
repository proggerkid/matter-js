# Matter.js

> *Matter.js* is a JavaScript 2D rigid body physics engine for the web

[brm.io/matter-js](http://brm.io/matter-js)

[Demos](#demos) - [Gallery](#gallery) - [Features](#features) - [Install](#install) - [Usage](#usage) - [Examples](#examples) -  [Docs](#documentation) - [References](#references) - [License](#license)

[![Build Status](https://travis-ci.org/liabru/matter-js.png?branch=master)](https://travis-ci.org/liabru/matter-js)

### Demos

<table>
  <tr>
    <td>
      <ul>
        <li><a href="http://brm.io/matter-js-demo-master#mixed">Mixed Shapes</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#mixedSolid">Solid Shapes</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#svg">Concave SVG Paths</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#terrain">Concave Terrain</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#concave">Concave Bodies</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#compound">Compound Bodies</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#newtonsCradle">Newton's Cradle</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#wreckingBall">Wrecking Ball</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#slingshot">Slingshot Game</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#rounded">Rounded Corners</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#views">Views</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#timescale">Time Scaling</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#manipulation">Body Manipulation</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#compositeManipulation">Composite Manipulation</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#raycasting">Raycasting</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#sprites">Sprites</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#pyramid">Pyramid</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#car">Car</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#catapult">Catapult</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#gravity">Reverse Gravity</a></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="http://brm.io/matter-js-demo-master#bridge">Bridge</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#avalanche">Avalanche</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#softBody">Basic Soft Bodies</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#cloth">Cloth</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#events">Events</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#collisionFiltering">Collision Filtering</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#chains">Chains</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#ballPool">Ball Pool</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#stack">Stack</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#circleStack">Circle Stack</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#compoundStack">Compound Stack</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#restitution">Restitution</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#friction">Friction</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#airFriction">Air Friction</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#staticFriction">Static Friction</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#sleeping">Sleeping</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#broadphase">Grid Broadphase</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#beachBalls">Beach Balls</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#stress">Stress 1</a></li>
        <li><a href="http://brm.io/matter-js-demo-master#stress2">Stress 2</a></li>
      </ul>
      <br>
    </td>
  </tr>
</table>

### Gallery

Some great projects using matter.js physics are

- [Les métamorphoses de Mr. Kalia](http://www.lab212.org/projects/les-metamorphoses-de-mr-kalia) by Lab212 for Google
- [Pablo The Flamingo](http://pablotheflamingo.com/) by Nathan Gordon et al
- [#GIFMYLIVE](http://bonhommeparis.com/en/projects/arte-gifmylive) by Bonnehomme for Arte
- [Adobe Analytics Live Stream](http://adobefirehose.mediarain.com/) by Rain for Adobe
- [Blood Sweat & Tools Interactive](http://bloodsweatandtools.discovery.ca/gamebench/) by Jam3 for Discovery
- [Hype](http://tumult.com/hype/pro/) by Tumult
- [Trophy Smasher](http://grindselect.com/trophy/game) by Kyle Stetz for Grind Select
- [Pelada](https://gabrielmfadt.wordpress.com/tag/matter-js/) by Gabriel Gianordoli
- [Labyrinth Game](https://vine.co/v/OjYTwi1gdB1) by Jaume Sanchez Elias
- [Powermate and Physics](https://vine.co/v/OjXaEzivvJe) by Jaume Sanchez Elias

### Features

- Rigid bodies
- Compound bodies
- Composite bodies
- Concave and convex hulls
- Physical properties (mass, area, density etc.)
- Restitution (elastic and inelastic collisions)
- Collisions (broad-phase, mid-phase and narrow-phase)
- Stable stacking and resting
- Conservation of momentum
- Friction and resistance
- Events
- Constraints
- Gravity
- Sleeping and static bodies
- Rounded corners (chamfering)
- Views (translate, zoom)
- Collision queries (raycasting, region tests)
- Time scaling (slow-mo, speed-up)
- Canvas renderer (supports vectors and textures)
- WebGL renderer (requires [pixi.js](https://github.com/GoodBoyDigital/pixi.js/))
- [MatterTools](https://github.com/liabru/matter-tools) for creating, testing and debugging worlds
- World state serialisation (requires [resurrect.js](https://github.com/skeeto/resurrect-js))
- Cross-browser (Chrome, Firefox, Safari, IE8+)
- Mobile-compatible (touch, responsive)
- An original JavaScript physics implementation (not a port)

### Install

Download the [edge build (master)](https://github.com/liabru/matter-js/blob/master/build/matter.js) or get a [stable release](https://github.com/liabru/matter-js/releases) and include the script in your web page:

    <script src="matter.js" type="text/javascript"></script>

You can also install using the package managers [Bower](http://bower.io/search/?q=matter-js) and [NPM](https://www.npmjs.org/package/matter-js).

    bower install matter-js
    npm install matter-js

### Usage

Visit the [Getting started](https://github.com/liabru/matter-js/wiki/Getting-started) wiki page for a minimal usage example.  
Also see the [Rendering](https://github.com/liabru/matter-js/wiki/Rendering) wiki page, which also shows how to use your own game loop.

### Examples

See the [examples](https://github.com/liabru/matter-js/tree/master/examples) directory which contains the source for all [demos](#demos).  
There are even more examples on [codepen](http://codepen.io/collection/Fuagy/).

### Documentation

Edge build documentation is at [Matter.js API Docs (master)](http://brm.io/matter-js-docs-master/)  
Stable release documentation is at [Matter.js API Docs (v0.8.0)](http://brm.io/matter-js-docs/)

### Building and Contributing

To build you must first install [node.js](http://nodejs.org/) and [gulp](http://gulpjs.com/), then run

	npm install

This will install the required build dependencies, then run

	gulp dev

which is a task that builds the `matter-dev.js` file, spawns a `connect` and `watch` server, then opens `demo/dev.html` in your browser. Any changes you make to the source will automatically rebuild `matter-dev.js` and reload your browser for quick and easy testing.

Contributions are welcome, please ensure they follow the same style and architecture as the rest of the code. You should run `gulp test` to ensure `jshint` gives no errors. Please do not include any changes to the files in the `build` directory. 

If you'd like to contribute but not sure what to work on, feel free to message me. Thanks!

### Changelog

To see what's new or changed in the latest version, see the [changelog](https://github.com/liabru/matter-js/blob/master/CHANGELOG.md).

### References

The engine uses the following techniques:

- Time-corrected position Verlet integrator
- Adaptive grid broad-phase detection
- AABB mid-phase detection
- SAT narrow-phase detection
- Iterative sequential impulse solver and position solver
- Resting collisions with resting constraints ala Erin Catto's method
    (GDC08)
- Temporal coherence impulse caching and warming
- Collision pairs, contacts and impulses maintained with a pair
    manager
- Approximate Coulomb friction model using friction constraints
- Constraints solved with the Gauss-Siedel method
- Semi-variable time step, synced with rendering
-   A basic sleeping strategy
- HTML5 Canvas / WebGL renderer

For more information see my post on [Game physics for beginners](http://brm.io/game-physics-for-beginners/).

### License

Matter.js is licensed under [The MIT License (MIT)](http://opensource.org/licenses/MIT)  
Copyright (c) 2014 Liam Brummitt

This license is also supplied with the release and source code.  
As stated in the license, absolutely no warranty is provided.
