# Realtime Attention Span Tracking using webgazer.js

This is a simple POC demo to show how we could calculate attention score with a ratio calculation using Webgazer.js

✨ **Features implemented** :

- Demonstration of Attention Span Detection using Webazer
- Gaze Prediction calculates eye focal point based on user eye tracking.
- Calculating attention score based on ratio of focus time and total time.
- Plotting attention score vs time using Canvas.js

## Project setup

The webgazer setup requires you to run this using a local server. A way to do this would be using [serve](https://www.npmjs.com/package/serve).

```
$ yarn global add serve

$ serve index.html
```

### Note

- During the first load, if your graph does not update automatically, clicking on the screen multiple times should fix it.
- To improve accuracy, look at a point on the screen while you drag you cursor to that point, and then click the point 5 times, and do it across different points in the screen.
