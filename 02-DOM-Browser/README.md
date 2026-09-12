# 02 — DOM & Browser JavaScript

## Learn

- DOM tree
- Selecting elements
- Changing text, HTML and attributes
- Classes and styles
- Events and event listeners
- Event bubbling and delegation
- Forms and validation
- localStorage/sessionStorage
- JSON
- Timers
- Browser APIs

## Example

```js
const button = document.querySelector("#addToCart");
button.addEventListener("click", () => {
  console.log("Product added");
});
```

## Real Case: Cafe QR Ordering

A customer scans a QR code, sees menu cards and clicks **Add to Cart**. JavaScript listens to the click, updates the cart array, saves it to localStorage and refreshes the cart count.

## Exercises

1. Build a counter.
2. Build a dark/light mode switch.
3. Build a form with validation.
4. Build a product filter.
5. Build a shopping cart with localStorage.
6. Build a cafe menu with category tabs.

## Important Questions

- What is the DOM?
- `querySelector` vs `getElementById`?
- Event bubbling vs capturing?
- Why use event delegation?
- localStorage vs sessionStorage?

## Resources

- MDN DOM: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
- MDN Events: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Events
- MDN Web APIs: https://developer.mozilla.org/en-US/docs/Web/API
