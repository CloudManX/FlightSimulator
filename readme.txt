This Webgl application accomplishes a simple flight simulator by utilizing diamond-square algorithm to generate terrain and quaternion rotation matrix to represent a camera. It is built on the given files hello-terrain from the course webpage. The diamond-square algorithm is implemented by a recursion on an array that stores the vertexes of the map. The general strategy is to divide the terrain into 4 parts every time until the size reaches 1. The camera is implemented by rotating view direction and up vector whenever the user is pressing a corresponding key(w, a ,s, d). To see the demo, it can be viewed by just opening the Terrain.html file. There is no other specific requirement.

Files in the folder
Terrain.html
Terrain.js
terrainModeling.js
gl-matrix-min.js
webgl-util.js