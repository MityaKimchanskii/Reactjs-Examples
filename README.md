# Reactjs-Examples

npm install -g npm-check-updates
ncu -u


npm install
npm start

------------------------------------------------------------------------


Then:

npm start

npx create-react-app my-app

npm start - Starts the development server.

npm run - build Bundles the app into static files for production.

npm test - Starts the test runner.

npm run eject - Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

cd my-app
npm start

-----------------------------------------------------------------------

import React from "react";
import { render } from "react-dom";
 
render(
  <div>
    <h1>Hello World!</h1>
    <p>This is a paragragh</p>
  </div>,
  document.getElementById("root")
);

-----------------------------------------------------------------------
const React = require("react");
const ReactDOM = require("react-dom/client");

// During an update, there is no need to pass the container again
const container = document.getElementById("root");
 
// Create a root.
const root = ReactDOM.createRoot(container);
 
// Initial render
root.render(<h1>Hello World</h1>);

-----------------------------------------------------------------------

import React from "react";
import { createRoot } from "react-dom/client";
 
const container = document.getElementById("root");
const root = createRoot(container);
 
root.render(<h1>Hello World</h1>);

-----------------------------------------------------------------------

 

