# 10 — Authentication & Security

## Learn

- Authentication vs authorization
- Password hashing
- Sessions and cookies
- JWT concepts
- Access control
- Input validation
- CORS
- HTTPS
- Environment variables
- SQL injection
- XSS
- CSRF basics
- Rate limiting basics

## Real Case

In the cafe app, a customer can create an order, but only an authenticated staff member should change the order status. Authorization must be checked on the server, not only hidden in the frontend.

## Practice

Build login/register endpoints, hash passwords, issue a session or token, protect an order-management endpoint, and return safe errors.

Never store passwords in plain text and never commit secrets to Git.

## Resources

- OWASP Top 10: https://owasp.org/www-project-top-ten/
- MDN HTTP authentication: https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Authentication
- Node.js security: https://nodejs.org/en/learn/getting-started/security-best-practices
