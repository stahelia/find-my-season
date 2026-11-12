# Find my Season (class prototype)

A small prototype for a university course. It estimates a color season from a headshot photo.

- Photos are analyzed in the visitor's own browser. Nothing is uploaded, saved or sent.
- `index.html` is the home page. `find-my-season.html` is the page where a photo is added.
- Color palettes are from the concept wardrobe's season guides. Color codes were sampled from the guides' images, so they are close on-screen matches, not official values. The 12-season system is a convention, not a tested classification.
- Prototype only: results are an estimate, not professional advice.
- Face finding uses Google's MediaPipe Face Detector (BlazeFace short-range model), Apache License 2.0, running in the browser. The files are in the `vendor/mediapipe` folder.
