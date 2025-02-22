varii Class Example
This repository contains a simple example of a varii class written in TypeScript, which demonstrates how to use classes, constructors, and object creation with parameters.

Class Overview
The varii class has two properties: x and y, both of type number. The class accepts two parameters (x and y) in its constructor, which are assigned to the respective class properties.

Class Definition
```
class varii {
    x: number;
    y: number;

    constructor(x: number, y: number) {
        this.x = x;
        this.y = y;
    }
}

```

The varii class allows you to create objects with x and y values passed during initialization.
Example Usage

```
const p1 = new varii(8, 9);
const p2 = new varii(6, 8);

console.log(p1); // Output: varii { x: 8, y: 9 }
console.log(p2); // Output: varii { x: 6, y: 8 }

console.log(`${p1.x}${p2.y}`); // Output: 88

```
In this example, two objects p1 and p2 are created with different values for x and y.
The final console.log outputs the value of p1.x and p2.y, which in this case will display 88.

...
varii { x: 8, y: 9 }
varii { x: 6, y: 8 }
88

...
