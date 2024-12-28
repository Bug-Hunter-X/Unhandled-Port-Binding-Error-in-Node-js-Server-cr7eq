# Unhandled Port Binding Error in Node.js Server

This repository demonstrates a common error in Node.js:  failure to handle errors when binding to a port. The `bug.js` file shows a server that crashes silently if the specified port is already in use. The `bugSolution.js` file provides a corrected version with robust error handling.

## Problem

Node.js servers can fail to start gracefully if there's an issue binding to the specified port (e.g., the port is already in use by another process).  Without proper error handling, this leads to a server crash with minimal information.