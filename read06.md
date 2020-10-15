# NODE JS

*event based, non-blocking, asynchronous I/O*

- Built into Chrome V8 JS Engine
    - [More Info about V8](https://v8.dev/)

- Chromium based browsers, Opera, Brave, Vivaldi.
- Aren't executable in browser
- Enhanced V8 with various features:
    - file system API
    - HTTP Library 
    - OS related utility methods
- Included with npm


## Node JS has good modern JS support
- [Support Tables](https://node.green/)
## What is Node JS Used for?
- automate building applications in JS
- Bundling JS files
- dependencies into static assets
- running tests
- automatic linting and style checking

*Expected to know node, and npm*  

- Don't really need node for back end to run frameworks
- many packages rely on node to run and are available on npm.

## Running on a server
- Node is used by a bunch of high profile companies
- first attepmted by netscape

## Execution Model   
- Each connection spawns new thread to handle the request
- database runs code and server waits
- Single Threaded
- everything that happens in Node is in reaction to an event
    - event-driven

## Downsides
- Single threaded so heavy CPU operations shouldn't be run
- some devs don't like the call-back style of coding.

## What kinds of apps?
- Real time collboration
- Chat
- codeshare type 

