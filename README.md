VinciGraph.js (0.1)
===

Introduction
---
This is a reference visualization which receives graph data (vertices and edges) in JSON form either from a server or flat file (on the client computer) and visualizes it in the browser. It is intended to be used as a component of other web applications rather then as a standalone application.

Features
---
* 2D (D3.js with SVG rendering) and 3D (Three.js with either Canvas or WebGL rendering) rendering
* static (radial tree based) and dynamic (force based) arrangement algorithms
* Customizable highlighting and filtration rules for data attributes
* Dynamic highlighting for numeric (heatmapping) and categorical sets

API
---
VinciGraph is designed to accept graphs either uploaded as a file or from a server in the GraphSON format defined as part of the TinkerPop Blueprints stack. GraphSON and related libraries are available at https://github.com/tinkerpop/blueprints/wiki/GraphSON-Reader-and-Writer-Library.

Browser Compatability
---
VinciGraph.js (0.1) has only been tested on Firefox 31-33

Example Backend
---
As an example of how VinciGraph would be used with a backend server, this version comes with an Vert.x backend that provides REST and 

External Libraries Used
---
* Three.js (http://threejs.org/)
* D3.js (http://d3js.org/)
* Bootstrap (http://getbootstrap.com/)
* React.js (http://facebook.github.io/react/)

Web Standards Used 
---
* WebSockets: https://developer.mozilla.org/en-US/docs/WebSockets
* WebWorkers: https://developer.mozilla.org/en-US/docs/Web/Guide/Performance/Using_web_workers
* WebGL: https://developer.mozilla.org/en-US/docs/Web/WebGL
* SVG: https://developer.mozilla.org/en-US/docs/Web/SVG
* ASM.js: http://asmjs.org/
