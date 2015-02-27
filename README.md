# map [![Circle CI][circleci-badge]][circleci-link]

Apply a function to a each element of a collection and return a new array of results.

## Installation

Browser:

```sh
component install ndhoule/map
```

Node:

```sh
$ npm install map
```

## API

### map(iterator : Function, collection : Object|Array|string) => Array

Produce a new array by passing each value in the input `collection` through a transformative `iterator` function. The `iterator` function is passed three arguments: `(value, index, collection)`.

```javascript
var square = function(x) { return x * x; };

map(square, [1, 2, 3]);
//=> [1, 4, 9]
```

## License

Released under the [MIT license](LICENSE.md).

[circleci-link]: https://circleci.com/gh/ndhoule/map
[circleci-badge]: https://circleci.com/gh/ndhoule/map.svg?style=svg&circle-token=70d335a8c955bf44faea736e8abc207f9bf852cf
