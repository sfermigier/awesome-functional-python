## Awesome Functional Python

> A curated list of awesome things related to functional programming in Python.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


- [Official documentation](#official-documentation)
- [Books](#books)
- [Talks](#talks)
- [Other resources](#other-resources)
- [Libraries](#libraries)
- [Languages](#languages)


### Official documentation

- [Functional Programming HOWTO](https://docs.python.org/3/howto/functional.html) - "In this document, we’ll take a tour of Python’s features suitable for implementing programs in a functional style".


### Books

#### Free books / ebooks

- [Functional Programming in Python](http://www.oreilly.com/programming/free/files/functional-programming-python.pdf) - Book by David Mertz (O'Reilly).

#### Non-free books

- [Functional Python Programming](https://www.packtpub.com/application-development/functional-python-programming) - Book by Steve Lott (Packtpub, 2015).

### Talks

#### Introductory

- Functional Programming with Python ([slides](http://kachayev.github.io/talks/uapycon2012/)) - Alexey Kachayev, UA PYCon 2012.
- Purely Functional Programming in Python: Pure Fun ([slides](https://speakerdeck.com/radix/purely-functional-programming-in-python-pure-fun)) - Christopher Armstrong, PyTenessee 2015.
- Side Effects are a Public API ([video](https://www.youtube.com/watch?v=D37dc9EoFus)) - Christopher Armstrong, Strangeloop 2015
- Functional Programming with Python ([video](https://www.youtube.com/watch?v=Ta1bAMOMFOI)) - Mike Müller, PyCon US 2013.
- Using Functional Programming for efficient Data Processing and Analysis ([video](https://www.youtube.com/watch?v=9kDUTJahXBM)) - Reuben Cummings, PyCon US 2017.
- Immutable Programming Writing Functional Python ([slides](https://speakerdeck.com/pycon2017/calen-pennington-immutable-programming-writing-functional-python), [video](https://www.youtube.com/watch?v=_OLEVvjrIj8)), Calen Pennington, PyCon 2017

#### Advanced or specialized

- Functionalish programming in Python with effect ([video](https://www.youtube.com/watch?v=fM5d_2BS6FY)), Robert Collins, NZ PyCon 2015.
- Monadic Parsing in Python ([slides](https://speakerdeck.com/kachayev/monadic-parsing-in-python)), Alexey Kachayev, KyivPy 2014.
- Immutability and Python - Introducing Pyrsistent ([slides](http://slides.com/tobiasgustafsson/immutability-and-python)), Tobias Gustafsson, 2014.
- Understanding Transducers ([slides](http://www.slideshare.net/alinadolgikh/austin-bingham-transducers-in-python), [video](https://www.youtube.com/watch?v=z_cmmbRQXh4)), Austin Bingham, PyCon Belarus 2015.

#### Data science oriented

- Functional Performance with Core Data Structures ([video](https://www.youtube.com/watch?v=PpBK4zIaFLE)), Matthew Rocklin, PyData SV 2014.
- Old School - Functional Data Analysis ([video](https://vimeo.com/80096814)), Matthew Rocklin, PyData NYC 2013.
- Learning Data Science Using Functional Python ([video](https://www.youtube.com/watch?v=ThS4juptJjQ), [slides](https://docs.google.com/presentation/d/1eI60SL3UxtWfr9ktrv48-pcIkk4S7JiDmeXGCyyGhCs)), Joel Grus, PyData Seattle 2015.

### Other resources

#### Video lectures

- [Functional Programming with Python](http://shop.oreilly.com/product/0636920042778.do) - by Christopher Armstrong, O'Reilly.
- [Functional Programming in 7 days](https://www.udemy.com/functional-programming-in-7-days/) - by Mohammed Kashif, Udemy.

#### Blog posts

- [Origins of Python's "Functional" Features](http://python-history.blogspot.fr/2009/04/origins-of-pythons-functional-features.html), Guido Van Rossum, 2009.
- [A practical introduction to functional programming](https://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming) (with examples in Python), by Mary Rose Cook (year unknown).
- [Immutable data structures in Python](https://www.theguardian.com/info/developer-blog/2014/oct/21/immutable-data-structures-in-python), Robert Rees, 2014.
- [Understanding Transducers through Python](http://sixty-north.com/blog/series/understanding-transducers-through-python), by Robert Smallshire. "In this 8 parts series we take an in-depth look at transducers. Transducers – a portmanteau of ‘transform reducers’ – are a new functional programming concept introduced into the Clojure programming language."
- [Thinking Functionally with Python and Django at eShares Inc.](https://medium.com/@hansonkd/thinking-functionally-with-python-and-django-4127e3ace6e9#.own6sie8s), Kyle Hanson, 2017.
- [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) - Nikita Sobolev, 2019.
- [Python exceptions considered an anti-pattern](https://sobolevn.me/2019/02/python-exceptions-considered-an-antipattern), Nikita Sobolev, 2019.
- [Enforcing Single Responsibility Principle in Python](https://sobolevn.me/2019/03/enforcing-srp) - Nikita Sobolev, 2019.
- [Typed functional Dependency Injection in Python](https://sobolevn.me/2020/02/typed-functional-dependency-injection) - Nikita Sobolev, 2020.
- [4 Part Series on Functional Programming Techniques and Design In Python](https://mpkocher.github.io/2019/03/01/Functional-Programming-Techniques-In-Python-Series/) M. Kocher, 2019.

#### Scientific papers

- [Practical Functional Reactive Programming](http://www.cs.jhu.edu/~roe/padl2014.pdf) (PDF), John Peterson, Ken Roe, and Alan Cleary, 2014.

#### Presentation slides

- [Python Generators](https://www.slideshare.net/SamuelLampa/py-sthlmmeetup15-pythongenerators), Samuel Lampa, From talk at PySthlm meetup, Oct 2013


### Libraries

#### General

- [toolz](https://github.com/pytoolz/toolz) ★3457 - "A functional standard library for Python".
- [fn.py](https://github.com/kachayev/fn.py) ★3082 - "Functional programming in Python: implementation of missing features to enjoy FP" (unmaintained since 2014).
- [funcy](https://github.com/suor/funcy) ★2469 - "A fancy and practical functional tools".
- [more-itertools](https://github.com/erikrose/more-itertools) ★1800 - "More routines for operating on iterables, beyond itertools".
- [PyFunctional](https://github.com/EntilZha/PyFunctional) ★1789 - "Python library for functional programming with collections in a data pipeline style".
- [returns](https://github.com/dry-python/returns) ★1585 - "Make your functions return something meaningful, typed, and safe!"
- [hask](https://github.com/billpmurphy/hask) ★827 - "Haskell language features and standard libraries in pure Python".
- [Pydash](https://github.com/dgilland/pydash) ★720 - "The kitchen sink of Python utility libraries for doing "stuff" in a functional way. Based on the Lo-Dash Javascript library".
- [Expression](https://github.com/cognitedata/Expression) ★87 - "Pragmatic functional programming for Python inspired by F#". Successor of OSlash.
- [OSlash](https://github.com/dbrattli/oslash) ★557 - "Functors, Applicatives, And Monads in Python".
- [Effect](https://github.com/python-effect/effect) ★323 - "Effect isolation in Python, to facilitate more purely functional code".
- [Underscore.py](https://github.com/serkanyersen/underscore.py) ★277 - "A Python port of excellent javascript library underscore.js".
- [Phi](https://github.com/cgarciae/phi) ★116 - "A library that intends to remove as much of the pain as possible from your functional programming experience in Python."
- [pyramda](https://github.com/jackfirth/pyramda) ★116 - "Python package supporting heavy functional programming through currying. Translation of the Ramda library from javascript to python".
- [PyMonad](https://bitbucket.org/jason_delaat/pymonad) - "a small library implementing monads and related data abstractions -- functors, applicative functors, and monoids -- for use in implementing functional style programs".
- [pyMonet](https://github.com/przemyslawjanpietrzak/pyMonet) ★27 - "High abstract python library for functional programming. Contains algebraic data structures known from Haskell or Scala".
- [pfun](https://github.com/suned/pfun) ★73 - "Pure functional programming in python".
- [fnc](https://github.com/dgilland/fnc) ★86 - "Functional programming in Python with generators and other utilities".
- [unpythonic](https://github.com/Technologicat/unpythonic) ★29 - "Supercharge your Python with parts of Lisp and Haskell."

#### Immutable / persistent data structures

- [Pyrsistent](https://github.com/tobgu/pyrsistent) ★1486 - "Persistent/Immutable/Functional data structures for Python".
- [Immutables](https://github.com/MagicStack/immutables) ★817 - "An immutable mapping type for Python."
- [Discodb](https://github.com/discoproject/discodb) ★95 - "An efficient, immutable, persistent mapping object".
- [Funktown](https://github.com/zhemao/funktown) ★75 - "Immutable Data Structures for Python".
- [Amino](https://github.com/tek/amino) ★31 - "functional data structures and type classes".
- [Pysistence](https://pythonhosted.org/pysistence/) - "Pysistence is a project that seeks to make functional programming in python easier".

#### Pattern matching

- [pampy](https://github.com/santinic/pampy) ★3344 - "Pampy: The Pattern Matching for Python you always dreamed of."
- [python-pattern-matching](https://github.com/grantjenks/python-pattern-matching) ★152 - "Python pattern matching like functional languages."
- [patmat](https://github.com/admk/patmat) ★31 - "Functional-style recursive pattern matching in Python. Crazy stuff."
- [apm](https://github.com/scravy/awesome-pattern-matching) ★77 - "Pattern Matching for Python 3.8+ in a simple, yet powerful, extensible manner."

#### Tranducers

- [Tranducers-Python](https://github.com/cognitect-labs/transducers-python) ★186 - "Transducers are composable algorithmic transformations".
- [Transducers](https://github.com/sixty-north/python-transducers) ★48 - "This is a port of the transducer concept from Clojure to Python, with an emphasis on providing as Pythonic as interpretation of transducers as possible, rather than reproducing Clojurisms more literally".

#### Support for reactive style

- [RxPy](https://github.com/ReactiveX/RxPY) ★3794 - "Reactive Extensions for Python".
- [broqer](https://github.com/semiversus/python-broqer) ★63 - "Library to operate with continuous streams of data in a reactive style"

#### Other / specialized

- [python-lenses](https://github.com/ingolemo/python-lenses) ★170 - "A python lens library for manipulating deeply nested immutable structures".
- [chainable](https://github.com/olirice/chainable) ★153 - "Method chaining built on generators".
- [deal](https://github.com/orsinium/deal) ★125 - "Design by contract for Python with many validators support."
- [ADT](https://github.com/jspahrsummers/adt) ★119 - Algebraic data types for Python
- [sumtypes](https://github.com/radix/sumtypes) ★33 - "Sum Types, aka Tagged Unions, for Python".
- [python-mini-lambda](https://github.com/smarie/python-mini-lambda) ★8 - "Simple Lambda functions without lambda x: and with string conversion capability"

### Languages

Functional programming languages that are not Python but are related to the Python ecosystem:

- [Hy](http://hylang.org/) - "A dialect of Lisp that's embedded in Python".
- [Coconut](http://coconut-lang.org/) - "Simple, elegant, Pythonic functional programming".
- [Mochi](https://github.com/i2y/mochi) ★905 - "A dynamically typed programming language for functional programming and actor-style programming.".
- [Tydy](https://github.com/cyrus-/tydy) ★47 - "Tydy is a statically typed, functional-first programming language in the ML tradition. tydy is an implementation of Tydy as a Python library."
- [dg (aka dogelang)](https://pyos.github.io/dg/) - "A programming language that compiles to CPython bytecode, much like Scala compiles to JVM's. That essentially means that dg is an alternative syntax for Python 3."
- [pixie](https://github.com/pixie-lang/pixie) ★2276 - "A lightweight and native lisp built in RPython". ([Discussion on HN](https://news.ycombinator.com/item?id=13420092))
- [Pycket](https://github.com/pycket/pycket) ★213 - "A rudimentary Racket implementation using RPython".
- [(How to Write a (Lisp) Interpreter (in Python))](http://norvig.com/lispy.html) and [(An ((Even Better) Lisp) Interpreter (in Python))](http://norvig.com/lispy2.html) - a couple of famous articles by Peter Norvig.

[More languages that compile to Python](https://github.com/vindarel/languages-that-compile-to-python).
