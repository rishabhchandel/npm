# Sort data 
sort data like JSON of ARRAY on basis of key

## Installation

```js
$ npm install sortjson
```

## Basic Usage
  ```		
  var sort = require('sortjson');
  
var  arr = [{name:"rishabh",age:33},{name:"amit",age:52},{name:"varun",age:63},{name:"alisha",age:19},{name:"shreya",age:21}]

//sort array json in Ascending Order
console.log(sort.inAscendingOrder(arr,'name'));

//sort array json in Descending Order
console.log(sort.inDescendingOrder(arr,'name'));

```


