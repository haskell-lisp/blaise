blaise
======

Slava Akhmechet's Lisp (implemented in Haskell) from 2006

### Intro

This project is described in Slava's related
[post on the topic](http://www.defmacro.org/ramblings/lisp-in-haskell.html). 
There is also some 
[related material](http://members.gamedev.net/coffeemug/test/blaise/faq.html)
discussing Slava's motivation for working on this project.

### Dependencies

You will need Haskell installed on your system. Download:
 * http://www.haskell.org/platform/

Then install `cabal-dev`:
```bash
$ cabal install cabal-dev
```

You may need to add the cabel-dev `bin` directory to your `$PATH`.


### Building

Get the source:
```bash
$ git clone https://github.com/haskell-lisp/blaise.git
$ cd blaise
```

Build, install in, and run from a local dev env:
```bash
$ cabal-dev install
$ ./cabal-dev/bin/blaise
```
