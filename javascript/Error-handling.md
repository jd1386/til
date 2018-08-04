### Error Handling

```javascript
try {
    // Block of code to try
	  if(x == "") throw "empty";
}
catch(err) {
    // Block of code to handle errors
  	console.log(err); 
  	// => "empty"
} 
finally {
    // Block of code to be executed regardless of the try / catch result
}
```

try-catch-finally is equivalant to Ruby's begin-rescue-ensure.