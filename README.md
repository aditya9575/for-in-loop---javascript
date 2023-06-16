# For...in Loops in JavaScript
This is a reference doc regarding how to use  -> for in loop   


A for...in loop is a type of loop that iterates over the properties of an object. The for...in loop is a powerful tool that can be used to iterate over complex objects, such as objects that contain nested objects.

The syntax for a for...in loop is as follows:

for (var variable in object) {
// code to be executed for each property in object
}

The variable variable is a temporary variable that is used to store the name of each property in the object. The object variable is the object that is being iterated over. The code to be executed for each property in object is the code that is executed for each property in the object.

The for...in loop iterates over the properties of the object in an unspecified order. This means that the order in which the properties are iterated over is not guaranteed.

The for...in loop can be used to iterate over any object, including objects that contain nested objects. When the for...in loop iterates over an object that contains nested objects, the for...in loop will iterate over the properties of the nested objects as well.


Here is an example of how to use a for...in loop to iterate over an object:

const object = {
"firstName": "John",
"lastName": "Doe",
"age": 30,
};

for (var property in object) {
console.log(property);
}

In this example, we first create an object called object. The object object has three properties: firstName, lastName, and age. Next, we use a for...in loop to iterate over the properties of the object object. For each property in the object object, we log the name of the property to the console.

The following is the output of the code:

firstName
lastName
age
