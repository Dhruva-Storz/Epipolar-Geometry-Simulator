# Epipolar Geometry Simulator

While solidifying my basics on stereo camera geometry, I found it difficult to gain an intuition for the different kinds of epipolar patterns that come from perturbations of camera geometry from the ideal, and how the simple application of a homography matrix to the stereo images can correct for these perturbations to rectify a pair of stereo images. So, as a visual learner, I made this tool with claude code to gain a better intuition. 

This is an interactive 3D visualization tool for understanding epipolar geometry, the fundamental constraint that makes stereo vision and 3D reconstruction possible.

## Features

- **Interactive 3D Scene**: Orbit around the scene to see how two cameras view a 3D object
- **Real-time Epipolar Lines**: Watch how epipolar lines change as cameras move
- **Camera Presets**: Explore different stereo configurations:
  - Ideal (parallel cameras)
  - Toe-In (converging cameras)
  - Vertical Offset
  - Roll/Pitch errors
  - Cameras facing each other
- **Manual Rectification**: Apply homography transformations to understand the rectification process. Watch the values of the homography matrix change as you apply different transforms. 
- **Visual Epipolar Planes**: See the 3D planes connecting camera centers and scene points

## Technologies

- [Three.js](https://threejs.org/) - 3D graphics library
- WebGL - Hardware-accelerated rendering
- HTML5 Canvas - 2D overlays for epipolar lines

## Credits

- **Dhruva Gowda Storz** - Project Creator
- **Claude Opus 4.5 (Anthropic)** - AI Programming Assistant
- **Juan** ([juane3d on Sketchfab](https://sketchfab.com/juane3d)) - Thai Mask 3D Model

### 3D Model Attribution

This work uses "[Thai Mask](https://sketchfab.com/3d-models/thai-mask-79da9d12d8f94fec88ca4d158211fa37)" by [Juan](https://sketchfab.com/juane3d) licensed under [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

## 📄 License

This project is open source. The 3D model has its own CC-BY-4.0 license (see `thai_mask/license.txt`).

**Note**: This application requires WebGL support and is optimized for desktop browsers with mouse controls.
