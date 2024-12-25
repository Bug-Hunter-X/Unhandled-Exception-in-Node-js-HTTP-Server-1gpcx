# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and provides a solution.

## Bug

The original code lacks error handling, leading to an unhandled exception if an error occurs during request processing. This can cause the server to crash unexpectedly.

## Solution

The solution adds error handling using a `try...catch` block within the request listener.  This prevents the server from crashing and allows for graceful handling of errors.
