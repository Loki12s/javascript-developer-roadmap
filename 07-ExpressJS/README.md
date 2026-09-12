# 07 — Express.js

## Learn

- Express setup
- Routes
- Route parameters
- Query parameters
- Middleware
- Request/response
- Controllers
- Validation
- Error handling
- REST conventions
- Project structure

## Example

```js
app.get("/api/menu", async (req, res, next) => {
  try {
    const items = await getMenuItems();
    res.json(items);
  } catch (error) {
    next(error);
  }
});
```

## Real Case

A cafe app needs `/api/menu`, `/api/orders`, `/api/orders/:id` and `/api/users/login`. Express handles routing and middleware while the application logic talks to the database.

## Exercises

- Build CRUD for tasks.
- Add validation middleware.
- Add centralized error handling.
- Add request logging.
- Build cafe menu CRUD.

## Resources

- Express install: https://expressjs.com/en/starter/installing.html
- Basic routing: https://expressjs.com/en/starter/basic-routing.html
- Middleware: https://expressjs.com/en/guide/using-middleware.html
- Error handling: https://expressjs.com/en/guide/error-handling.html
