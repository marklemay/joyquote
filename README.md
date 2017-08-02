## Embedding Joy into Scala 

This tutorial is going to provide a step-by-step tutorial on how to
embed a subset of Joy programming language into Scala via a combination
of extensible string interpolation, macros, typeclasses and Scala's
extensible pattern matching.

The Joy was chosen as an example of small language that won't complicate
demonstration of core ideas used to implement custom quotations. The
same technique can be used to embed any other language too. For example
quasiquotes introduced in [Scala 2.11][1] are implemented in very similar
fashion.

To start the tutorial open the [list of commits][3] in the master branch
of this repo.

It is based on my ["Quote or be quoted" talk given on ScalaDays'14][2].
Slides from the talk are also available as a [plain pdf][4]. 

[1]: http://docs.scala-lang.org/overviews/quasiquotes/intro.html

[2]: https://www.youtube.com/watch?v=_c6SMsZNxms

[3]: https://github.com/densh/joyquote/commits/master

[4]: http://parleys.com/play/53a7d2c4e4b0543940d9e53e/chapter0/about
