## requirement 
    
- Create a new main.js file and write a function that calculates how many words a string contains.

```
function countWords(message){
  // wirte your code here
}
countWords('Good morning, I love JavaScript.'); // should return 5
```
function countWords(message){
	var entry = message.split(" ");
	var len = entry.length;
	return len;
}