# Introduction

### The capacities for great coders:
* Analytical problem solving with code
* technical communication: (can i implement your approach just from your explanation)
* engineering best practies and approach (debugging, code structure, patience, and reference to documentation)
* non-technical communication
* language and computer science experience (not that important)
---
### Execution Context:
> what happens when javascript executes my code? 
* the thread of execution is **line by line**
* A local memory ('variable environment') where anything defined in the function is stored.

#### How do you know what fn you're in?
* Call stack:
  * first in (push) last out (pop).

##### Buzz words:
* `parameter` is the *primitive* value passed into a function
  * `primitive` = string / boolean / null / undefined / object
* functions default to *undefined*
* `execution context` created when a function is called with parens
* `memory` = inputs and results of a function?
* `thread` = javascript going line by line
* `just in time compilation` = optimizations around which bits get assigned to memory first
