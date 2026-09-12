# 01 — JavaScript Fundamentals

## Topics

1. Variables: `let`, `const`, `var`
2. Primitive and reference values
3. Strings and template literals
4. Numbers and type conversion
5. Boolean logic
6. Operators
7. `if`, `else`, `switch`
8. Loops
9. Functions and parameters
10. Return values
11. Arrays and array methods
12. Objects and destructuring
13. Spread/rest
14. Optional chaining and nullish coalescing
15. Scope and hoisting
16. Closures
17. `this`
18. Error handling
19. ES modules

## Simple Example

```js
const price = 250;
const quantity = 2;
const total = price * quantity;
console.log(`Total: ₹${total}`);
```

## Real Case: Cafe Order

A cafe order can be represented as:

```js
const order = {
  id: 101,
  customer: "Sahil",
  items: [
    { name: "Cold Coffee", price: 120, quantity: 2 },
    { name: "Sandwich", price: 160, quantity: 1 }
  ]
};

const total = order.items.reduce(
  (sum, item) => sum + item.price * item.quantity,
  0
);

console.log(total);
```

This single example connects objects, arrays, functions, callbacks and `reduce`.

## Practice

### Beginner
- Make a calculator for two numbers.
- Check whether a number is even or odd.
- Print numbers from 1 to 100.
- Find the largest number in an array.
- Count vowels in a string.

### Intermediate
- Create a shopping cart using an array of objects.
- Calculate subtotal, discount and GST.
- Group products by category.
- Write a function that safely handles missing values.
- Build a menu search function.

### Debugging
Intentionally create errors involving `undefined`, incorrect types and off-by-one loop conditions. Read the error before fixing it.

## Interview Questions

- Difference between `let`, `const` and `var`?
- Primitive vs reference values?
- What is hoisting?
- What is a closure?
- `==` vs `===`?
- `map()` vs `filter()` vs `reduce()`?
- What is scope?
- What does `this` mean?

## Resources

- MDN Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
- MDN Reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
- Video search — freeCodeCamp: https://www.youtube.com/@freecodecamp/search?query=javascript

## Completion Test

Build a console-based **Cafe Billing System** that accepts products, quantities, discount and tax, then prints an invoice. Do it without copying a solution.
