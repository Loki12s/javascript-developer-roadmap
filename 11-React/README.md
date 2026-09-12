# 11 — React

Start React only after you are comfortable with JavaScript functions, arrays, objects, modules and async/await.

## Learn

- Components
- JSX
- Props
- State
- Events
- Conditional rendering
- Lists and keys
- Forms
- Lifting state
- `useState`
- `useEffect`
- Context basics
- Custom hooks basics
- API integration
- Loading/error states
- Component design

## Example

```jsx
function ProductCard({ product, onAdd }) {
  return (
    <article>
      <h3>{product.name}</h3>
      <p>₹{product.price}</p>
      <button onClick={() => onAdd(product)}>Add to cart</button>
    </article>
  );
}
```

## Real Case: Cafe Cart

The menu page receives products from an API. A user clicks Add to Cart. React state updates the cart, the cart count changes, and checkout receives the selected items.

## Exercises

- Counter
- Todo app
- Product search
- Shopping cart
- Cafe menu
- Login form
- API-powered order dashboard

## Resources

- React Learn: https://react.dev/learn
- React Tic-Tac-Toe tutorial: https://react.dev/learn/tutorial-tic-tac-toe
- React API reference: https://react.dev/reference/react
