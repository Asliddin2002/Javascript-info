# Javascript-info

1. Object literal?
A: {}
2. Primitive? 
A: – Their value is single thing.
3. For object properties there is no name restrictions.
4. let a = {b: “Asliddin”}
“b ” in a 	// true­
5. Difference between copying primitive types and reference types?
A: As whole value,  copied by reference respectively
6. Difference way of copying: for(let key in obj){} 2. Object.assign() 3. spread Operators
	4. structuredClone    let clone =  structuredClone(user)  
7. The structuredClone method can clone most data types, such as objects, arrays, primitive values.
8. When the value of  “This”  is defined?
A: During Runtime.
9. If we write this in arrow function what will it be? It will take its value from outer function.
10. Why we use new keyword? In order to create similar objects.
11. What is difference between constructor function and regular function?
A: 1. CF has a name in capital letters. 2. They should be executed with new keyword.
12. How constructor function works?
A: 1. creates new empty object and assign to this. 2. function body executes, usually this obj, adds new properties to it.
3. and it return “This” object

13. How we know that our function is called with new keyword?  New.target
14. What will constructor function returns? // this object
what if we return primitive type it will ignore if we return reference type it will take it into account.
