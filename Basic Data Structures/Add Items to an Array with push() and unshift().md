Original:

```
function mixedNumbers(arr) {
  // Only change code below this line

  // Only change code above this line
  return arr;
}

console.log(mixedNumbers(['IV', 5, 'six']));
```

Solution:

```
function mixedNumbers(arr) {
  arr.unshift('I', 2, 'three');
  arr.push(7, 'VIII', 9 );
  
  return arr;
}

console.log(mixedNumbers(['IV', 5, 'six']));    
```