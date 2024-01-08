# face-api-webcam-landmarks
Webcam Face Landmark Detection and show in on the video

# install and run
npm i

npm run start

start in port 3000
# how its work
dentro de `webcamfacelandmarkdetection.html`

When a smiling expression is detected, capture the image in base64 format.
```javascript
    if (isMouthOpen(result.expressions)) {
      // Capturar una instantánea del video cuando la persona está sonriendo
      capturarInstantanea(videoEl);
    }
```