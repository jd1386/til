### Array 정렬하기



```javascript
// alphabetical order

var nonSortedArray = ['hi', 'yo', 'whatup', 'bye', 'lol'];
var sortedArray = nonSortedArray.sort(function (a, b) {
      if (a < b) return -1;
      else if (a > b) return 1;
      return 0;
    });
console.log(sortedArray); // ["bye", "hi", "lol", "whatup", "yo"]
```



```javascript
// reverse alphabetical order

var nonSortedArray = ['hi', 'yo', 'whatup', 'bye', 'lol'];
var reverseSortedArray = nonSortedArray.sort(function (a, b) {
      if (a > b) return -1;
      else if (a < b) return 1;
      return 0;
    });
console.log(reverseSortedArray); // ["yo", "whatup", "lol", "hi", "bye"]
```

