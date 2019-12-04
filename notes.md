_"Refactoring"_

## Middleware

There are two types
- normal
- error handling

Can come from different sources:

- built-in: included with express
- third party: need to be installed separately
- custom: we write it!

We can use it:

- globally
- locally

Middleware can:

- inspect the `request` and `response` objects
- make changes to the `request` and response `objects`
- move the `request` or `response` object to the _next_ middleware in the queue
- stop the request and send back a response to the client

** order matters! **