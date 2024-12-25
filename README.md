# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js applications where long-running requests can cause the server to hang.  The `server.js` file contains code that simulates a long-running task within a request handler. This blocks the event loop, preventing the server from responding to other requests.

The solution (`serverSolution.js`) provides an improved implementation using asynchronous operations, preventing the server from blocking.