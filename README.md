# Photo Motion Studio

A free, static photo-animation website designed for mobile Chrome. It creates 20-second camera-motion videos in the browser. It does not run an AI image-to-video model; realistic body movement requires a separate model/service and free access to those services is not guaranteed.

## Deploy to Render for free
1. Create a new public GitHub repository, for example `photo-motion-studio`.
2. Upload `index.html` from this folder to the repository root.
3. In Render, choose **New + → Static Site**, connect the repository, and deploy.
4. Leave Build Command blank. Set Publish Directory to `.` (a single dot).
5. Keep the service on the free Static Site option. No backend or environment variables are needed.

## Use on Android
Open the Render URL in Chrome, choose a photo, select a motion style and format, then tap **Create 20-second video**. The browser records WebM in supported browsers, despite the button's MP4 wording. Save the resulting WebM file to your phone. If you need MP4 specifically, convert the WebM using a trusted local/offline converter.

## Notes
- The photo is processed in your browser and is not uploaded by this code.
- Video export can be memory-intensive on phones; use a reasonably sized image.
- Render free web services can sleep, but static sites are the simplest free hosting choice.
- Do not add this project to your existing Whiplash bot repository; keep it separate.
