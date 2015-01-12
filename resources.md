---
layout: page
title: Resources
---

Very little we do is original, so here is a list of resources that helped us.

There are many more resources that can not all be mentioned here, but we want to thank everybody who has worked, commented or donated to these projects. Thank you.

### Luajit

This fantasic project is our closest ancestor, and without it, we would be nowhere near where we are today. Our architecture will be very similar, a (hopefully) fast interpreter combined with a single tracing JIT.

On a more detailed level, we also look at LuaJit, for example our [Bytecode](https://github.com/clojit/clojit-doc/blob/master/Bytecode%20Spec.md) is very much inspired by [LuaJit's Bytecode](http://wiki.luajit.org/Bytecode-2.0).

There is a lot left to devlope and a lot left to learn from LuaJit.

  - [LuaJIT 2.0 intellectual property disclosure and research opportunities](http://lua-users.org/lists/lua-l/2009-11/msg00089.html)
  - [The LuaJit Project](http://luajit.org/)
  - [The LuaJit Wiki](http://wiki.luajit.org/)

### wingolog

The blogger Andy Wingo has many posts on JIT compilers and other useful matter. We regularly consult this blog for overviews of the current state of the art in JIT compilers and the details of the Guile VM.

Here is a short list of useful links:

  - [value representation in javascript implementations](https://wingolog.org/archives/2011/05/18/value-representation-in-javascript-implementations)
  - [a register vm for guile](https://wingolog.org/archives/2013/11/26/a-register-vm-for-guile)
  - [wingolog.org](https://wingolog.org/)


### lambdachine

Thomas Schilling had a very similar idea to ours, look at LuaJit and implement a functional language with that architecture. Specially useful is reading his PhD Thesis, that covers the architecture and implementation of lambdachine in some detail.

Here is a short list of useful links:

  - [lambdachine](https://github.com/nominolo/lambdachine)
  - [Trace-based Just-in-time Compilation for Lazy Functional Programming Languages](http://files.catwell.info/misc/mirror/tracing-jit-haskell-schilling.pdf)


### Servo Project

While the Servo Project is a web browser engine rather then a virtual machine, they still face some of the same problems that we do. These problems are mostly related on how to integrate a garbage collector with the Rust language.

  - [JavaScript: Servo’s only garbage collector](https://blog.mozilla.org/research/2014/08/26/javascript-servos-only-garbage-collector/)
  - [Servo Project on GitHub](https://github.com/servo/servo)

### Self Language

The Self language is where JIT compilers grew up. The early research is still relevant to everything we do. Especially the PhD theses of Craig Chambers and Urs Hölzle written during that research program in the early 1990s. They still are a fantastic read.

  - [The Design and Implementation of the Self Compiler, an Optimizing Compiler for Object-Oriented Programming Languages](http://bibliography.selflanguage.org/craig-thesis.html)
  - [Adaptive optimization for Self: Reconciling High Performance with Exploratory Programming](http://bibliography.selflanguage.org/urs-thesis.html)

(Note: If you have troubles finding the some papers, contact us.)
