# VR.Viewer

VR.Viewer is a simple WebVR image viewer for Over under images. It is uses the magnificient A-Frame (https://aframe.io/).

## To use VR.Viewer there are 2 options

**by URL:**
https://yoursite/viewer.html?img=your-image-url
You can try or use it on www.architecturalrealities.com/viewer.html?img=your-image-url

If you want to use Onedrive:
- Select your image. 
- Choose embed in Onedrive and copy the URL.
- https://yoursite/viewer.html?img=PASTE-ONEDRIVE-EMBED-CODE-HERE

Make sure if you use www.architecturalrealities.com/viewer.html?img=your-image-url the server is CORS enabled.

**by loading the files:**
- Open https://yoursite/viewer.html or press this link www.architecturalrealities.com/viewer.html - 
- The site opens with a screen on which you can choose to load images local (works also on iPhone).
- If you choose upload the iamges are uploaded to Uploadcare. The viewer returns a URL that can be used to view the images.
- The images stay on Uploadcare for a month.

Have Fun!

## Roadmap

- a lot of code cleaning
- cubemaps
- tours (floating links using XML files)
- better load screen



