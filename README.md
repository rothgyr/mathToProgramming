# mathToProgramming
I've noted the correlations between math and functional programming. Let's explore it.

## History of Functional Programming
When there was a craze for developers in the 90s, mainstream programming switched from functional to classical, or verb based to noun based. Before the developer craze, most programmers were mathematicians, and it makes sense that the paradigm was closer to math. Take the base function for calculating derivitives as an example:

```
limit h->0

(f(x+h) - f(x)) / h
```

In programming, it might look something like this:

```javascript
const f = (x) => 3x^2-3x

const g = (x) => x + h

const h = () => 'some function that represents limit approaching zero'

const i = (number) => number / h 

const derivitive = i(f(g(x))-f(x))
```

We compose functions. You could even introduce async with `h` and get it really rolling.

