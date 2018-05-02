# Functional Programming


## Pure functions:
* `pure functions` = no 'side effects', meaning, when a function is run there are no consequences. function is consistent based on its inputs


## High Order Functions:
* `Higher order functions` ? 
```
function tensquared() {
  return 10 * 10;
}
tensquared(); // 100
```

should abstract above to something like:

```
function squareNum(num) {
  return num * num;
}
squareNum(10) // 100
squareNum(9) // 81
```


##### Buzz words:
* `functional programming` = paradigm of code writing utilizing functions calling other functions.
  > functions are first class citizens'
* `OOP` = object oriented programming
* `immutability` = unchangeable pieces
* `modularize` = 'reusable'