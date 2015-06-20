<!--
    Copyright 2014 The Gfx-rs Developers.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->
<p align="center">
  <img src="info/logo.png">
</p>
<p align="center">
  <a href="https://travis-ci.org/gfx-rs/gfx-rs">
      <img src="https://img.shields.io/travis/gfx-rs/gfx/master.svg?style=flat-square" alt="Build Status">
  </a>
  <a href="https://crates.io/crates/gfx">
      <img src="http://meritbadge.herokuapp.com/gfx?style=flat-square" alt="crates.io">
  </a>
  <img src="https://img.shields.io/badge/GITTER-join%20chat-green.svg?style=flat-square" alt="Gitter Chat">
  <br>
  <strong><a href="http://rust-ci.org/gfx-rs/gfx-rs/doc/gfx/index.html">Documentation</a> | <a href="http://gfx-rs.github.io/">Blog</a> </strong>
</p>

## gfx-rs
`gfx` is a high-performance, bindless graphics API for the Rust programming language. It aims to be the default API for Rust graphics: for one-off applications, or higher level libraries or engines.

## Motivation

- Graphics APIs are mostly designed with C and C++ in mind, and hence are dangerous and error prone, with little static safety guarantees.
- Providing type safe wrappers around platform-specific APIs is feasible, but only pushes the problem of platform independence to a higher level of abstraction, often to the game or rendering engine.
- Modern graphics APIs, whilst providing a great degree of flexibility and a high level of performance, often have a much higher barrier to entry than traditional [fixed-function](http://en.wikipedia.org/wiki/Fixed-function) APIs.
- Graphics APIs like OpenGL still [require the developer to 'bind' and 'unbind' objects](http://www.arcsynthesis.org/gltut/Basics/Intro%20What%20is%20OpenGL.html#d0e887) in order to perform operations on them. This results in a large amount of boiler plate code, and brings with it the usual problems associated with global state.

## Getting started

Add the following to your `Cargo.toml`:

~~~toml
[dependencies]
gfx = "*"
~~~

See the [triangle example](https://github.com/gfx-rs/gfx_examples/tree/master/src/triangle) for a typical context
initialization with [glfw](https://github.com/bjz/glfw-rs/), or
[glutin example](https://github.com/gfx-rs/gfx_examples/tree/master/src/glutin) for [glutin](https://github.com/tomaka/glutin/).

links to stuff here!

## Who's using it?

People are!
![](https://raw.githubusercontent.com/csherratt/snowmew/master/.screenshot.jpg)

## Note

gfx is still in the early stages of development. Help is most appreciated.

If you are interested in helping out, you can contact the developers on [Gitter](https://gitter.im/gfx-rs/gfx). See [contrib.md](info/contrib.md) for contact information and contribution guidelines.
