Original:
 
```
const arr = [2, 4, 5, 1, 7, 5, 2, 1];
// Only change code below this line

// Only change code above this line
console.log(arr);
```

Solution:

```
const arr = [2, 4, 5, 1, 7, 5, 2, 1];

arr.splice(0, 1); // => [ 4, 5, 1, 7, 5, 2, 1 ]
arr.splice(3);   //  => [ 4, 5, 1 ] sum is 10

console.log(arr);
```