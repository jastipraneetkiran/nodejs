# Node JS Essential

## Node JS
It is JavaScript on backend Server .......
- Javascript on server is done by some virtual machine(VM) Like V8 or Chakra and node js is a wrapper which uses this viortual machine to proceed with the exection of code on server.
- A wrapper around V8 with built-in modules providing rich features through easy-to-use asynchronous APIs
- C++ Addons
- Debugger and other utilities
- NPM 
- Module dependancy Manager
- There are Multiple built in modules in Node which uses Asynchronous API's (no  Threads)


|Module|	Description|
|------|:-----------:|
|assert |Provides a set of assertion tests|
|buffer	|To handle binary data|
|child_process|	To run a child process|
|cluster|	To split a single Node process into multiple processes|
|crypto	|To handle OpenSSL cryptographic functions|
|dgram|	Provides implementation of UDP datagram sockets|
|dns	|To do DNS lookups and name resolution functions|
|domain|	Deprecated. To handle unhandled errors|
|events	|To handle events|
|fs|	To handle the file system|
|http|	To make Node.js act as an HTTP server|
|https|	To make Node.js act as an HTTPS server.|
|net|	To create servers and clients|
|os|	Provides information about the operation system|
|path|	To handle file paths|
|punycode|	Deprecated. A character encoding scheme|
|querystring|	To handle URL query strings|
|readline|	To handle readable streams one line at the time|
|stream|	To handle streaming data|
|string_decoder|	To decode buffer objects into strings|
|timers	|To execute a function after a given number of milliseconds|
|tls|	To implement TLS and SSL protocols|
|tty|	Provides classes used by a text terminal|
|url|	To parse URL strings|
|util|	To access utility functions|
|v8|	To access information about V8 (the JavaScript engine)|
|vm|	To compile JavaScript code in a virtual machine|
|zlib|	To compress or decompress files|

Node is a popular for two reasons:

- Node ships with a reliable package manager (NPM) and it works with the NPM registry (hosted at npmjs.com). Using the NPM CLI, it is very easy install a package from the many available in the registry.

- Node has reliable module dependency managers ("CommonJS" modules and ECMAScript modules). For CommonJS modules, this is basically the "require" function in Node combined with the "module" object. For ECMAScript modules, dependencies are managed with the import/export JavaScript syntax

