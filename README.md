## Awesome Cycle.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome Cycle.js tools, resources, videos and shiny things.

- [Learn](#learn)
  - [Documentation](#documentation)
  - [Tutorials](#tutorials)
  - [Videos](#videos)
  - [Slides](#slides)
  - [Example Applications](#example-applications)
- [Libraries](#libraries)
  - [Drivers](#drivers)
  - [Boilerplates](#boilerplates)
  - [Testing](#testing)
  - [Debugging](#debugging)
  - [Components](#components)
- [Community](#community)

---
## Learn

### Documentation

* [cycle.js.org](http://cycle.js.org/) - Cycle.js official tutorial and documentation.

### Tutorials

### Videos

* [What if the user was a function?](https://www.youtube.com/watch?v=1zj7M1LnJV4) - Presentation at JSConf BP2015 by [Andre Staltz](https://twitter.com/andrestaltz)
* [Cycle.js and functional reactive user interfaces](https://www.youtube.com/watch?v=uNZnftSksYg) - Presentation at ReactiveConf 2015 by [Andre Staltz](http://twitter.com/andrestaltz)
* [Intro to Functional Reactive Programming with Cycle.js](https://www.youtube.com/watch?v=6_ETUyh0tns) - Presentation by [Nick Johnstone](https://twitter.com/widdnz)
* [Cycle.js Fundamentals](https://egghead.io/series/cycle-js-fundamentals) - Playlist at [egghead.io](https://egghead.io)

### Slides

* [Cycle.js an honestly reactive framework for web user interfaces](http://slides.com/erykpiast/cycle) - by Eryk Napierała
* [Intro to Cycle.js](http://www.slideshare.net/aryelukashevski/cyclejs-introduction) - by Arye Lukashevki

### Example Applications

* [**cyclejs/cycle-examples ★141**](https://github.com/cyclejs/examples) - Official collection of small Cycle.js examples
* [Widdershin/tricycle ★19](https://github.com/Widdershin/tricycle) - Scratchpad for trying out Cycle.js, relies on Ace Editor with Cycle
* [cgeorg/todomvp ★17](https://github.com/cgeorg/todomvp) - Minimum Viable Pizza, an example webapp written in Cycle.js
* [erykpiast/cyclejs-examples ★7](https://github.com/erykpiast/cyclejs-examples) - Example web applications built with Cycle.js.
* [grozen/trends-cycle ★3](https://github.com/grozen/trends-cycle) - Slack trend searching written in Cycle.js
* [ivan-kleshnin/cyclejs-examples ★86](https://github.com/ivan-kleshnin/cyclejs-examples) - Collection of CycleJS examples, ES6.
* [ivan-kleshnin/tetris-cyclejs ★7](https://github.com/ivan-kleshnin/tetris-game) - Tetris game implemented in CycleJS, ES6
* [phadej/graafi ★13](https://github.com/phadej/graafi) - Cycle.js experiment with SVG and global undo/redo
http://oleg.fi/graafi/
* [**staltz/rxmarbles ★1,022**](https://github.com/staltz/rxmarbles) - Interactive diagrams of Rx Observables http://rxmarbles.com/
* [MarcCloud/magic-cart ★6](https://github.com/MarcCloud/magic-cart) - Simple shopping cart of a magic creatures store.
* [foxdonut/cycle-todolist ★9](https://github.com/foxdonut/cycle-todolist) - demonstrates a simple Cycle.js TODO list app with CRUD.
* [collardeau/kairos ★13](https://github.com/collardeau/kairos) - Source code for [Kairos](http://my-kairos.herokuapp.com/), a weather app built in Cycle.js.
* [**Mercateo/component-check ★417**](https://github.com/Mercateo/component-check) - Common patterns for building Cycle.js components
* [edge/electron-cycle-media ★23](https://github.com/edge/electron-cycle-media) - Media player written with Cycle.js and Electron.
* [kibin/cycle-example-who-to-follow ★16](https://github.com/kibin/cycle-example-who-to-follow) - Small example partly implements twitter’s who to follow box using github api.
* [SkaterDad/cycle-snabbdom-examples ★4](https://github.com/SkaterDad/cycle-snabbdom-examples) - Examples of nested components, using snabbdom-specific animations.
* [bahmutov/draw-cycle ★81](https://github.com/bahmutov/draw-cycle) - Interactive visualization of counter application showing the data flow inside a MVI component [glebbahmutov.com/draw-cycle](https://glebbahmutov.com/draw-cycle/)

## Libraries

### Drivers

* [tylors/cycle-director ★15](https://github.com/TylorS/cycle-director) - Router driver using Director.
* [cyclejs/cycle-http-driver ★51](https://github.com/cyclejs/http) - A Cycle.js Driver for making HTTP requests, based on superagent.
* [cyclejs/cycle-storage-driver ★20](https://github.com/cyclejs/cycle-storage-driver) - A Cycle.js Driver for using localStorage and sessionStorage.
* [cyclejs/cycle-notification-driver ★15](https://github.com/cyclejs/cycle-notification-driver) - A Cycle.js Driver for showing and responding to HTML5 Notifications.
* [axefrog/cycle-router5 ★28](https://github.com/axefrog/cycle-router5) - A router driver using Router5
* [cgeorg/cycle-socket.io ★15](https://github.com/cgeorg/cycle-socket.io) - A Cycle driver for Socket.IO clients
* [**cyclejs/cycle-dom ★141**](https://github.com/cyclejs/dom) - The standard DOM Driver for Cycle.js based on virtual-dom, and other helpers
* [secobarbital/cycle-fetch-driver ★1](https://github.com/secobarbital/cycle-fetch-driver) - A Cycle.js Driver for making HTTP requests, using the Fetch API.
* [r7kamura/cycle-fetcher-driver ★12](https://github.com/r7kamura/cycle-fetcher-driver) - A Cycle.js Driver for making HTTP requests using [stackable-fetcher](https://github.com/r7kamura/stackable-fetcher).
* [cyclejs/cycle-history ★58](https://github.com/cyclejs/history) - The standard Cycle driver for dealing with the [History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API)
* [benji6/cycle-audio-graph ★9](https://github.com/benji6/cycle-audio-graph) - A Cycle.js Driver for manipulating the Web Audio API using [virtual-audio-graph](https://github.com/benji6/virtual-audio-graph)
* [CyclicMaterials/cycle-hammer-driver ★10](https://github.com/CyclicMaterials/cycle-hammer-driver) - A Cycle.js driver to wrap Hammer.js and detect touch gestures
* [jessaustin/cycle-sse-driver ★4](https://github.com/jessaustin/cycle-sse-driver) - Source driver for Server-Sent Events/EventSource.
* [tylors/cycle-snabbdom ★41](https://github.com/TylorS/cycle-snabbdom) - DOM driver using Snabbdom
* [TylorS/cycle-router ★31](https://github.com/TylorS/cycle-router) - Router driver designed for Cycle.js
* [TylorS/cyclic-router ★34](https://github.com/TylorS/cyclic-router) - Router Driver built for Cycle.js
* [Widdershin/cycle-animation-driver ★22](https://github.com/Widdershin/cycle-animation-driver) - Cycle driver for requestAnimationFrame
* [dralletje/cycle-firebase ★15](https://github.com/dralletje/cycle-firebase) - A Cycle.js Driver for Firebase
* [edge/cycle-blessed ★26](https://github.com/edge/cycle-blessed) - A Cycle.js Driver for terminal applications
* [10clouds/cyclejs-cookie ★0](https://github.com/10clouds/cyclejs-cookie) - Cookies Driver for Cycle.js 

### Utilities

* [staltz/chai-virtual-dom ★22](https://github.com/staltz/chai-virtual-dom) - Chai assertion helpers to test virtual-dom VTrees
* [cgeorg/sinject ★10](https://github.com/cgeorg/sinject) - a dependency injection tool supporting Cycle's circular dependencies
* [erykpiast/cyclejs-group ★19](https://github.com/erykpiast/cyclejs-group) - Utility for CycleJS framework for reducing boilerplate when creating groups of streams.
* [erykpiast/cyclejs-stream ★25](https://github.com/cyclejs/rx-injectable-observable) - Observable (events stream) to which you can inject another streams.
* [erykpiast/cyclejs-wc ★0](https://github.com/erykpiast/cyclejs-wc) - Utility for creating Web Components based on Cycle.js
* [**ohanhi/hyperscript-helpers ★237**](https://github.com/ohanhi/hyperscript-helpers) - elm-html inspired helpers for writing hyperscript or virtual-hyperscript.
* [**pH200/cycle-react ★234**](https://github.com/pH200/cycle-react) - use React instead of virtual-dom with a Cycle-like API
* [madcapjake/earlhyperscript ★2](https://github.com/MadcapJake/earl-hyperscript) - A helper function and macro for using Earl Grey's [document-building syntax](https://breuleux.github.io/earl-grey/doc.html#documentbuildingsyntax) with Cycle.js.

### Boilerplates

* [andreloureiro/cyclejs-starter ★27](https://github.com/andreloureiro/cyclejs-starter) - Cycle.js starter template with ES6 and Livereload.
* [Frikki/generator-cyclejs ★1](https://github.com/Frikki/generator-cyclejs) - Scaffold out a Cycle.js Nested Dialogue module using Yeoman.
* [adicirstei/cycle-bp ★4](https://github.com/adicirstei/cycle-bp) - Boilerplate template for building Cycle.js apps
* [edge/cyc ★82](https://github.com/edge/cyc) - Scaffold an isomorphic Cycle.js app in seconds.
* [cmdv/cycle-webpack-boilerplate ★63](https://github.com/Cmdv/cycle-webpack-boilerplate) - Cycle app with routing, state handling and tests.
* [Widdershin/cycle-hot-reloading-example ★25](https://github.com/Widdershin/cycle-hot-reloading-example) - A Cycle.js starter project with hot reloading using browserify-hmr

### Testing

* [erykpiast/cyclejs-mock ★16](https://github.com/erykpiast/cyclejs-mock) - Utility for testing applications based on CycleJS framework.

### Debugging

* [**cyclejs/cycle-time-travel ★138**](https://github.com/cyclejs/cycle-time-travel) - A time travelling debugger for Cycle.js apps. Displays a stream visualizer that you can drag to go back in time. Try it online [here](http://cycle.js.org/cycle-time-travel/).

### Components

* [erykpiast/autocompleted-select ★9](https://github.com/erykpiast/autocompleted-select) - Select Web Component with autocompletion. Based on RxJS and VirtualDOM.
* [enten/cyclejs-calendar ★6](https://github.com/enten/cyclejs-calendar) - Calendar component for Cycle.js. Try it online [here](http://enten.github.io/cyclejs-calendar/example).
* [mciparelli/cyclejs-gravatar ★0](https://github.com/mciparelli/cyclejs-gravatar) - Cycle.js component for rendering a gravatar profile image.

## Community

* [Gitter chat](https://gitter.im/cyclejs/cycle-core) - Ask 'how do I ...?'


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
