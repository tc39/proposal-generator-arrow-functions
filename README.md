# ECMAScript proposal: Generator Arrow Functions

**Authors**: TBA

**Champion**: TBA

**Stage**: Stage 1 of [the TC39 process](https://tc39.github.io/process-document/).

## Motivation

> Experience so far has been that people love arrow functions and generators and want a generator arrow.
> — Brendan Eich

Both [arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions) and [generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*) are available since ES2015. Often people want to use generator arrow and this proposal (which was raised years ago) should solve their needs.

## Use cases

- [3 years old React example](https://gist.github.com/threepointone/014954c9270749d0b1d1051c12a705af)
- need more [use-cases](https://github.com/chicoxyzzy/proposal-generator-arrow-functions/issues/1)

## Possible solutions

```js
// Irregular
() =*> ...

// not the same order as in regular generator functions
() =>* ...

// also wrong order
() *=> ...

// ASI hazard
*() => ...
```

Discussion of future syntax: https://github.com/chicoxyzzy/proposal-generator-arrow-functions/issues/2

## TC39 meeting notes

- [20 November 2013](https://github.com/rwaldron/tc39-notes/blob/master/meetings/2013-11/nov-20.md#410-generator-arrow-function-syntax)
- [27 September 2016](https://github.com/tc39/tc39-notes/blob/master/meetings/2016-09/sept-27.md#11ic-generator-arrow-functions)
- [29 September 2016](https://github.com/tc39/tc39-notes/blob/master/meetings/2016-09/sept-29.md#arrow-generator-revisit)

## Implementations

- none yet
