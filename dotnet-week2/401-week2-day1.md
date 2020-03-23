### Week 2, Monday
## OOP Principles

#### What
__Test-Driven Development__ (TDD) is the process of building code based on the tests needed to prove that the code has the intended result

#### Why
We use TDD in order to develop *best-practice* code that doesn't reach beyond what our initial problem domain is,
that doesn't try to do too much with a single method, or strays away from our intended output.
It also helps us develop code that actually *is* testable. As I've found in the first week, it's far to easy, writing code first
and testing it later, to write un-readable un-testable code that is just a big mess of user input, redundant algorithms,
and wasted time and memory. TDD also promotes retention of Big O Principles, making our code space and time efficient.

#### How
Of course it's just as useless to write tests for code that is nonexistant yet, so the best way to practice TDD is to
start with what kind of test your writing, and use __Red-Green-Refactor__ process to go back and forth between your program code
and your test code, keeping them in line with eachother. Every non-void method should start with some kind of test to challenge it
and make sure it is responding to the correct paramaters with acceptable output. Be warned, the process is *very* slow at first, 
but with practice and muscle-memory, it will become your go to process for building modules.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)