## .css() vs. .animate()

The .animate() method only works on CSS properties that have **numeric values**. 

The.css() method does **not** work on CSS properties that have **strings as values**.



#### .animate()

```javascript
$('#button').on('click', () => {
  $('.example').animate({
    opacity: 0.25,
    left: "+=50"
  }, 5000); 
});
```



#### .css()

```javascript
$('#button').on('click', () => {
  $('.example').css({
    backgroundColor: "yellow",
    fontSize: "20px"
  }); 
});
```

