# Difference Between OOP and Functional Programming in JavaScript

### OOP:
```javascript
// Creating a class and objects using OOP

class Rectangle {
  constructor(width, height) {
    this.width = width;
    this.height = height;
  }

  calculateArea() {
    return this.width * this.height;
  }
}

const rectangle1 = new Rectangle(5, 10);
console.log(rectangle1.calculateArea()); // Output: 50
```
### FP:
```javascript
// Using functional programming to calculate the area of a rectangle

function calculateArea(width, height) {
  return width * height;
}

const width = 5;
const height = 10;
const area = calculateArea(width, height);
console.log(area); // Output: 50
```

## 4 Fundamental Principles of Object-Oriented Programming:
- Abstraction
- Encapsulation
- Inheritance
- Polymorphism
