# New•FrontEnd•Resources

#### This directory contains a number of resources for the Front End Coding Bootcamp
###### Copyright (c)2023, Promineo Tech


## Variable Declaration:

```JavaScript
var x = "value";
let y = "value";
const z = "value"; (constant, can not be changed)
```

## Data Types:
	• 	Number (e.g. 42)
	• 	String (e.g. "Goodbye World")
	• 	Boolean ( e.g. true/false)
	• 	Undefined (e.g. undefined)
	• 	Null (e.g. null)
	• 	Object (e.g. {})
	• 	Array (e.g. [1,2,3,4,5])


## Arrays:
	•	Create: var arr = [element1, element2, element3];
	•	Access: arr[index];
	•	Update: arr[index] = newElement;
	•	Methods: 
		•	arr.push(element)
		•	arr.pop()
		•	arr.shift()
		•	arr.unshift(element)
		•	arr.slice(start, end)
		•	arr.splice(index, deleteCount, element)


## Operators:
	•	Arithmetic: +, •, *, /, % (modulo)
	•	Assignment: =, +=, •=, *=, /=, %=
	•	Comparison: ==, ===, !=, !==, >, <, >=, <=
	•	Logical: &&, ||, !


## Control Flow: 

### if•else: 
```JavaScript
	if (condition) { 
		statement1(s); 
	} else {
		statement2(s);
	}
```

### switch:
```JavaScript
	switch (expression) { 
		case x: statement1; 
		   	 	break; 
		case y: statement2; 
				break; 
		default: statement3; 
	}
```

### for loop:
```JavaScript
	for (var i = 0; i < 10; i++) { 
		statement(s); 
	}
```

### while loop:
```JavaScript
	while (condition) {
		statement(s);
	}
```

### do•while loop:
```JavaScript
	do {
	statements(s);	
	} while (condition);
```

## Functions:
	•	Define: function name(param1, param2) { statement; }
	•	Call: name(arg1, arg2);
	•	Arrow function: (param1, param2) => { statement; }

## Objects
	•	Create: var obj = { key1: value1, key2: value2 };
	•	Access: obj.key1 or obj["key1"]
	•	Update: obj.key1 = newValue;
	
## Event Handling:
	•	element.addEventListener("eventType", function() { statement; });
	•	Example: button.addEventListener("click", function() { alert("Button clicked!"); });




## DOM Manipulation
	•	Get element: document.getElementById("id"), document.querySelector("css selector")
	•	Change content: element.innerHTML = "new content";
	•	Change style: element.style.property = "new value";



## String Methods
	•	length: str.length
	•	concatenate: str1 + str2
	•	indexOf: str.indexOf("substring")
	•	slice: str.slice(start, end)
	•	replace: str.replace("old", "new")
