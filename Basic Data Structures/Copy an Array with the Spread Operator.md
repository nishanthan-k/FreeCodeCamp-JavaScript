Original:

```
function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // Only change code below this line
    
    // Only change code above this line
    num--;
  }
  console.log(newArr);
  return newArr;
}

console.log(copyMachine([true, false, true], 2));
```

Solution:

```
function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // Only change code below this line
    newArr.push([...arr]);
    // Only change code above this line
    num--;
  }
  
  return newArr;
}

console.log(copyMachine([true, false, true], 2));   
```