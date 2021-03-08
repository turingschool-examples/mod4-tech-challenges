# Bracket Matcher

Ever wonder how your linter knows if you have matching brackets? Well it's time to think of a solution to that!

Given a set of brackets, `[, {, (`, create a function that determines if the brackets are well-formed (match) or not - even with bracket nesting. For example:

```javascript
bracket('{}');

// => true
```

```javascript
bracket('{(');

// => false
```

```javascript
bracket('{()}');

// => true
```

```javascript
bracket('{[)][]}');

// => false
```

```javascript
bracket(']');

// => false
```

```javascript
bracket('({[]}{[]})');

// => true
```

## Instructions

1. Copy this markdown and paste in your own, private gist
2. In your private gist, fill out the questions below
4. Submit by the due time as instructed in Zoom


## Rewrite the question in your own words:


## What assumptions will you make about this problem if you cannot ask any more clarifying questions? What are your reasons for making those assumptions?


## What are your initial thoughts about this problem? (high level design, 2-3 sentences)


## How would you identify the elements of this problem?

- [ ] Searching of Data
- [ ] Sorting of Data
- [ ] Pattern Recognition
- [ ] Build/Navigate a Grid
- [ ] Math
- [ ] Language API knowledge
- [ ] Optimization


## Which data structure(s) do you think you'll use? What pros/cons do you see with that choice?


## Write out a few lines of initial pseudocode: (mid-level design, NOT REAL CODE)

## Write out any implementation code OR link to repl

## What is the Big O complexity of your solution?
