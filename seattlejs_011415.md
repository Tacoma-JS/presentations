Dear Tacoma-JS Coders,

Fortunately I was able to attend the 14-Jan SeattleJS meetup
to hear about the wonders of Observables/Reactive coding and
Abstract Syntax Trees presented by
[Jeremy Foster](https://github.com/codefoster) and
[Jamund Ferguson](https://github.com/xjamundx) respectively.

To be sure the color and excitement of being there in
person is difficult to translate into a newsletter, however
please take a few minutes to have a look at these two
perspectives that were so eloquently presented.

* [reactivex.io](http://reactivex.io/)
* [AST](https://en.wikipedia.org/wiki/Abstract_syntax_tree) - Abstract Syntax Tree

============================================================

## [Observer Patterns](https://en.wikipedia.org/wiki/Observer_pattern)

The observer pattern is a software design pattern in which
an object, called the subject, maintains a list of its
dependents, called observers, and notifies them automatically
of any state changes, usually by calling one of their methods.
It is mainly used to implement distributed event handling
systems. The Observer pattern is also a key part in the
familiar model view controller (MVC) architectural pattern.


### [ReactiveX](http://reactivex.io/intro.html)

ReactiveX is a library for composing asynchronous and
event-based programs by using observable sequences.

It extends the observer pattern to support sequences of data
and/or events and adds operators that allow you to compose
sequences together declaratively while abstracting away
concerns about things like low-level threading,
synchronization, thread-safety, concurrent data structures,
and non-blocking I/O. 

============================================================

## [Abstract Syntax Tree](https://en.wikipedia.org/wiki/Abstract_syntax_tree)

... is a tree representation of the abstract syntactic
structure of source code ...

Abstract syntax trees are also used in program analysis and
program transformation systems.

Think power tools for manipulating your javascript on a
large scale, search and replace on steroids, minification,
rule creation for known bug detection, code modification to
meet best practice standards, automatic version upgrades to
'fix' existing installed code, ...

Want immediate feedback in your browser?
[AST Explorer](http://astexplorer.net/)

Some AST manipulation tools
  * npmjs/[acorn](https://www.npmjs.com/package/acorn)
    * on [github](https://github.com/ternjs/acorn)
  * [eslint](http://eslint.org/)
    * on [github](https://github.com/eslint/eslint)
  * npmjs/[jscodeshift](https://www.npmjs.com/package/jscodeshift)
    * on [github](https://github.com/facebook/jscodeshift)
  * [babeljs.io](https://babeljs.io/)
    * on [github](https://github.com/babel/babel)

============================================================

At the end of the meeting I also had a chance to discuss
with Chris of [encapsule.io](https://encapsule.io/) his code:

## [JBUS](https://github.com/Encapsule/jbus) 

 ... a bi-directional JSON processing engine, sub-system
communication bus, in-memory transport, and serialization
infrastructure for building marvelously decoupled, composable
apps and services that talk to each other through jbus - not
directly to one another using conventional in-process
function or network calls.

============================================================

I hope you have found this letter informative and usefull.

Your organizer,

Joe Devlin
