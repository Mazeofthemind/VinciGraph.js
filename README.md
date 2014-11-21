Vinci-Graph-Visualization (0.1)
=========================

===Introduction===
This is a reference visualization which receives graph data (vertices and edges) in JSON form either from a server or flat file (on the client computer) and visualizes it in the browser. It is intended to be used as a component of other web applications rather then as a standalone application.

The Morse Graph Visualization provides both 2D (D3.js with SVG rendering) and 3D (Three.js with either Canvas or WebGL rendering) options for visualizing data and provides a variety of static (radial tree based) and dynamic (force based) arrangement algorithms.

The visualization also allows users to associate visual attributes (color, size, shape) with data attributes through its interface. This includes assigning an individual visual attribute using a rule (element.data.x == y so element.color = purple) or dynamically mapping an array of visual attributes to a data attribute (for every unique value of data.x assign a unique color).

All of a users settings and visual attributes are cached on the browser and can also be imported/exported from a flat file.

===Compatability===
Vinci Graph Visualization (0.1) has only been tested on Firefox 31-33

===Example Server===
The first version of the Morse Graph Visualization uses the Python built in SimpleHTTPServer

===External Libraries Used===
-Three.js (http://threejs.org/)
-D3.js (http://d3js.org/)
-Bootstrap (http://getbootstrap.com/)
-React.js (http://facebook.github.io/react/)
