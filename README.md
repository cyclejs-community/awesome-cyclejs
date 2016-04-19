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

* [cyclejs/cycle-examples](https://github.com/cyclejs/cycle-examples) - Official collection of small Cycle.js examples
* [Widdershin/tricycle](https://github.com/Widdershin/tricycle) - Scratchpad for trying out Cycle.js, relies on Ace Editor with Cycle
* [cgeorg/todomvp](https://github.com/cgeorg/todomvp) - Minimum Viable Pizza, an example webapp written in Cycle.js
* [erykpiast/cyclejs-examples](https://github.com/erykpiast/cyclejs-examples) - Example web applications built with Cycle.js.
* [grozen/trends-cycle](https://github.com/grozen/trends-cycle) - Slack trend searching written in Cycle.js
* [ivan-kleshnin/cyclejs-examples](https://github.com/ivan-kleshnin/cyclejs-examples) - Collection of CycleJS examples, ES6.
* [ivan-kleshnin/tetris-cyclejs](https://github.com/ivan-kleshnin/tetris-cyclejs) - Tetris game implemented in CycleJS, ES6
* [phadej/graafi](https://github.com/phadej/graafi) - Cycle.js experiment with SVG and global undo/redo
http://oleg.fi/graafi/
* [staltz/rxmarbles](https://github.com/staltz/rxmarbles) - Interactive diagrams of Rx Observables http://rxmarbles.com/
* [MarcCloud/magic-cart](https://github.com/MarcCloud/magic-cart) - Simple shopping cart of a magic creatures store.
* [foxdonut/cycle-todolist](https://github.com/foxdonut/cycle-todolist) - demonstrates a simple Cycle.js TODO list app with CRUD.
* [collardeau/kairos](https://github.com/collardeau/kairos) - Source code for [Kairos](http://my-kairos.herokuapp.com/), a weather app built in Cycle.js.
* [Mercateo/component-check](https://github.com/Mercateo/component-check) - Common patterns for building Cycle.js components
* [edge/electron-cycle-media](https://github.com/edge/electron-cycle-media) - Media player written with Cycle.js and Electron.
* [kibin/cycle-example-who-to-follow](https://github.com/kibin/cycle-example-who-to-follow) - Small example partly implements twitter’s who to follow box using github api.
* [SkaterDad/cycle-snabbdom-examples](https://github.com/SkaterDad/cycle-snabbdom-examples) - Examples of nested components, using snabbdom-specific animations.
* [bahmutov/draw-cycle](https://github.com/bahmutov/draw-cycle) - Interactive visualization of counter application showing the data flow inside a MVI component [glebbahmutov.com/draw-cycle](https://glebbahmutov.com/draw-cycle/)

## Libraries

### Drivers

* [tylors/cycle-director](https://github.com/tylors/cycle-director) - Router driver using Director.
* [cyclejs/cycle-http-driver](https://github.com/cyclejs/cycle-http-driver) - A Cycle.js Driver for making HTTP requests, based on superagent.
* [cyclejs/cycle-storage-driver](https://github.com/cyclejs/cycle-storage-driver) - A Cycle.js Driver for using localStorage and sessionStorage.
* [cyclejs/cycle-notification-driver](https://github.com/cyclejs/cycle-notification-driver) - A Cycle.js Driver for showing and responding to HTML5 Notifications.
* [axefrog/cycle-router5](https://github.com/axefrog/cycle-router5) - A router driver using Router5
* [cgeorg/cycle-socket.io](https://github.com/cgeorg/cycle-socket.io) - A Cycle driver for Socket.IO clients
* [cyclejs/cycle-dom](https://github.com/cyclejs/cycle-dom) - The standard DOM Driver for Cycle.js based on virtual-dom, and other helpers
* [secobarbital/cycle-fetch-driver](https://github.com/secobarbital/cycle-fetch-driver) - A Cycle.js Driver for making HTTP requests, using the Fetch API.
* [r7kamura/cycle-fetcher-driver](https://github.com/r7kamura/cycle-fetcher-driver) - A Cycle.js Driver for making HTTP requests using [stackable-fetcher](https://github.com/r7kamura/stackable-fetcher).
* [cyclejs/cycle-history](https://github.com/cyclejs/cycle-history) - The standard Cycle driver for dealing with the [History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API)
* [benji6/cycle-audio-graph](https://github.com/benji6/cycle-audio-graph) - A Cycle.js Driver for manipulating the Web Audio API using [virtual-audio-graph](https://github.com/benji6/virtual-audio-graph)
* [CyclicMaterials/cycle-hammer-driver](https://github.com/CyclicMaterials/cycle-hammer-driver) - A Cycle.js driver to wrap Hammer.js and detect touch gestures
* [jessaustin/cycle-sse-driver](https://github.com/jessaustin/cycle-sse-driver) - Source driver for Server-Sent Events/EventSource.
* [tylors/cycle-snabbdom](https://github.com/TylorS/cycle-snabbdom) - DOM driver using Snabbdom
* [TylorS/cycle-router](https://github.com/TylorS/cycle-router) - Router driver designed for Cycle.js
* [TylorS/cyclic-router](https://github.com/TylorS/cyclic-router) - Router Driver built for Cycle.js
* [Widdershin/cycle-animation-driver](https://github.com/Widdershin/cycle-animation-driver) - Cycle driver for requestAnimationFrame
* [dralletje/cycle-firebase](https://github.com/dralletje/cycle-firebase) - A Cycle.js Driver for Firebase
* [edge/cycle-blessed](https://github.com/edge/cycle-blessed) - A Cycle.js Driver for terminal applications
* [10clouds/cyclejs-cookie](https://github.com/10clouds/cyclejs-cookie) - Cookies Driver for Cycle.js 

### Utilities

* [staltz/chai-virtual-dom](https://github.com/staltz/chai-virtual-dom) - Chai assertion helpers to test virtual-dom VTrees
* [cgeorg/sinject](https://github.com/cgeorg/sinject) - a dependency injection tool supporting Cycle's circular dependencies
* [erykpiast/cyclejs-group](https://github.com/erykpiast/cyclejs-group) - Utility for CycleJS framework for reducing boilerplate when creating groups of streams.
* [erykpiast/cyclejs-stream](https://github.com/cyclejs/rx-injectable-observable) - Observable (events stream) to which you can inject another streams.
* [erykpiast/cyclejs-wc](https://github.com/erykpiast/cyclejs-wc) - Utility for creating Web Components based on Cycle.js
* [ohanhi/hyperscript-helpers](https://github.com/ohanhi/hyperscript-helpers) - elm-html inspired helpers for writing hyperscript or virtual-hyperscript.
* [pH200/cycle-react](https://github.com/pH200/cycle-react) - use React instead of virtual-dom with a Cycle-like API
* [madcapjake/earlhyperscript](https://github.com/MadcapJake/earl-hyperscript) - A helper function and macro for using Earl Grey's [document-building syntax](https://breuleux.github.io/earl-grey/doc.html#documentbuildingsyntax) with Cycle.js.

### Boilerplates

* [andreloureiro/cyclejs-starter](https://github.com/andreloureiro/cyclejs-starter) - Cycle.js starter template with ES6 and Livereload.
* [Frikki/generator-cyclejs](https://github.com/Frikki/generator-cyclejs) - Scaffold out a Cycle.js Nested Dialogue module using Yeoman.
* [adicirstei/cycle-bp](https://github.com/adicirstei/cycle-bp) - Boilerplate template for building Cycle.js apps
* [edge/cyc](https://github.com/edge/cyc) - Scaffold an isomorphic Cycle.js app in seconds.
* [cmdv/cycle-webpack-boilerplate](https://github.com/Cmdv/cycle-webpack-boilerplate) - Cycle app with routing, state handling and tests.
* [Widdershin/cycle-hot-reloading-example](https://github.com/Widdershin/cycle-hot-reloading-example) - A Cycle.js starter project with hot reloading using browserify-hmr

### Testing

* [erykpiast/cyclejs-mock](https://github.com/erykpiast/cyclejs-mock) - Utility for testing applications based on CycleJS framework.

### Debugging

* [cyclejs/cycle-time-travel](https://github.com/cyclejs/cycle-time-travel) - A time travelling debugger for Cycle.js apps. Displays a stream visualizer that you can drag to go back in time. Try it online [here](http://cycle.js.org/cycle-time-travel/).

### Components

* [erykpiast/autocompleted-select](https://github.com/erykpiast/autocompleted-select) - Select Web Component with autocompletion. Based on RxJS and VirtualDOM.
* [enten/cyclejs-calendar](https://github.com/enten/cyclejs-calendar) - Calendar component for Cycle.js. Try it online [here](http://enten.github.io/cyclejs-calendar/example).
* [mciparelli/cyclejs-gravatar](https://github.com/mciparelli/cyclejs-gravatar) - Cycle.js component for rendering a gravatar profile image.

## Community

* [Gitter chat](https://gitter.im/cyclejs/cycle-core) - Ask 'how do I ...?'


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
