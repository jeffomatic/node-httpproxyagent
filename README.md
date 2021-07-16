# node-httpproxyagent

This is a NodeJS implementation of an HTTP/HTTPS proxy agent. Its goals are:

- Support the conventional suite of HTTP proxy environment variables, including `HTTP_PROXY`, `HTTPS_PROXY`, and `NO_PROXY`.
- Zero production dependencies.
- A clean, modern TypeScript implementation. Yes, this is quite subjective.

There are [many](https://www.npmjs.com/search?q=proxy agent) proxy agent implementations for NodeJS, but I couldn't find any that satisfy all three of the above.

## Usage