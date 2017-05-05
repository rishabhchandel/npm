# Sort data
sort data like JSON of ARRAY on basis of key

## Installation

```js
$ npm install sortjson
```

## Basic Usage
```		
var sort = require('sortjson');
For Ascending Order
  sort..inAscendingOrder(arr, key);

For Descending Order
  sort.inDescendingOrder(arr, key);

  key is field on basis are you sorted array of json.
```

## Code
```
var sort = require('sortjson');

var  arr = [{name:"rishabh",age:33},{name:"amit",age:52},{name:"varun",age:63},{name:"alisha",age:19},{name:"shreya",age:21}]

//sort array json in Ascending Order
console.log(sort.inAscendingOrder(arr,'name'));

Result:
[ { name: 'alisha', age: 19 },
  { name: 'amit', age: 52 },
  { name: 'rishabh', age: 33 },
  { name: 'shreya', age: 21 },
  { name: 'varun', age: 63 } ]

//sort array json in Descending Order
console.log(sort.inDescendingOrder(arr,'name'));
Result:
[ { name: 'varun', age: 63 },
  { name: 'shreya', age: 21 },
  { name: 'rishabh', age: 33 },
  { name: 'amit', age: 52 },
  { name: 'alisha', age: 19 }
```
