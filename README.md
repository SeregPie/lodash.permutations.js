# lodash.product

`_.product(...collections)`

Calculates the Cartesian product between multiple collections.

| argument | description |
| ---: | :--- |
| `collections` | Iterables of values to calculate the Cartesian product from. |

Returns a new array.

## dependencies

- [lodash](https://github.com/lodash/lodash)

## usage

```javascript
let product = _.product([false, true], ['a', 'b', 'c'], [{}]);
// => [[false, 'a', {}], [false, 'b', {}], [false, 'c', {}], [true, 'a', {}], [true, 'b', {}], [true, 'c', {}]]
```

```javascript
let array = [1, 2, 3];
let product = _.product(array, array);
// => [[1, 1], [1, 2], [1, 3], [2, 1], [2, 2], [2, 3], [3, 1], [3, 2], [3, 3]]
```
