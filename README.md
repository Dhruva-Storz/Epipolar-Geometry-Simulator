# Epipolar Geometry Simulator

An interactive 3D visualization tool for understanding epipolar geometry, the fundamental constraint that makes stereo vision and 3D reconstruction possible.

![Screenshot](https://via.placeholder.com/800x400?text=Epipolar+Geometry+Simulator)

## 🎯 Features

- **Interactive 3D Scene**: Orbit around the scene to see how two cameras view a 3D object
- **Real-time Epipolar Lines**: Watch how epipolar lines change as cameras move
- **Camera Presets**: Explore different stereo configurations:
  - Ideal (parallel cameras)
  - Toe-In (converging cameras)
  - Vertical Offset
  - Roll/Pitch errors
  - Cameras facing each other
- **Manual Rectification**: Apply homography transformations to understand the rectification process
- **Visual Epipolar Planes**: See the 3D planes connecting camera centers and scene points

## 🚀 Live Demo

[Try the Simulator](https://yourusername.github.io/epipolar-geometry-simulator/)

## 📖 Learn More

The [Info Page](info.html) includes:
- Theory of epipolar geometry
- Explanation of stereo rectification
- The fundamental and essential matrices
- Further reading recommendations

## 🛠️ Technologies

- [Three.js](https://threejs.org/) - 3D graphics library
- WebGL - Hardware-accelerated rendering
- HTML5 Canvas - 2D overlays for epipolar lines

## 👏 Credits

- **Dhruva Gowda Storz** - Project Creator
- **Claude Opus 4.5 (Anthropic)** - AI Programming Assistant
- **Juan** ([juane3d on Sketchfab](https://sketchfab.com/juane3d)) - Thai Mask 3D Model

### 3D Model Attribution

This work uses "[Thai Mask](https://sketchfab.com/3d-models/thai-mask-79da9d12d8f94fec88ca4d158211fa37)" by [Juan](https://sketchfab.com/juane3d) licensed under [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

## 📄 License

This project is open source. The 3D model has its own CC-BY-4.0 license (see `thai_mask/license.txt`).

## 🖥️ Local Development

Simply open `index.html` in a modern web browser. For the best experience, use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 📱 Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari

**Note**: This application requires WebGL support and is optimized for desktop browsers with mouse controls.
