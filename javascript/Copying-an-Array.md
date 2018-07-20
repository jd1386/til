### Copying an Array

.slice() 라는 array method로 array의 복사본을 만들 수 있다.

```javascript
var fruits = ['Apple', 'Orange'];
var shallowCopy = fruits.slice();
console.log(shallowCopy);
// ['Apple', 'Orange']
```

원래 .slice()라는 array method는 인자에 따라 복사된 array를 리턴한다.

```javascript
var fruits = ['Apple', 'Orange', 'Strawberry', 'Banana'];
var shallowCopy = fruits.slice(1, 3);
console.log(shallowCopy);
// => ['Strawberry', 'Banana']
var shallowCopy2 = fruits.slice(1);
console.log(shallowCopy2);
// => ['Orange', 'Strawberry', 'Banana']
```







