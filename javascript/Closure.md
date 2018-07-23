## Closure

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/71AtaJpJHw0/0.jpg)](http://www.youtube.com/watch?v=71AtaJpJHw0)



> "Closures are nothing but functions with preserved data."



유튜브 영상에 있는 코드를 그대로 가져와보면:

```javascript
var addTo = function (passed) {
	var inner = 2;
  return passed + inner;
};

console.log(addTo(3));
// => 5
```



