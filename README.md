[![Build Status](https://travis-ci.org/skaterdav85/pipe-operator.svg?branch=master)](https://travis-ci.org/skaterdav85/pipe-operator)

# pipe-operator

A small library to simulate the pipe operator in languages like Elixir for JavaScript

## Installation

```
npm install pipe-operator
```

## Usage

```js
function sum(a, b) {
  return a + b;
}

take(1).pipe(sum, 3, 2).pipe(sum, 4).result(); // 10
```

Thanks to [Sebastiaan Luca](https://blog.sebastiaanluca.com/enabling-php-method-chaining-with-a-makeshift-pipe-operator) for the API inspiration.
