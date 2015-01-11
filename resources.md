---
layout: page
title: Resources
---

<p>
  Very little we do is original, so here is a list of resources that helped us.
</p>

<p>
  There are many more resources that can not all be mentioned here, but we want to thank everybody that has worked, commented or donated to these projects. Thank you.
</p>

<h3>Luajit</h3>

<p> This fantasic project is our closes Ancestor, and without it, we would be nowwhere near where we are today. Our Architecture will be very simular, a (hopefully) fast interpreter combined with a single tracing jit.  </p>

<p> On a more detailed level, we also look at LuaJit, for example our <a src="https://github.com/clojit/clojit-doc/blob/master/Bytecode%20Spec.md"> Bytecode </a> is very much inspired by <a href="http://wiki.luajit.org/Bytecode-2.0">  LuaJit Bytecode. </a> </p>

<p> There is a lot left to devlop, and a lot left to learn from LuaJit. <p>

<ul>
  <li> <a href="http://luajit.org/"> The LuaJIT Project </a> </li>
  <li> <a href="http://wiki.luajit.org/"> LuaJit Wiki </a> </li>
</ul>

<h3>wingolog</h3>

<p> The blogger Andy Wingo has many posts on JIT compilers and other usful matter. We regularly consult this blog for overviews of the current state of the art in JIT compilers and the details of the Guile VM. <p>

<p> Here is a short list of usful links: <p>

<ul>
  <li> <a href="http://wingolog.org/archives/2011/05/18/value-representation-in-javascript-implementations"> value representation in javascript implementations </a> </li>
  <li> <a href="http://wingolog.org/">  http://wingolog.org/ </a> </li>
</ul>

<h3>lambdachine</h3>

<p> Thomas Schilling had a very simular idea to ours, look at LuaJit and implment a functional language with that architecture. Specially usful is reading his PhD Thesis that goes over the inpmentation in some detail. <p>

<p> Here is a short list of usful links: <p>

<ul>
  <li> <a href="https://github.com/nominolo/lambdachine"> lambdachine </a> </li>
  <li> <a href="http://files.catwell.info/misc/mirror/tracing-jit-haskell-schilling.pdf">  Trace-based Just-in-time Compilation for Lazy Functional Programming Languages </a> </li>
</ul>

<h3>Servo Project</h3>

<p> While the Servo Project is a web browser engine rather then a virtual maschine, they still face simular problems that we have too. The problems are mostly related to the Garbage Collector and the Rust language.  <p>

<ul>
  <li> <a href="https://blog.mozilla.org/research/2014/08/26/javascript-servos-only-garbage-collector/"> JavaScript: Servo’s only garbage collector </a> </li>
  <li> <a href="https://github.com/servo/servo">  Servo Project on Github </a> </li>
</ul>


<h3> Self Language </h3>

<p> The Self langauge is where JIT compilers grew up. The early research is still relevant to everything we do. <p>

<ul>
  <li>
    <a href="http://bibliography.selflanguage.org/craig-thesis.html">
      The Design and Implementation of the Self Compiler, an Optimizing Compiler for Object-Oriented Programming Languages
    </a>
  </li>
  <li>
    <a href="http://bibliography.selflanguage.org/urs-thesis.html">
      Adaptive optimization for Self: Reconciling High Performance with Exploratory Programming
    </a>
  </li>
</ul>

<p> (Note: If you cant find the first paper, contact us) </p>
