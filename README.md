## Awesome Cycle.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome Cycle.js tools, resources, videos and shiny things.

- [Learn](#learn)
  - [Documentation](#documentation)
  - [Tutorials](#tutorials)
  - [Tutorial video series](#tutorial-video-series)
  - [Videos](#videos)
    - [2017](#2017)
    - [2016](#2017)
    - [2015](#2015)
  - [Cycle conf](#cycle-conf)
  - [Slides](#slides)
  - [Try Cycle online](#try-cycle-online)
  - [Built with Cycle](#built-with-cycle)
  - [Example collections](#example-collections)
  - [Sample apps](#sample-apps)
- [Tools](#tools)
  - [CLI](#cli)
- [Libraries](#libraries)
  - [Drivers](#drivers)
  - [Boilerplates](#boilerplates)
  - [Testing](#testing)
  - [Debugging](#debugging)
  - [Components](#components)
- [Community](#community)

---

## Help!?

* Ask on [Gitter chat](https://gitter.im/cyclejs/cycle-core)

## Learn

### Documentation

* [cycle.js.org](http://cycle.js.org/) - Cycle.js official tutorial and documentation.

### Tutorials

* [What Developers Need to Know about MVI (Model-View-Intent)](http://thenewstack.io/developers-need-know-mvi-model-view-intent/) - Post on MVI architecture.
* [Cycle.js: a reactive framework](https://lucamezzalira.com/2016/05/23/cycle-js-a-reactive-framework/) - Introduction to Cycle.js with real time data example.
* [Building realtime applications with CycleJS and RxJS](https://blog.pusher.com/building-realtime-applications-with-cyclejs-and-rxjs/) - Learn how to build realtime applications with CycleJS and RxJS

#### Tutorial video series

* [Cycle.js Fundamentals](https://egghead.io/series/cycle-js-fundamentals) - Playlist at [egghead.io](https://egghead.io) (mar 2016)

### Videos

#### 2017

* [Introduction to Cycle.js](https://www.youtube.com/watch?v=UEqRzty0Cas) by [Marius Kazlauskas](https://twitter.com/ugibugivugi) at [Vilnius.js](https://www.meetup.com/Vilnius-js) (feb 2017) [slides](https://mariuskazlauskas.github.io/talks/cyclejs/intro#/)

#### 2016

* [User Interfaces as Pure Functions of Time](https://www.youtube.com/watch?v=9BG0Y3C6WqM) - Lightning talk by [Thomas Belin](http://twitter.com/atomrc) at [dotjs 2016](http://dotjs.io/) (dec 2016)
* [See the data flowing through your app ](https://www.youtube.com/watch?v=R-GzJgEccEQ) by [Andre Staltz](https://twitter.com/andrestaltz) at [Full stack fest 2016](https://2016.fullstackfest.com/) (sep 2016)
* [Reactive Programming with Cycle.js](https://vimeo.com/175121069) - by Luca Mezzalira at [JSDay 2016](http://2016.jsday.it/) (jun 2016)
* [Unidirectional data flow architectures](https://vimeo.com/168652278) - Presentation AtTheFrontend Conference (may 2016) by [Andre Staltz](https://twitter.com/andrestaltz)
(http://twitter.com/andrestaltz)
* [Learning how to ride: an introduction to Cycle.js](https://youtu.be/31URmaeNHSs) - by Fernando Macias Pereznieto at [JS Monthly London](http://www.meetup.com/js-monthly-london/) (may 2016)
* [Cycle.js was built to solve problems](https://www.youtube.com/watch?v=Rj8ZTRVka4E) - by Andre Staltz at [Frontend.fi](http://frontend.fi/) (mar 2016)

#### 2015

* [What if the user was a function?](https://www.youtube.com/watch?v=1zj7M1LnJV4) - Presentation at JSConf BP2015 (june 2015) by [Andre Staltz](https://twitter.com/andrestaltz)
* [Cycle.js and functional reactive user interfaces](https://www.youtube.com/watch?v=uNZnftSksYg) - Presentation at ReactiveConf 2015 (nov 2015) by [Andre Staltz]
* [Intro to Functional Reactive Programming with Cycle.js](https://www.youtube.com/watch?v=6_ETUyh0tns) - Presentation by [Nick Johnstone] (jul 2015) (https://twitter.com/widdnz)

### Cycle Conf

#### Cycle Conf 2016: Copenhagen

[Cycle conf](http://cycleconf.com/)

* [Back to the Future, Hot reloading with Cycle.js](https://www.youtube.com/watch?v=rbrnyC5fXMM) - by Nick Johnstone at [CycleConf 2016](http://cycleconf.com/) (apr 2016)
* [From MVC to FRP](https://www.youtube.com/watch?v=-PCq4pXaDZw) - by Gleb Bahmutov at [CycleConf 2016](http://cycleconf.com/) (apr 2016)
* [Cycle.js on the bash side](https://www.youtube.com/watch?v=Rx5N99TQ52g) - by Hadrien de Cuzey at [CycleConf 2016](http://cycleconf.com/) (apr 2016)
* [Brains as Building Blocks](https://www.youtube.com/watch?v=1ToJ7cxb1R8) - by Andre Staltz at [CycleConf 2016](http://cycleconf.com/) (apr 2016)

### Slides

* [Cycle.js an honestly reactive framework for web user interfaces](http://slides.com/erykpiast/cycle) - by Eryk Napierała
* [Intro to Cycle.js](http://www.slideshare.net/aryelukashevski/cyclejs-introduction) - by Arye Lukashevki
* [Reactive Programming with Cycle.js](http://www.slideshare.net/flashplatform/reactive-programming-with-cyclejs) - by Luca Mezzalira
* [Cycle.js - building apps with streams only] (http://lmatteis.github.io/cyclejs-slides/keynote/index.html) - by Luca Matteis
* [Functional Reactive Programming with Cycle.js](https://slides.com/artfuldev/frp-with-cycle-js) - by Sudarsan Balaji

### Try Cycle online

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[tricycle](https://github.com/Widdershin/tricycle)|[![Dependency Status](https://david-dm.org/Widdershin/tricycle.svg)](https://david-dm.org/Widdershin/tricycle)|[![devDependency Status](https://david-dm.org/Widdershin/tricycle/dev-status.svg)](https://david-dm.org/Widdershin/tricycle?info=devDependencies)|Scratchpad for trying out Cycle.js, relies on Ace Editor with Cycle|![Stars](https://img.shields.io/github/stars/Widdershin/tricycle.svg?label=Stars&style=social)|

### Built with Cycle

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[built-with-cycle](https://github.com/cyclejs-community/built-with-cycle)|[![Dependency Status](https://david-dm.org/cyclejs-community/built-with-cycle.svg)](https://david-dm.org/cyclejs-community/built-with-cycle)|[![devDependency Status](https://david-dm.org/cyclejs-community/built-with-cycle/dev-status.svg)](https://david-dm.org/cyclejs-community/built-with-cycle?info=devDependencies)|[A website](http://cyclejs-community.github.io/built-with-cycle) to showcase the cool projects built with Cycle.js|![Stars](https://img.shields.io/github/stars/cyclejs-community/built-with-cycle.svg?label=Stars&style=social)|

### Example collections

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-examples](https://github.com/cyclejs/examples)|[![Dependency Status](https://david-dm.org/cyclejs/examples.svg)](https://david-dm.org/cyclejs/examples)|[![devDependency Status](https://david-dm.org/cyclejs/examples/dev-status.svg)](https://david-dm.org/cyclejs/examples?info=devDependencies)|Official collection of small Cycle.js examples|![Stars](https://img.shields.io/github/stars/cyclejs/examples.svg?label=Stars&style=social)|
|[cyclejs-examples](https://github.com/erykpiast/cyclejs-examples)|[![Dependency Status](https://david-dm.org/erykpiast/cyclejs-examples.svg)](https://david-dm.org/erykpiast/cyclejs-examples)|[![devDependency Status](https://david-dm.org/erykpiast/cyclejs-examples/dev-status.svg)](https://david-dm.org/erykpiast/cyclejs-examples?info=devDependencies)|Example web applications built with Cycle.js.|![Stars](https://img.shields.io/github/stars/erykpiast/cyclejs-examples.svg?label=Stars&style=social)|
|[cyclejs-examples](https://github.com/ivan-kleshnin/cyclejs-examples)|[![Dependency Status](https://david-dm.org/ivan-kleshnin/cyclejs-examples.svg)](https://david-dm.org/ivan-kleshnin/cyclejs-examples)|[![devDependency Status](https://david-dm.org/ivan-kleshnin/cyclejs-examples/dev-status.svg)](https://david-dm.org/ivan-kleshnin/cyclejs-examples?info=devDependencies)|Collection of CycleJS examples, ES6.|![Stars](https://img.shields.io/github/stars/ivan-kleshnin/cyclejs-examples.svg?label=Stars&style=social)|
|[cycle-snabbdom-examples](https://github.com/SkaterDad/cycle-snabbdom-examples)|[![Dependency Status](https://david-dm.org/SkaterDad/cycle-snabbdom-examples.svg)](https://david-dm.org/SkaterDad/cycle-snabbdom-examples)|[![devDependency Status](https://david-dm.org/SkaterDad/cycle-snabbdom-examples/dev-status.svg)](https://david-dm.org/SkaterDad/cycle-snabbdom-examples?info=devDependencies)|Examples of nested components, using snabbdom-specific animations.|![Stars](https://img.shields.io/github/stars/SkaterDad/cycle-snabbdom-examples.svg?label=Stars&style=social)|

### Sample Apps

#### Todo Lists

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[todomvp](https://github.com/cgeorg/todomvp)|[![Dependency Status](https://david-dm.org/cgeorg/todomvp.svg)](https://david-dm.org/cgeorg/todomvp)|[![devDependency Status](https://david-dm.org/cgeorg/todomvp/dev-status.svg)](https://david-dm.org/cgeorg/todomvp?info=devDependencies)|Minimum Viable Pizza, an example webapp written in Cycle.js|![Stars](https://img.shields.io/github/stars/cgeorg/todomvp.svg?label=Stars&style=social)|
|[cycle-todolist](https://github.com/foxdonut/cycle-todolist)|[![Dependency Status](https://david-dm.org/foxdonut/cycle-todolist.svg)](https://david-dm.org/foxdonut/cycle-todolist)|[![devDependency Status](https://david-dm.org/foxdonut/cycle-todolist/dev-status.svg)](https://david-dm.org/foxdonut/cycle-todolist?info=devDependencies)|demonstrates a simple Cycle.js TODO list app with CRUD.|![Stars](https://img.shields.io/github/stars/foxdonut/cycle-todolist.svg?label=Stars&style=social)|

#### Misc

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[trends-cycle](https://github.com/grozen/trends-cycle)|[![Dependency Status](https://david-dm.org/grozen/trends-cycle.svg)](https://david-dm.org/grozen/trends-cycle)|[![devDependency Status](https://david-dm.org/grozen/trends-cycle/dev-status.svg)](https://david-dm.org/grozen/trends-cycle?info=devDependencies)|Slack trend searching written in Cycle.js|![Stars](https://img.shields.io/github/stars/grozen/trends-cycle.svg?label=Stars&style=social)|
|[rxmarbles](https://github.com/staltz/rxmarbles)|[![Dependency Status](https://david-dm.org/staltz/rxmarbles.svg)](https://david-dm.org/staltz/rxmarbles)|[![devDependency Status](https://david-dm.org/staltz/rxmarbles/dev-status.svg)](https://david-dm.org/staltz/rxmarbles?info=devDependencies)|Interactive diagrams of Rx Observables http://rxmarbles.com/ |![Stars](https://img.shields.io/github/stars/staltz/rxmarbles.svg?label=Stars&style=social)|
|[magic-cart](https://github.com/MarcCloud/magic-cart)|[![Dependency Status](https://david-dm.org/MarcCloud/magic-cart.svg)](https://david-dm.org/MarcCloud/magic-cart)|[![devDependency Status](https://david-dm.org/MarcCloud/magic-cart/dev-status.svg)](https://david-dm.org/MarcCloud/magic-cart?info=devDependencies)|Simple shopping cart of a magic creatures store.|![Stars](https://img.shields.io/github/stars/MarcCloud/magic-cart.svg?label=Stars&style=social)|
|[component-check](https://github.com/Mercateo/component-check)|[![Dependency Status](https://david-dm.org/Mercateo/component-check.svg)](https://david-dm.org/Mercateo/component-check)|[![devDependency Status](https://david-dm.org/Mercateo/component-check/dev-status.svg)](https://david-dm.org/Mercateo/component-check?info=devDependencies)|Common patterns for building Cycle.js components|![Stars](https://img.shields.io/github/stars/Mercateo/component-check.svg?label=Stars&style=social)|
|[cycle-example-who-to-follow](https://github.com/kibin/cycle-example-who-to-follow)|[![Dependency Status](https://david-dm.org/kibin/cycle-example-who-to-follow.svg)](https://david-dm.org/kibin/cycle-example-who-to-follow)|[![devDependency Status](https://david-dm.org/kibin/cycle-example-who-to-follow/dev-status.svg)](https://david-dm.org/kibin/cycle-example-who-to-follow?info=devDependencies)|Small example partly implements twitter’s who to follow box using github api.|![Stars](https://img.shields.io/github/stars/kibin/cycle-example-who-to-follow.svg?label=Stars&style=social)|
|[draw-cycle](https://github.com/bahmutov/draw-cycle)|[![Dependency Status](https://david-dm.org/bahmutov/draw-cycle.svg)](https://david-dm.org/bahmutov/draw-cycle)|[![devDependency Status](https://david-dm.org/bahmutov/draw-cycle/dev-status.svg)](https://david-dm.org/bahmutov/draw-cycle?info=devDependencies)|Interactive visualization of counter application showing the data flow inside a MVI component [glebbahmutov.com/draw-cycle](https://glebbahmutov.com/draw-cycle/) |![Stars](https://img.shields.io/github/stars/bahmutov/draw-cycle.svg?label=Stars&style=social)|
|[pomocycle](https://github.com/andreloureiro/pomocycle)|[![Dependency Status](https://david-dm.org/andreloureiro/pomocycle.svg)](https://david-dm.org/andreloureiro/pomocycle)|[![devDependency Status](https://david-dm.org/andreloureiro/pomocycle/dev-status.svg)](https://david-dm.org/andreloureiro/pomocycle?info=devDependencies)|A simple Pomodoro timer.|![Stars](https://img.shields.io/github/stars/andreloureiro/pomocycle.svg?label=Stars&style=social)|
|[jsday-cycle-js](https://github.com/lucamezzalira/jsday-cycle-js)|[![Dependency Status](https://david-dm.org/lucamezzalira/jsday-cycle-js.svg)](https://david-dm.org/lucamezzalira/jsday-cycle-js)|[![devDependency Status](https://david-dm.org/lucamezzalira/jsday-cycle-js/dev-status.svg)](https://david-dm.org/lucamezzalira/jsday-cycle-js?info=devDependencies)|Reactive Live London Tube trains status example built with Cycle.js.|![Stars](https://img.shields.io/github/stars/lucamezzalira/jsday-cycle-js.svg?label=Stars&style=social)|

#### Teaching tools

|[tams-tools](https://github.com/laszlokorte/tams-tools)|[![Dependency Status](https://david-dm.org/laszlokorte/tams-tools.svg)](https://david-dm.org/laszlokorte/tams-tools)|[![devDependency Status](https://david-dm.org/laszlokorte/tams-tools/dev-status.svg)](https://david-dm.org/laszlokorte/tams-tools?info=devDependencies)|A set of tools for teaching and learning computer science built with cycle.js.|![Stars](https://img.shields.io/github/stars/laszlokorte/tams-tools.svg?label=Stars&style=social)|

#### Games & Graphics

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[graafi](https://github.com/phadej/graafi)|[![Dependency Status](https://david-dm.org/phadej/graafi.svg)](https://david-dm.org/phadej/graafi)|[![devDependency Status](https://david-dm.org/phadej/graafi/dev-status.svg)](https://david-dm.org/phadej/graafi?info=devDependencies)|Cycle.js experiment with SVG and global undo/redo http://oleg.fi/graafi/ |![Stars](https://img.shields.io/github/stars/phadej/graafi.svg?label=Stars&style=social)|
|[cyclejs-fractals](https://github.com/wmaurer/cyclejs-fractals)|[![Dependency Status](https://david-dm.org/wmaurer/cyclejs-fractals.svg)](https://david-dm.org/wmaurer/cyclejs-fractals)|[![devDependency Status](https://david-dm.org/wmaurer/cyclejs-fractals/dev-status.svg)](https://david-dm.org/wmaurer/cyclejs-fractals?info=devDependencies)|Dancing pythagorean tree fractal : Animating 2048 SVG nodes.|![Stars](https://img.shields.io/github/stars/wmaurer/cyclejs-fractals.svg?label=Stars&style=social)|
|[tetris-cyclejs](https://github.com/ivan-kleshnin/tetris-game)|[![Dependency Status](https://david-dm.org/ivan-kleshnin/tetris-game.svg)](https://david-dm.org/ivan-kleshnin/tetris-game)|[![devDependency Status](https://david-dm.org/ivan-kleshnin/tetris-game/dev-status.svg)](https://david-dm.org/ivan-kleshnin/tetris-game?info=devDependencies)|Tetris game implemented in CycleJS, ES6|![Stars](https://img.shields.io/github/stars/ivan-kleshnin/tetris-game.svg?label=Stars&style=social)|
|[cyclejs-hangman](https://github.com/class-ideas/cyclejs-hangman)|[![Dependency Status](https://david-dm.org/class-ideas/cyclejs-hangman.svg)](https://david-dm.org/class-ideas/cyclejs-hangman)|[![devDependency Status](https://david-dm.org/class-ideas/cyclejs-hangman/dev-status.svg)](https://david-dm.org/class-ideas/cyclejs-hangman?info=devDependencies)|A hangman game built with Cycle.js|![Stars](https://img.shields.io/github/stars/class-ideas/cyclejs-hangman.svg?label=Stars&style=social)|

#### Desktop & Mobile apps

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[electron-cycle-media](https://github.com/edge/electron-cycle-media)|[![Dependency Status](https://david-dm.org/edge/electron-cycle-media.svg)](https://david-dm.org/edge/electron-cycle-media)|[![devDependency Status](https://david-dm.org/edge/electron-cycle-media/dev-status.svg)](https://david-dm.org/edge/electron-cycle-media?info=devDependencies)|Media player written with Cycle.js and Electron.|![Stars](https://img.shields.io/github/stars/edge/electron-cycle-media.svg?label=Stars&style=social)|

## Tools

### CLI

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[create-cycle-app](https://github.com/cyclejs-community/create-cycle-app)|[![Dependency Status](https://david-dm.org/cyclejs-community/create-cycle-app.svg)](https://david-dm.org/cyclejs-community/create-cycle-app)|[![devDependency Status](https://david-dm.org/cyclejs-community/create-cycle-app/dev-status.svg)](https://david-dm.org/cyclejs-community/create-cycle-app?info=devDependencies)|Create Cycle.js apps with no build configuration.|![Stars](https://img.shields.io/github/stars/cyclejs-community/create-cycle-app.svg?label=Stars&style=social)|

## Libraries

### Drivers

#### Virtual DOM
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-dom](https://github.com/cyclejs/dom)|[![Dependency Status](https://david-dm.org/cyclejs/dom.svg)](https://github.com/cyclejs/cyclejs/tree/master/dom)|[![devDependency Status](https://david-dm.org/cyclejs/dom/dev-status.svg)](https://david-dm.org/cyclejs/dom?info=devDependencies)|The standard DOM Driver for Cycle.js (core)|![Stars](https://img.shields.io/github/stars/cyclejs/dom.svg?label=Stars&style=social)|
|[cycle-snabbdom](https://github.com/TylorS/cycle-snabbdom)|[![Dependency Status](https://david-dm.org/TylorS/cycle-snabbdom.svg)](https://david-dm.org/TylorS/cycle-snabbdom)|[![devDependency Status](https://david-dm.org/TylorS/cycle-snabbdom/dev-status.svg)](https://david-dm.org/TylorS/cycle-snabbdom?info=devDependencies)|DOM driver using Snabbdom (jun 2016)|![Stars](https://img.shields.io/github/stars/TylorS/cycle-snabbdom.svg?label=Stars&style=social)|

#### Browser APIs
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-history](https://github.com/cyclejs/history)|[![Dependency Status](https://david-dm.org/cyclejs/history.svg)](https://github.com/cyclejs/cyclejs/tree/master/history)|[![devDependency Status](https://david-dm.org/cyclejs/history/dev-status.svg)](https://david-dm.org/cyclejs/history?info=devDependencies)|The standard Cycle driver for dealing with the [History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API) (sep 2016)|![Stars](https://img.shields.io/github/stars/cyclejs/history.svg?label=Stars&style=social)|
|[cyclejs-cookie](https://github.com/10clouds/cyclejs-cookie)|[![Dependency Status](https://david-dm.org/10clouds/cyclejs-cookie.svg)](https://david-dm.org/10clouds/cyclejs-cookie)|[![devDependency Status](https://david-dm.org/10clouds/cyclejs-cookie/dev-status.svg)](https://david-dm.org/10clouds/cyclejs-cookie?info=devDependencies)|Cookies Driver for Cycle.js (aug 2016)|![Stars](https://img.shields.io/github/stars/10clouds/cyclejs-cookie.svg?label=Stars&style=social)|

#### User Interaction (UX)
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-keys](https://github.com/raquelxmoss/cycle-keys)|[![Dependency Status](https://david-dm.org/raquelxmoss/cycle-keys.svg)](https://david-dm.org/raquelxmoss/cycle-keys)|[![devDependency Status](https://david-dm.org/raquelxmoss/cycle-keys/dev-status.svg)](https://david-dm.org/raquelxmoss/cycle-keys?info=devDependencies)|Driver for keyboard events (sep 2016)|![Stars](https://img.shields.io/github/stars/raquelxmoss/cycle-keys.svg?label=Stars&style=social)|
|[cycle-keyboard](https://github.com/cyclejs-community/cycle-keyboard)|[![Dependency Status](https://david-dm.org/cyclejs-community/cycle-keyboard.svg)](https://david-dm.org/cyclejs-community/cycle-keyboard)|[![devDependency Status](https://david-dm.org/cyclejs-community/cycle-keyboard/dev-status.svg)](https://david-dm.org/cyclejs-community/cycle-keyboard?info=devDependencies)|A keyboard driver for cycle.js (dec 2016)|![Stars](https://img.shields.io/github/stars/cyclejs-community/cycle-keyboard.svg?label=Stars&style=social)|
|[cycle-hammer-driver](https://github.com/CyclicMaterials/cycle-hammer-driver)|[![Dependency Status](https://david-dm.org/CyclicMaterials/cycle-hammer-driver.svg)](https://david-dm.org/CyclicMaterials/cycle-hammer-driver)|[![devDependency Status](https://david-dm.org/CyclicMaterials/cycle-hammer-driver/dev-status.svg)](https://david-dm.org/CyclicMaterials/cycle-hammer-driver?info=devDependencies)|A Cycle.js driver to wrap Hammer.js and detect touch gestures (nov 2015)|![Stars](https://img.shields.io/github/stars/CyclicMaterials/cycle-hammer-driver.svg?label=Stars&style=social)|
|[cycle-audio-graph](https://github.com/benji6/cycle-audio-graph)|[![Dependency Status](https://david-dm.org/benji6/cycle-audio-graph.svg)](https://david-dm.org/benji6/cycle-audio-graph)|[![devDependency Status](https://david-dm.org/benji6/cycle-audio-graph/dev-status.svg)](https://david-dm.org/benji6/cycle-audio-graph?info=devDependencies)|A Cycle.js Driver for manipulating the Web Audio API using (apr 2016)[virtual-audio-graph](https://github.com/benji6/virtual-audio-graph)|![Stars](https://img.shields.io/github/stars/benji6/cycle-audio-graph.svg?label=Stars&style=social)|

#### Animation/UI
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-animation-driver](https://github.com/Widdershin/cycle-animation-driver)|[![Dependency Status](https://david-dm.org/Widdershin/cycle-animation-driver.svg)](https://david-dm.org/Widdershin/cycle-animation-driver)|[![devDependency Status](https://david-dm.org/Widdershin/cycle-animation-driver/dev-status.svg)](https://david-dm.org/Widdershin/cycle-animation-driver?info=devDependencies)|Cycle driver for requestAnimationFrame (oct 2016)|![Stars](https://img.shields.io/github/stars/Widdershin/cycle-animation-driver.svg?label=Stars&style=social)|

#### Routers

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclic-router](https://github.com/cyclejs-community/cyclic-router)|[![Dependency Status](https://david-dm.org/cyclejs-community/cyclic-router.svg)](https://david-dm.org/cyclejs-community/cyclic-router)|[![devDependency Status](https://david-dm.org/cyclejs-community/cyclic-router/dev-status.svg)](https://david-dm.org/cyclejs-community/cyclic-router?info=devDependencies)|Router Driver built for Cycle.js (apr 2016)|![Stars](https://img.shields.io/github/stars/cyclejs-community/cyclic-router.svg?label=Stars&style=social)|
|[cycle-page](https://github.com/garrydzeng/cycle-page)|[![Dependency Status](https://david-dm.org/garrydzeng/cycle-page.svg)](https://david-dm.org/garrydzeng/cycle-page)|[![devDependency Status](https://david-dm.org/garrydzeng/cycle-page/dev-status.svg)](https://david-dm.org/garrydzeng/cycle-page?info=devDependencies)|A tiny client-side router for Cycle.js (fresh)|![Stars](https://img.shields.io/github/stars/garrydzeng/cycle-page.svg?label=Stars&style=social)|
|[cycle-router5](https://github.com/axefrog/cycle-router5)|[![Dependency Status](https://david-dm.org/axefrog/cycle-router5.svg)](https://david-dm.org/axefrog/cycle-router5)|[![devDependency Status](https://david-dm.org/axefrog/cycle-router5/dev-status.svg)](https://david-dm.org/axefrog/cycle-router5?info=devDependencies)|A router driver using Router5 (sep 2015)|![Stars](https://img.shields.io/github/stars/axefrog/cycle-router5.svg?label=Stars&style=social)|

#### Storage

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-storage](https://github.com/cyclejs/storage)       |[![Dependency Status](https://david-dm.org/cyclejs/storage.svg)](https://david-dm.org/cyclejs/storage)|[![devDependency Status](https://david-dm.org/cyclejs/storage/dev-status.svg)](https://david-dm.org/cyclejs/storage?info=devDependencies)|A Cycle.js Driver for using localStorage and sessionStorage. (fresh)|![Stars](https://img.shields.io/github/stars/cyclejs/storage.svg?label=Stars&style=social)|
|[cyclejs-animated-localstorage](https://github.com/rkrupinski/cyclejs-animated-localstorage)|[![Dependency Status](https://david-dm.org/rkrupinski/cyclejs-animated-localstorage.svg)](https://david-dm.org/rkrupinski/cyclejs-animated-localstorage)|[![devDependency Status](https://david-dm.org/rkrupinski/cyclejs-animated-localstorage/dev-status.svg)](https://david-dm.org/rkrupinski/cyclejs-animated-localstorage?info=devDependencies)|A Cycle.js driver for animating (srsly) localStorage. (jun 2016)|![Stars](https://img.shields.io/github/stars/rkrupinski/cyclejs-animated-localstorage.svg?label=Stars&style=social)|
|[cycle-gun](https://github.com/JuniperChicago/cycle-gun)|[![Dependency Status](https://david-dm.org/JuniperChicago/cycle-gun.svg)](https://david-dm.org/JuniperChicago/cycle-gun)|[![devDependency Status](https://david-dm.org/JuniperChicago/cycle-gun/dev-status.svg)](https://david-dm.org/JuniperChicago/cycle-gun?info=devDependencies)|A basic Cycle.js driver wrapping a gun.js instance allowing graph storage and p2p sync. (fresh)|![Stars](https://img.shields.io/github/stars/uniperChicago/cycle-gun.svg?label=Stars&style=social)|
|[cycle-deepstream](https://github.com/EnigmaCurry/cycle-deepstream)|[![Dependency Status](https://david-dm.org/EnigmaCurry/cycle-deepstream.svg)](https://david-dm.org/EnigmaCurry/cycle-deepstream)|[![devDependency Status](https://david-dm.org/EnigmaCurry/cycle-deepstream/dev-status.svg)](https://david-dm.org/EnigmaCurry/cycle-deepstream?info=devDependencies)|A Cycle.js driver for [deepstream.io](https://deepstream.io) (fresh)|![Stars](https://img.shields.io/github/stars/EnigmaCurry/cycle-deepstream.svg?label=Stars&style=social)|
|[cycle-firebase](https://github.com/dralletje/cycle-firebase)|[![Dependency Status](https://david-dm.org/dralletje/cycle-firebase.svg)](https://david-dm.org/dralletje/cycle-firebase)|[![devDependency Status](https://david-dm.org/dralletje/cycle-firebase/dev-status.svg)](https://david-dm.org/dralletje/cycle-firebase?info=devDependencies)|A Cycle.js Driver for Firebase (mar 2016)|![Stars](https://img.shields.io/github/stars/dralletje/cycle-firebase.svg?label=Stars&style=social)|
[cycle-graphql-driver](https://github.com/fiatjaf/cycle-graphql-driver)|[![Dependency Status](https://david-dm.org/fiatjaf/cycle-graphql-driver.svg)](https://david-dm.org/fiatjaf/cycle-graphql-driver)|[![devDependency Status](https://david-dm.org/fiatjaf/cycle-graphql-driver/dev-status.svg)](https://david-dm.org/fiatjaf/cycle-graphql-driver?info=devDependencies)|A Cycle.js Driver for GraphQL using most.js (dec 2016)|![Stars](https://img.shields.io/github/stars/fiatjaf/cycle-graphql-driver.svg?label=Stars&style=social)|

#### Communication/protocols

Drivers to work with external communication protocols (HTTP, Sockets etc.)

##### Sync (Request/Response) protocols

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-fetch-driver](https://github.com/secobarbital/cycle-fetch-driver)|[![Dependency Status](https://david-dm.org/secobarbital/cycle-fetch-driver.svg)](https://david-dm.org/secobarbital/cycle-fetch-driver)|[![devDependency Status](https://david-dm.org/secobarbital/cycle-fetch-driver/dev-status.svg)](https://david-dm.org/secobarbital/cycle-fetch-driver?info=devDependencies)|A Cycle.js Driver for making HTTP requests, using the Fetch API. (oct 2015)|![Stars](https://img.shields.io/github/stars/secobarbital/cycle-fetch-driver.svg?label=Stars&style=social)|
|[cycle-fetcher-driver](https://github.com/r7kamura/cycle-fetcher-driver)|[![Dependency Status](https://david-dm.org/r7kamura/cycle-fetcher-driver.svg)](https://david-dm.org/r7kamura/cycle-fetcher-driver)|[![devDependency Status](https://david-dm.org/r7kamura/cycle-fetcher-driver/dev-status.svg)](https://david-dm.org/r7kamura/cycle-fetcher-driver?info=devDependencies)|A Cycle.js Driver for making HTTP requests using (oct 2015)[stackable-fetcher](https://github.com/r7kamura/stackable-fetcher).|![Stars](https://img.shields.io/github/stars/r7kamura/cycle-fetcher-driver.svg?label=Stars&style=social)|

##### Async protocols
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-socket.io](https://github.com/cgeorg/cycle-socket.io)|[![Dependency Status](https://david-dm.org/cgeorg/cycle-socket.io.svg)](https://david-dm.org/cgeorg/cycle-socket.io)|[![devDependency Status](https://david-dm.org/cgeorg/cycle-socket.io/dev-status.svg)](https://david-dm.org/cgeorg/cycle-socket.io?info=devDependencies)|A Cycle driver for Socket.IO clients (oct 2016)|![Stars](https://img.shields.io/github/stars/cgeorg/cycle-socket.io.svg?label=Stars&style=social)|
|[cycle-socketcluster](https://github.com/jbowden1982/cycle-socketcluster)|[![Dependency Status](https://david-dm.org/jbowden1982/cycle-socketcluster.svg)](https://david-dm.org/jbowden1982/cycle-socketcluster)|[![devDependency Status](https://david-dm.org/jbowden1982/cycle-socketcluster/dev-status.svg)](https://david-dm.org/jbowden1982/cycle-socketcluster?info=devDependencies)|A socketcluster driver for Cycle.js (fresh)|![Stars](https://img.shields.io/github/stars/jbowden1982/cycle-socketcluster.svg?label=Stars&style=social)|
|[cycle-async-driver](https://github.com/whitecolor/cycle-async-driver)|[![Dependency Status](https://david-dm.org/whitecolor/cycle-async-driver.svg)](https://david-dm.org/whitecolor/cycle-async-driver)|[![devDependency Status](https://david-dm.org/whitecolor/cycle-async-driver/dev-status.svg)](https://david-dm.org/whitecolor/cycle-async-driver?info=devDependencies)|Factory for creating async request/response cycle.js drivers (aug 2016)|![Stars](https://img.shields.io/github/stars/whitecolor/cycle-async-driver.svg?label=Stars&style=social)|

##### Push notifications

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-notification-driver](https://github.com/cyclejs/cycle-notification-driver)|[![Dependency Status](https://david-dm.org/cyclejs/cycle-notification-driver.svg)](https://david-dm.org/cyclejs/cycle-notification-driver)|[![devDependency Status](https://david-dm.org/cyclejs/cycle-notification-driver/dev-status.svg)](https://david-dm.org/cyclejs/cycle-notification-driver?info=devDependencies)|A Cycle.js Driver for showing and responding to HTML5 Notifications. (mar 2016)|![Stars](https://img.shields.io/github/stars/cyclejs/cycle-notification-driver.svg?label=Stars&style=social)|
|[cycle-sse-driver](https://github.com/jessaustin/cycle-sse-driver)|[![Dependency Status](https://david-dm.org/jessaustin/cycle-sse-driver.svg)](https://david-dm.org/jessaustin/cycle-sse-driver)|[![devDependency Status](https://david-dm.org/jessaustin/cycle-sse-driver/dev-status.svg)](https://david-dm.org/jessaustin/cycle-sse-driver?info=devDependencies)|Source driver for Server-Sent Events/EventSource. (jan 2016)|![Stars](https://img.shields.io/github/stars/jessaustin/cycle-sse-driver.svg?label=Stars&style=social)|


#### Runtime Environments

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-electron-driver](https://github.com/apoco/cycle-electron-driver)|[![Dependency Status](https://david-dm.org/apoco/cycle-electron-driver.svg)](https://david-dm.org/apoco/cycle-electron-driver)|[![devDependency Status](https://david-dm.org/apoco/cycle-electron-driver/dev-status.svg)](https://david-dm.org/apoco/cycle-electron-driver?info=devDependencies)|Driver to interact with Electron interface from Cycle.js application (mar 2016)|![Stars](https://img.shields.io/github/stars/apoco/cycle-electron-driver.svg?label=Stars&style=social)|
|[cycle-blessed](https://github.com/edge/cycle-blessed)|[![Dependency Status](https://david-dm.org/edge/cycle-blessed.svg)](https://david-dm.org/edge/cycle-blessed)|[![devDependency Status](https://david-dm.org/edge/cycle-blessed/dev-status.svg)](https://david-dm.org/edge/cycle-blessed?info=devDependencies)|A Cycle.js Driver for terminal applications (may 2016)|![Stars](https://img.shields.io/github/stars/edge/cycle-blessed.svg?label=Stars&style=social)|

#### Web Frameworks
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[redux-cycles](https://github.com/cyclejs-community/redux-cycles)|[![Dependency Status](https://david-dm.org/cyclejs-community/redux-cycles.svg)](https://david-dm.org/cyclejs-community/redux-cycles)|[![devDependency Status](https://david-dm.org/cyclejs-community/redux-cycles/dev-status.svg)](https://david-dm.org/cyclejs-community/redux-cycles?info=devDependencies)|A Redux middleware that allows you to handle actions lifecycle with Cycle.js (fresh)|![Stars](https://img.shields.io/github/stars/cyclejs-community/redux-cycles.svg?label=Stars&style=social)|

#### Operating System (OS)
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[recyclec](https://github.com/rektide/recyclec)|[![Dependency Status](https://david-dm.org/rektide/recyclec.svg)](https://david-dm.org/rektide/recyclec)|[![devDependency Status](https://david-dm.org/rektide/recyclec/dev-status.svg)](https://david-dm.org/rektide/recyclec?info=devDependencies)|Readline driver (feb 2016)|![Stars](https://img.shields.io/github/stars/rektide/recyclec.svg?label=Stars&style=social)|

#### Bots
| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-telegram](https://github.com/goodmind/cycle-telegram)|[![Dependency Status](https://david-dm.org/goodmind/cycle-telegram.svg)](https://david-dm.org/goodmind/cycle-telegram)|[![devDependency Status](https://david-dm.org/goodmind/cycle-telegram/dev-status.svg)](https://david-dm.org/goodmind/cycle-telegram?info=devDependencies)|A Cycle.js Driver for Telegram Bot API (nov 2016)|![Stars](https://img.shields.io/github/stars/goodmind/cycle-telegram.svg?label=Stars&style=social)|

### Utilities

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[sinject](https://github.com/cgeorg/sinject)|[![Dependency Status](https://david-dm.org/cgeorg/sinject.svg)](https://david-dm.org/cgeorg/sinject)|[![devDependency Status](https://david-dm.org/cgeorg/sinject/dev-status.svg)](https://david-dm.org/cgeorg/sinject?info=devDependencies)|a dependency injection tool supporting Cycle's circular dependencies (jun 2015) |![Stars](https://img.shields.io/github/stars/cgeorg/sinject.svg?label=Stars&style=social)|
|[cyclejs-group](https://github.com/erykpiast/cyclejs-group)|[![Dependency Status](https://david-dm.org/erykpiast/cyclejs-group.svg)](https://david-dm.org/erykpiast/cyclejs-group)|[![devDependency Status](https://david-dm.org/erykpiast/cyclejs-group/dev-status.svg)](https://david-dm.org/erykpiast/cyclejs-group?info=devDependencies)|Utility for CycleJS framework for reducing boilerplate when creating groups of streams (jul 2015) |![Stars](https://img.shields.io/github/stars/erykpiast/cyclejs-group.svg?label=Stars&style=social)|

#### UI/UX

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclejs-sortable](https://github.com/cyclejs-community/cyclejs-sortable)|[![Dependency Status](https://david-dm.org/cyclejs-community/cyclejs-sortable.svg)](https://david-dm.org/cyclejs-community/cyclejs-sortable)|[![devDependency Status](https://david-dm.org/cyclejs-community/cyclejs-sortable/dev-status.svg)](https://david-dm.org/cyclejs-community/cyclejs-sortable?info=devDependencies)|Make everything sortable via drag and drop in only one line of code (mar 2017)|![Stars](https://img.shields.io/github/stars/cyclejs-community/cyclejs-sortable.svg?label=Stars&style=social)|

#### Web components

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclejs-wc](https://github.com/erykpiast/cyclejs-wc)|[![Dependency Status](https://david-dm.org/erykpiast/cyclejs-wc.svg)](https://david-dm.org/erykpiast/cyclejs-wc)|[![devDependency Status](https://david-dm.org/erykpiast/cyclejs-wc/dev-status.svg)](https://david-dm.org/erykpiast/cyclejs-wc?info=devDependencies)|Utility for creating Web Components based on Cycle.js (jul 2015)|![Stars](https://img.shields.io/github/stars/erykpiast/cyclejs-wc.svg?label=Stars&style=social)|
|[cycle-custom-elementify](https://github.com/staltz/cycle-custom-elementify)|[![Dependency Status](https://david-dm.org/staltz/cycle-custom-elementify/cycle-custom-elementify.svg)](https://david-dm.org/staltz/cycle-custom-elementify/cycle-custom-elementify)|[![devDependency Status](https://david-dm.org/staltz/cycle-custom-elementify/dev-status.svg)](https://david-dm.org/staltz/cycle-custom-elementify/?info=devDependencies)|Utility for creating Custom Elements (v0/1) based on Cycle.js (sep 2016)|![Stars](https://img.shields.io/github/stars/staltz/cycle-custom-elementify.svg?label=Stars&style=social)|

#### Testing

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[chai-virtual-dom](https://github.com/staltz/chai-virtual-dom)|[![Dependency Status](https://david-dm.org/staltz/chai-virtual-dom.svg)](https://david-dm.org/staltz/chai-virtual-dom)|[![devDependency Status](https://david-dm.org/staltz/chai-virtual-dom/dev-status.svg)](https://david-dm.org/staltz/chai-virtual-dom?info=devDependencies)|Chai assertion helpers to test virtual-dom VTrees (sep 2015)|![Stars](https://img.shields.io/github/stars/staltz/chai-virtual-dom.svg?label=Stars&style=social)|

#### Hyperscript (render)

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-react](https://github.com/pH200/cycle-react)|[![Dependency Status](https://david-dm.org/pH200/cycle-react.svg)](https://david-dm.org/pH200/cycle-react)|[![devDependency Status](https://david-dm.org/pH200/cycle-react/dev-status.svg)](https://david-dm.org/pH200/cycle-react?info=devDependencies)|use React instead of virtual-dom with a Cycle-like API (dec 2015)|![Stars](https://img.shields.io/github/stars/pH200/cycle-react.svg?label=Stars&style=social)|
|[earlhyperscript](https://github.com/MadcapJake/earl-hyperscript)|[![Dependency Status](https://david-dm.org/MadcapJake/earl-hyperscript.svg)](https://david-dm.org/MadcapJake/earl-hyperscript)|[![devDependency Status](https://david-dm.org/MadcapJake/earl-hyperscript/dev-status.svg)](https://david-dm.org/MadcapJake/earl-hyperscript?info=devDependencies)|A helper function and macro for using Earl Grey's [document-building syntax](https://breuleux.github.io/earl-grey/doc.html#documentbuildingsyntax) with Cycle.js (jul 2015)|![Stars](https://img.shields.io/github/stars/MadcapJake/earl-hyperscript.svg?label=Stars&style=social)|
|[hyperscript-helpers](https://github.com/ohanhi/hyperscript-helpers)|[![Dependency Status](https://david-dm.org/ohanhi/hyperscript-helpers.svg)](https://david-dm.org/ohanhi/hyperscript-helpers)|[![devDependency Status](https://david-dm.org/ohanhi/hyperscript-helpers/dev-status.svg)](https://david-dm.org/ohanhi/hyperscript-helpers?info=devDependencies)|elm-html inspired helpers for writing hyperscript or virtual-hyperscript (nov 2016)|![Stars](https://img.shields.io/github/stars/ohanhi/hyperscript-helpers.svg?label=Stars&style=social)|

#### Authentication

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclejs-auth0](https://github.com/atomrc/cyclejs-auth0)|[![Dependency Status](https://david-dm.org/atomrc/cyclejs-auth0.svg)](https://david-dm.org/atomrc/cyclejs-auth0)|[![devDependency Status](https://david-dm.org/atomrc/cyclejs-auth0/dev-status.svg)](https://david-dm.org/atomrc/cyclejs-auth0?info=devDependencies)|Everything you need to start playing with Auth0 on your Cyclejs app (Driver + component) (feb 2017)|![Stars](https://img.shields.io/github/stars/atomrc/cyclejs-auth0.svg?label=Stars&style=social)|

#### Higher level abstractions

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-gear](https://github.com/WorldMaker/cycle-gear)|[![Dependency Status](https://david-dm.org/WorldMaker/cycle-gear.svg)](https://david-dm.org/WorldMaker/cycle-gear)|[![devDependency Status](https://david-dm.org/WorldMaker/cycle-gear/dev-status.svg)](https://david-dm.org/WorldMaker/cycle-gear?info=devDependencies)|A main function factory for Cycle based upon a formalization of Cycle's MVI pattern (jan 2017)|![Stars](https://img.shields.io/github/stars/WorldMaker/cycle-gear.svg?label=Stars&style=social)|

### Boilerplates

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[generator-cyclejs](https://github.com/Frikki/generator-cyclejs)|[![Dependency Status](https://david-dm.org/Frikki/generator-cyclejs.svg)](https://david-dm.org/Frikki/generator-cyclejs)|[![devDependency Status](https://david-dm.org/Frikki/generator-cyclejs/dev-status.svg)](https://david-dm.org/Frikki/generator-cyclejs?info=devDependencies)|Scaffold out a Cycle.js Nested Dialogue module using Yeoman (sep 2015)|![Stars](https://img.shields.io/github/stars/Frikki/generator-cyclejs.svg?label=Stars&style=social)|
|[cycle-bp](https://github.com/adicirstei/cycle-bp)|[![Dependency Status](https://david-dm.org/adicirstei/cycle-bp.svg)](https://david-dm.org/adicirstei/cycle-bp)|[![devDependency Status](https://david-dm.org/adicirstei/cycle-bp/dev-status.svg)](https://david-dm.org/adicirstei/cycle-bp?info=devDependencies)|Boilerplate template for building Cycle.js apps (oct 2015)|![Stars](https://img.shields.io/github/stars/adicirstei/cycle-bp.svg?label=Stars&style=social)|
|[cyc](https://github.com/edge/cyc)|[![Dependency Status](https://david-dm.org/edge/cyc.svg)](https://david-dm.org/edge/cyc)|[![devDependency Status](https://david-dm.org/edge/cyc/dev-status.svg)](https://david-dm.org/edge/cyc?info=devDependencies)|Scaffold an isomorphic Cycle.js app in seconds (oct 2016)|![Stars](https://img.shields.io/github/stars/edge/cyc.svg?label=Stars&style=social)|
|[cycle-webpack-boilerplate](https://github.com/Cmdv/cycle-webpack-boilerplate)|[![Dependency Status](https://david-dm.org/Cmdv/cycle-webpack-boilerplate.svg)](https://david-dm.org/Cmdv/cycle-webpack-boilerplate)|[![devDependency Status](https://david-dm.org/Cmdv/cycle-webpack-boilerplate/dev-status.svg)](https://david-dm.org/Cmdv/cycle-webpack-boilerplate?info=devDependencies)|Cycle app with routing, state handling and tests (dec 2017)|![Stars](https://img.shields.io/github/stars/Cmdv/cycle-webpack-boilerplate.svg?label=Stars&style=social)|

#### Hot/live reload

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclejs-starter](https://github.com/andreloureiro/cyclejs-starter)|[![Dependency Status](https://david-dm.org/andreloureiro/cyclejs-starter.svg)](https://david-dm.org/andreloureiro/cyclejs-starter)|[![devDependency Status](https://david-dm.org/andreloureiro/cyclejs-starter/dev-status.svg)](https://david-dm.org/andreloureiro/cyclejs-starter?info=devDependencies)|Cycle.js starter template with ES6 and Livereload (jan 2017)|![Stars](https://img.shields.io/github/stars/andreloureiro/cyclejs-starter.svg?label=Stars&style=social)|
|[cycle-hot-reloading-example](https://github.com/Widdershin/cycle-hot-reloading-example)|[![Dependency Status](https://david-dm.org/Widdershin/cycle-hot-reloading-example.svg)](https://david-dm.org/Widdershin/cycle-hot-reloading-example)|[![devDependency Status](https://david-dm.org/Widdershin/cycle-hot-reloading-example/dev-status.svg)](https://david-dm.org/Widdershin/cycle-hot-reloading-example?info=devDependencies)|A Cycle.js starter project with hot reloading using browserify-hmr (mar 2016)|![Stars](https://img.shields.io/github/stars/Widdershin/cycle-hot-reloading-example.svg?label=Stars&style=social)|
|[cycle-hmr-example](https://github.com/mciparelli/cycle-hmr-example)|[![Dependency Status](https://david-dm.org/mciparelli/cycle-hmr-example.svg)](https://david-dm.org/mciparelli/cycle-hmr-example)|[![devDependency Status](https://david-dm.org/mciparelli/cycle-hmr-example/dev-status.svg)](https://david-dm.org/mciparelli/cycle-hmr-example?info=devDependencies)|A Cycle.js starter project using browserify and cycle-hmr (mar 2016)|![Stars](https://img.shields.io/github/stars/mciparelli/cycle-hmr-example.svg?label=Stars&style=social)|

#### with Web Server

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[hapi-cycle](https://github.com/wyqydsyq/hapi-cycle)|[![Dependency Status](https://david-dm.org/wyqydsyq/hapi-cycle.svg)](https://david-dm.org/wyqydsyq/hapi-cycle)|[![devDependency Status](https://david-dm.org/wyqydsyq/hapi-cycle/dev-status.svg)](https://david-dm.org/wyqydsyq/hapi-cycle?info=devDependencies)|A boilerplate isomorphic Cycle app running on a Hapi server with a simple CRUD skeleton to get you started (oct 2016)|![Stars](https://img.shields.io/github/stars/wyqydsyq/hapi-cycle.svg?label=Stars&style=social)|


#### TypeScript

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[typescript-starter-cycle](https://github.com/cyclejs-community/typescript-starter-cycle)|[![Dependency Status](https://david-dm.org/cyclejs-community/typescript-starter-cycle.svg)](https://david-dm.org/cyclejs-community/typescript-starter-cycle)|[![devDependency Status](https://david-dm.org/cyclejs-community/typescript-starter-cycle/dev-status.svg)](https://david-dm.org/cyclejs-community/typescript-starter-cycle?info=devDependencies)|A simple project for getting started with TypeScript in cycle.js, using Webpack. Has settings for Visual Studio Code as candy (oct 2016)|![Stars](https://img.shields.io/github/stars/cyclejs-community/typescript-starter-cycle.svg?label=Stars&style=social)|

### Testing

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cyclejs-mock](https://github.com/erykpiast/cyclejs-mock)|[![Dependency Status](https://david-dm.org/erykpiast/cyclejs-mock.svg)](https://david-dm.org/erykpiast/cyclejs-mock)|[![devDependency Status](https://david-dm.org/erykpiast/cyclejs-mock/dev-status.svg)](https://david-dm.org/erykpiast/cyclejs-mock?info=devDependencies)|Utility for testing applications based on CycleJS framework.|![Stars](https://img.shields.io/github/stars/erykpiast/cyclejs-mock.svg?label=Stars&style=social)|

### Debugging

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-time-travel](https://github.com/cyclejs/cycle-time-travel)|[![Dependency Status](https://david-dm.org/cyclejs/cycle-time-travel.svg)](https://david-dm.org/cyclejs/cycle-time-travel)|[![devDependency Status](https://david-dm.org/cyclejs/cycle-time-travel/dev-status.svg)](https://david-dm.org/cyclejs/cycle-time-travel?info=devDependencies)|A time travelling debugger for Cycle.js apps. Displays a stream visualizer that you can drag to go back in time. Try it online [here](http://cycle.js.org/cycle-time-travel/).|![Stars](https://img.shields.io/github/stars/cyclejs/cycle-time-travel.svg?label=Stars&style=social)|

### Components

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[autocompleted-select](https://github.com/erykpiast/autocompleted-select)|[![Dependency Status](https://david-dm.org/erykpiast/autocompleted-select.svg)](https://david-dm.org/erykpiast/autocompleted-select)|[![devDependency Status](https://david-dm.org/erykpiast/autocompleted-select/dev-status.svg)](https://david-dm.org/erykpiast/autocompleted-select?info=devDependencies)|Select Web Component with autocompletion. Based on RxJS and VirtualDOM.|![Stars](https://img.shields.io/github/stars/erykpiast/autocompleted-select.svg?label=Stars&style=social)|
|[cyclejs-calendar](https://github.com/enten/cyclejs-calendar)|[![Dependency Status](https://david-dm.org/enten/cyclejs-calendar.svg)](https://david-dm.org/enten/cyclejs-calendar)|[![devDependency Status](https://david-dm.org/enten/cyclejs-calendar/dev-status.svg)](https://david-dm.org/enten/cyclejs-calendar?info=devDependencies)|Calendar component for Cycle.js. Try it online [here](http://enten.github.io/cyclejs-calendar/example).|![Stars](https://img.shields.io/github/stars/enten/cyclejs-calendar.svg?label=Stars&style=social)|
|[cyclejs-gravatar](https://github.com/mciparelli/cyclejs-gravatar)|[![Dependency Status](https://david-dm.org/mciparelli/cyclejs-gravatar.svg)](https://david-dm.org/mciparelli/cyclejs-gravatar)|[![devDependency Status](https://david-dm.org/mciparelli/cyclejs-gravatar/dev-status.svg)](https://david-dm.org/mciparelli/cyclejs-gravatar?info=devDependencies)|Cycle.js component for rendering a gravatar profile image.|![Stars](https://img.shields.io/github/stars/mciparelli/cyclejs-gravatar.svg?label=Stars&style=social)|
|[cyclejs-ace-editor](https://github.com/tommy-the-runner/cyclejs-ace-editor)|[![Dependency Status](https://david-dm.org/tommy-the-runner/cyclejs-ace-editor.svg)](https://david-dm.org/tommy-the-runner/cyclejs-ace-editor)|[![devDependency Status](https://david-dm.org/tommy-the-runner/cyclejs-ace-editor/dev-status.svg)](https://david-dm.org/tommy-the-runner/cyclejs-ace-editor?info=devDependencies)|Cycle.js intergration with Ace Editor using [brace](https://github.com/thlorenz/brace). Check an example [here](https://tommy-the-runner.github.io/cyclejs-ace-editor/).|![Stars](https://img.shields.io/github/stars/tommy-the-runner/cyclejs-ace-editor.svg?label=Stars&style=social)|
|[cycle-color-picker](https://github.com/raquelxmoss/cycle-color-picker)|[![Dependency Status](https://david-dm.org/raquelxmoss/cycle-color-picker.svg)](https://david-dm.org/raquelxmoss/cycle-color-picker)|[![devDependency Status](https://david-dm.org/raquelxmoss/cycle-color-picker/dev-status.svg)](https://david-dm.org/raquelxmoss/cycle-color-picker?info=devDependencies)|A Color Picker component for Cycle.js. [Check out the example](https://raquelxmoss.github.io/cycle-color-picker).|![Stars](https://img.shields.io/github/stars/raquelxmoss/cycle-color-picker.svg?label=Stars&style=social)|

#### Graphics

| Name | Dependencies  | DevDependencies | Description | ★ |
|------|-------------- |-----------------|-------------|---|
|[cycle-svg-pan-and-zoom](https://github.com/cyclejs-community/cycle-svg-pan-and-zoom)|[![Dependency Status](https://david-dm.org/cyclejs-community/cycle-svg-pan-and-zoom.svg)](https://david-dm.org/cyclejs-community/cycle-svg-pan-and-zoom)|[![devDependency Status](https://david-dm.org/cyclejs-community/cycle-svg-pan-and-zoom/dev-status.svg)](https://david-dm.org/cyclejs-community/cycle-svg-pan-and-zoom?info=devDependencies)|A Google Maps style SVG pan and zoom component for Cycle.js|![Stars](https://img.shields.io/github/stars/cyclejs-community/cycle-svg-pan-and-zoom.svg?label=Stars&style=social)|

## Community

* [Gitter chat](https://gitter.im/cyclejs/cycle-core) - Ask 'how do I ...?'


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
