Static
- Makes a variable static, meaning all classes made that use this variable share the same variable
- Makes a method static, meaning the method can be accessed using both a class instance AND the class itself

Why use static?
- Wanting all classes to share a characteristic, like count of all of that object.
	- Shared info
- Wanting all classes to use the same helper function. 

Restrictions:
Static methods cannot use non-static methods/variables
- The non static method is made during class creation, so you're "calling a method that doesn't exist yet"
- "this" is implicit in non static classes, not in static classes
- Same for variables
- You CAN refer to a specific instance of an object IF it was instantiated before static class call