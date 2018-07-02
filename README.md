# pose-tfjs-p5
Realtime pose estimation in the browser examples using tensorflow.js and p5.js. 

Made using [this tutorial](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5).

Tensorflow.js, the posenet model and p5.js are simply loaded from a CDN. To run the example, just open index.html in a modern browser (works in Chrome, haven't checked others). You'll probably have to serve it from a local development server (e.g. [node's http-server](https://www.npmjs.com/package/http-server) or [python's http.server](https://docs.python.org/3.7/library/http.server.html?highlight=server#module-http.server) or [xampp](https://www.apachefriends.org/index.html)) because of cross-origin problems, or online through https.
