# AngularJS - Migrating to single-spa - Starter

This repository contains the starting code needed to follow along with the [AngularJS - Migrating to single-spa](https://single-spa.js.org/docs/migrating-angularJS-tutorial.html) tutorial found on the [single-spa](https://single-spa.js.org/) website.

This project was taken from [Douge Johnson's](https://github.com/dougjohnston) project, [Angular Drum Machine](https://github.com/dougjohnston/angular-drum-machine.git).


## Get Started

This project requires that you have [Grunt](https://gruntjs.com/getting-started), [Bower](https://bower.io/), and [Sass](https://sass-lang.com/) installed to get up and running.

```bash
npm install -g grunt-cli
npm install -g bower
npm install -g sass
```

With those dependencies installed, you can get started by typing the following command into your terminal:

```bash
git clone git@github.com:alocke12992/angularJS-migrating-to-single-spa-starter.git
cd angularJS-migrating-to-single-spa-starter
yarn
cd public/assets
bower install
```

Run `grunt` in the root directory to fire up a server at `http://localhost:8080`.

## Tutorial

You can find the tutorial, [AngularJS - Migrating to single-spa](https://single-spa.js.org/docs/migrating-angularJS-tutorial.html), on the [single-spa](https://single-spa.js.org/) website. You can find the completed [code for this tutorial here](https://github.com/alocke12992/angularJS-migrating-to-single-spa).

## Original README.md

Angular Drum Machine
--------------------

Just a little experiment with [AngularJS](https://github.com/angular/angular.js
"AngularJS") and HTML5 Audio (via [howler.js](https://github.com/goldfire/howler.js "howler.js")). Currently using Angular 1.2.

At one point, there were plans to upgrade this to later versions of Angular and even to port it to React. But, as this was only ever a fun proof-of-concept project, I never found time for those upgrades. I'll still review/accept any PRs if someone wants to take a crack at it.

DEMO: [http://drums.dojosto.com](http://drums.dojosto.com)

![Drum Machine Screenshot](https://raw.github.com/dougjohnston/angular-drum-machine/master/screenshot.png)

Installation
============

Run `npm install` to install Bower, Grunt and other local dependencies.
From `public/assets`, run `bower install` to install runtime dependencies.

Run `grunt` to fire up a server at http://localhost:8080.

Testing
=======

Run `grunt test` to fire up Karma and watch for changes.
