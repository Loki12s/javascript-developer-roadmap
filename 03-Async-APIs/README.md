# 03 — Async JavaScript & APIs

## Learn

- Synchronous vs asynchronous code
- Callbacks
- Promises
- Promise states
- `.then()` / `.catch()` / `.finally()`
- `async` / `await`
- `try/catch`
- Fetch API
- HTTP methods and status codes
- JSON
- Parallel requests with `Promise.all`
- Loading and error states

## Example

```js
async function loadMenu() {
  try {
    const response = await fetch("/api/menu");
    if (!response.ok) throw new Error("Menu request failed");
    const menu = await response.json();
    console.log(menu);
  } catch (error) {
    console.error(error.message);
  }
}
```

## Real Case

When a cafe customer opens the menu, the browser sends a request to the server. The UI must show loading, wait for the response, display products, and show a useful error if the server is unavailable.

## Exercises

- Fetch a public API and display results.
- Add loading and error states.
- Fetch product and category data in parallel.
- Add retry behavior.
- Build a search page using query parameters.

## Interview Questions

- Why does JavaScript use asynchronous programming?
- Promise vs callback?
- What does `await` do?
- What happens when a promise rejects?
- `Promise.all` vs `Promise.allSettled`?
- What is the event loop?

## Resources

- MDN Promises: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
- MDN async function: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
- MDN Fetch: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
- Node.js Learn: https://nodejs.org/en/learn/asynchronous-work
- Video search — freeCodeCamp: https://www.youtube.com/@freecodecamp/search?query=async%20javascript
