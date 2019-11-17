## requirement 
    
- Create a new main. Js file, write a function, implement the following function: a string output in reverse order.

```
function reverseString(message){
  // wirte your code here
}
reverseString('hello'); // should return 'olleh'
```
function reverseString(str) {
    var splitString = str.split(""); // var splitString = "hello".split("");
    var reverseArray = splitString.reverse(); // var reverseArray = ["h", "e", "l", "l", "o"].reverse();
    var joinArray = reverseArray.join(""); // var joinArray = ["o", "l", "l", "e", "h"].join("");
    return joinArray; // "olleh"
}
