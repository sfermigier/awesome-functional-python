## Awesome Functional Python

> A curated list of awesome things related to functional programming in Python.

- [Official documentation](#official-documentation)
- [Books](#books)
- [Talks](#talks)
- [Other resources](#other-resources)
- [Libraries](#librairies)
- [Languages](#languages)


### Official documentation

- [Functional Programming HOWTO](https://docs.python.org/3/howto/functional.html) - "In this document, we’ll take a tour of Python’s features suitable for implementing programs in a functional style".


### Books

#### Free books / ebooks

- [Functional Programming in Python](http://www.oreilly.com/programming/free/files/functional-programming-python.pdf) by David Mertz (O'Reilly)

#### Non-free books

- [Functional Python Programming](https://www.packtpub.com/application-development/functional-python-programming), by Steve Lott (Packtpub, 2015)
- [Python Reactive Programming](https://www.packtpub.com/application-development/python-reactive-programming), by Dag Brattli (Packtpub, 2017 - preorder)


### Talks

#### Introductory

- Functional Programming with Python ([slides](http://kachayev.github.io/talks/uapycon2012/)), Alexey Kachayev, UA PYCon 2012.
- Purely Functional Programming in Python: Pure Fun ([slides](https://speakerdeck.com/radix/purely-functional-programming-in-python-pure-fun)), Christopher Armstrong, PyTenessee 2015.
- Functional Programming with Python ([video](https://www.youtube.com/watch?v=Ta1bAMOMFOI)), Mike Müller, PyCon US 2013.
- Using Functional Programming for efficient Data Processing and Analysis ([video](https://www.youtube.com/watch?v=9kDUTJahXBM)), Reuben Cummings, PyCon US 2017.

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

- [Functional Programming with Python](http://shop.oreilly.com/product/0636920042778.do), by Christopher Armstrong, O'Reilly.

#### Blog posts

- [Origins of Python's "Functional" Features](http://python-history.blogspot.fr/2009/04/origins-of-pythons-functional-features.html), Guido Van Rossum, 2009.
- [A practical introduction to functional programming](https://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming) (with examples in Python), by Mary Rose Cook (year unknown).
- [Immutable data structures in Python](https://www.theguardian.com/info/developer-blog/2014/oct/21/immutable-data-structures-in-python), Robert Rees, 2014.
- [Understanding Transducers through Python](http://sixty-north.com/blog/series/understanding-transducers-through-python), by Robert Smallshire. "In this 8 parts series we take an in-depth look at transducers. Transducers – a portmanteau of ‘transform reducers’ – are a new functional programming concept introduced into the Clojure programming language."
- [Thinking Functionally with Python and Django at eShares Inc.](https://medium.com/@hansonkd/thinking-functionally-with-python-and-django-4127e3ace6e9#.own6sie8s), Kyle Hanson, 2017.


#### Scientific papers

- [Practical Functional Reactive Programming](http://www.cs.jhu.edu/~roe/padl2014.pdf) (PDF), John Peterson, Ken Roe, and Alan Cleary, 2014.


### Libraries

#### General

- [toolz](https://github.com/pytoolz/toolz) ★1500 - "A functional standard library for Python".
- [funcy](https://github.com/suor/funcy/) ★1300 - "A fancy and practical functional tools".
- [fn.py](https://github.com/kachayev/fn.py) ★2100 - "Functional programming in Python: implementation of missing features to enjoy FP" (unmaintained since 2014).
- [hask](https://github.com/billpmurphy/hask) ★500 - "Haskell language features and standard libraries in pure Python".
- [PyFunctional](https://github.com/EntilZha/PyFunctional) ★390 - "Python library for functional programming with collections in a data pipeline style".
- [more-itertools](https://github.com/erikrose/more-itertools) ★330 - "More routines for operating on iterables, beyond itertools".
- [Effect](https://github.com/python-effect/effect) ★200 - "Effect isolation in Python, to facilitate more purely functional code".
- [Pydash](https://github.com/dgilland/pydash) ★160 - "The kitchen sink of Python utility libraries for doing "stuff" in a functional way. Based on the Lo-Dash Javascript library".
- [Underscore.py](https://github.com/serkanyersen/underscore.py) ★220 - "A Python port of excellent javascript library underscore.js".
- [pyramda](https://github.com/jackfirth/pyramda) ★30 - "Python package supporting heavy functional programming through currying. Translation of the Ramda library from javascript to python".
- [PyMonad](https://bitbucket.org/jason_delaat/pymonad) - "a small library implementing monads and related data abstractions -- functors, applicative functors, and monoids -- for use in implementing functional style programs".
- [Amino](https://github.com/tek/amino) - "functional data structures and type classes".

#### Immutable / persistent data structures

- [Pyrsistent](https://github.com/tobgu/pyrsistent) ★500 - "Persistent/Immutable/Functional data structures for Python". 
- [Funktown](https://github.com/zhemao/funktown) ★60 - "Immutable Data Structures for Python".
- [Discodb](https://github.com/discoproject/discodb) ★50 - "An efficient, immutable, persistent mapping object".
- [Pysistence](https://pythonhosted.org/pysistence/) - "Pysistence is a project that seeks to make functional programming in python easier".

#### Other / specialized

- [Transducers](https://github.com/sixty-north/python-transducers) - "This is a port of the transducer concept from Clojure to Python, with an emphasis on providing as Pythonic as interpretation of transducers as possible, rather than reproducing Clojurisms more literally".
- [Tranducers-Python](https://github.com/cognitect-labs/transducers-python) - "Transducers are composable algorithmic transformations".
- [RxPy](https://github.com/ReactiveX/RxPY) - "Reactive Extensions for Python".
- [python-lenses](https://github.com/ingolemo/python-lenses) - "A python lens library for manipulating deeply nested immutable structures".

### Languages

Functional programming languages that are not Python but are related to the Python ecosystem:

- [Perl 6](https://github.com/niner/Inline-Python) - "Perl 6 can use Python inline and is mostly a functional language"
- [Hy](http://docs.hylang.org/en/latest/) - "A dialect of Lisp that’s embedded in Python".
- [Coconut](http://coconut-lang.org/) - "Simple, elegant, Pythonic functional programming".
- [Mochi](https://github.com/i2y/mochi) - "A dynamically typed programming language for functional programming and actor-style programming.".
- [Tydy](https://github.com/cyrus-/tydy) - "Tydy is a statically typed, functional-first programming language in the ML tradition. tydy is an implementation of Tydy as a Python library."
- [dg (aka dogelang)](https://pyos.github.io/dg/) - "A programming language that compiles to CPython bytecode, much like Scala compiles to JVM's. That essentially means that dg is an alternative syntax for Python 3."
- [pixie](https://github.com/pixie-lang/pixie) - "A lightweight and native lisp built in RPython". ([Discussion on HN](https://news.ycombinator.com/item?id=13420092))
- [Pycket](https://github.com/pycket/pycket) - "A rudimentary Racket implementation using RPython".
- [(How to Write a (Lisp) Interpreter (in Python))](http://norvig.com/lispy.html) and [(An ((Even Better) Lisp) Interpreter (in Python))](http://norvig.com/lispy2.html) - a couple of famous articles by Peter Norvig.

([More languages that compile to Python](https://github.com/vindarel/languages-that-compile-to-python))
