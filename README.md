#TypeScript Notes

-TypeScript Simple Types
There are three main primitives in JavaScript and TypeScript.
boolean - true or false values
number - whole numbers and floating point values
string - text values like "TypeScript Rocks"
-Special Types
Type: any
any is a type that disables type checking and effectively allows all types to be used.
In reality, any time we call JSON parse, we get back a value of the any type.
-TypeScript Arrays
*Readonly
The readonly keyword can prevent arrays from being changed.
EX:
const names: readonly string[] = ["Dylan"];
names.push("Jack"); // Error: Property 'push' does not exist on type 'readonly string[]'.
// try removing the readonly modifier and see if it works?
-Type Inference
TypeScript can infer the type of an array if it has values.
-Type annotations
Code we add to tell Typescript what type of value a variable will refer to 
-Type inference 
Typescript tries to figure out what type of value a variable refers to 