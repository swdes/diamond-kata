# TDD

## What
Write tests before the code

## Why
- full code coverage
- KISS
- modularity / architecture
- document
- easy to refactor
- ease collaboration (no fear to break something)
- less dependencies / useless code
- less bug fix...
- clear interfaces

But, on the other hand
- you have to maintain your tests
- some tests are hard to write: mocks, strong integration...
- difficult with legacy code
- don't push the tests to far... as everything, consume with moderation


## How
![](https://www.testingexcellence.com/wp-content/uploads/2016/11/pros_cons_tdd-768x455.jpeg)
```
for (const spec in specs) {
    1. RED: Create a test and check it fails
    2. GREEN: Code the spec so test is successfull
    3. REFACTO: Refactor if needed
}
```

# Diamand Kata

1. Print a A diamond
2. Print a B diamond
3. Print a C diamond
4. Print a D diamond

printDiamond("D") should produce a string containing
```
    A
   B B
  C   C
 D     D
  C   C 
   B B
    A
```