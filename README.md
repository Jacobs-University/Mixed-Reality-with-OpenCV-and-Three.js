# Mixed-Reality-With-OpenCV-and-Three.js
**Idea**: create a mixed reality experience where a virtual light in a 3D scene is controlled in real-time by tracking the movement and orientation of a real object from a webcam stream.

The following packages are required: **numpy, opencv, SimpleWebSocketServer1**
1. run `pip install -r requirements.txt`
2. Before running anything, print chessboard.svg or save it on your phone.
3. run server.py and then open index.html in your browser.
4. Hold the pattern (chessboard.svg) and bring it close to the camera. A window with the webcam feed (with the 3D axes overlayed on top) should pop up. Now, you should be able to control the light in the scene by moving the pattern. 

![interface](./demo/test.PNG)
