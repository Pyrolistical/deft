<p align="center">
  <img src="logo.svg" width="200" height="200" alt="deft logo" />
</p>

deft
====

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/deft)

Syntax
------

### Canonical form

`deft` is mostly syntactic sugar with a handful of canonical forms. This allows tools to work closer to the semantics of what the code is expressing, rather the syntax.

### Everything is a "function"

  * functions are closures assigned an indentifer
  * closures take in a tuple and return a tuple

Semantics
---------

  * closure tuples are curried, thus closure can be thought of as taking in a single value and returning a single value