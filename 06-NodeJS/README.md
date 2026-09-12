# 06 — Node.js

## Learn

- What Node.js is
- V8 and the runtime
- npm and package.json
- CommonJS vs ES modules
- Built-in modules
- `fs`, `path`, `url`
- Environment variables
- HTTP server
- Event loop basics
- Streams basics
- Debugging

## Example

```js
import { readFile } from "node:fs/promises";

const data = await readFile("menu.json", "utf8");
console.log(JSON.parse(data));
```

## Real Case

The cafe backend needs to read configuration, receive HTTP requests, access a database and return JSON. Node.js provides the runtime for that server-side JavaScript.

## Exercises

- Build a CLI calculator.
- Read/write a JSON file.
- Build a simple HTTP server.
- Create a CLI expense tracker.
- Create a small menu API without Express.

## Resources

- Node.js Learn: https://nodejs.org/en/learn
- Node.js API docs: https://nodejs.org/docs/latest/api/
- npm docs: https://docs.npmjs.com/
- Video search — freeCodeCamp: https://www.youtube.com/@freecodecamp/search?query=nodejs
