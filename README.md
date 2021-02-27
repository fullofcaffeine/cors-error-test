# What

This project can be used to test cross-origin error-reporting behavior across browsers. Providing it's correctly configured, it should serve a JS script from a different domain. It also listens to the global error event and logs its event object to the console for inspection.

# Setup

1. Install `http-server`: npm install --g http-server;
1. Setup `cross.origin` to map to 127.0.0.1 in your local hosts file;
1. cd into this dir and start a web server: `http-server -p 3000`;
1. Open the browser you want to test on and load `http://localhost:3000`;
1. Open the JS inspector and inspect the logged event error object.
