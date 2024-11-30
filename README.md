# -DOM-Element-Selectors

This JavaScript script demonstrates various ways to select elements in the DOM using different methods. It provides examples for selecting elements by tag name, class name, ID, and CSS selectors.

## Methods Used

1. getElementsByTagName()

   Description: Selects all elements with the specified tag name.
```
var a = document.getElementsByTagName('li');
console.log(a);
```

2. getElementsByClassName()

   Description: Selects all elements with the specified class name.
```
var b = document.getElementsByClassName('hero'); 
console.log(b);

```

3. getElementById()\

   Description: Selects the first element with the specified ID.
```
var c = document.getElementById('hero');
console.log(c);
```

4. querySelector()
    Description: Selects the first element that matches the specified CSS selector.

```
var d = document.querySelector('#hero');
console.log(d);

var d = document.querySelector('.hero');
console.log(d);
```


5. querySelectorAll()

Description: Selects all elements that match the specified CSS selector.
```
var e = document.querySelectorAll('.hero'); 
console.log(e);
```
