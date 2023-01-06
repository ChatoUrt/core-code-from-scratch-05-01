# core-code-from-scratch-05-01

## ---Strings---
* [Strings and concatenation](https://www.jshero.net/en/koans/string.html)
 
 Solution / /
 ``` javascript
 function greet(name){
  return 'Hello ' + name + '!';
 }
 ```
 
 ---
 ## --- String: lenght---
 
 * [.length property](https://www.jshero.net/en/koans/stringlength.html)
 
 Solution / /
 
``` javascript
function length(charNumb){
  return charNumb.length;
}
```

---
## ---String: UpperCase/LowerCase---

* [UpperCase() and LowerCase()](https://www.jshero.net/en/koans/stringupper.html)

Solution / /
``` javascript
function toCase(v){
  return v.toLowerCase() + '-' + v.toUpperCase();
}
```

---
## ---String: charAt()---

* [charAt() method](https://www.jshero.net/en/koans/stringcharat.html)

Solution / /
``` javascript
funtion shortcut(v1, v2){
  return v1.charAt() + v2.charAt();
}
```

---
## ---String: indexOf()---

* [How to use the indexOf() method](https://www.jshero.net/en/koans/stringindexof.html)

Solution / /
``` javascript 
function indexOfIgnoreCase(v1, v2){
  let v1Lower = v1.toLowerCase();
  let v2Lower = v2.toLowerCase();
  return v1Lower.indexOf(v2Lower);
}
```
---
## Knowledge Base
1. [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
2. [Concatenating strings](https://attacomsian.com/blog/javascript-string-concat)
3. [String length](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length) <br>
3.1. [String length](https://www.w3schools.com/jsref/jsref_length_string.asp)
4. [String: .toUpperCase](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase)
5. [String: .toLowerCase](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase)
6. [String: .charAt()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt)
7. [String: .indexOf()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)
