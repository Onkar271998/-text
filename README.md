# text 


Difference between props and state:

PROPS
The Data is passed from one component to another.
It is Immutable (cannot be modified).
Props can be used with state and functional components.
Props are read-only.

STATE

	The Data is passed within the component only.
	It is Mutable ( can be modified).
	State can be used only with the state components/class component (Before 16.0).
	State is both read and write.


    Map
    const numbers = [1, 2, 3, 4];
const doubled = numbers.map(item => item * 2);
console.log(doubled); // [2, 4, 6, 8]

Filter
var new_array = arr.filter(function callback(element, index, array) {
    // Return true or false
}[, thisArg])

ex.
const numbers = [1, 2, 3, 4];
const evens = numbers.filter(item => item % 2 === 0);
console.log(evens); // [2, 4]
