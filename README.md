# 🎨 Normal Map Studio
Normal Map Studio is an advanced, fully client-side web tool that transforms any 2D texture into a professional-grade Normal Map. It provides a fast and efficient solution for game developers, 3D artists, and designers directly in the browser.
✨ Key Features
* 🚀 Instant Processing: Preview all changes in real-time as soon as an image is uploaded.
* 🛠️ Advanced Controls:
   * Strength: Fine-tune surface depth with a precise range from 0.1 to 10.0.
   * Blur (Pre-process): Smooth out noisy textures to achieve cleaner, more stable normal maps.
   * Sharpness: Use advanced sharpening filters to emphasize micro-surface details.
   * High Detail Mode: Maximize detail levels using specialized edge-detection algorithms.
* 🔄 DirectX & OpenGL Support: Toggle the Green (G) channel with a single click to ensure compatibility with your target engine (Unreal Engine, Unity, Blender, etc.).
* 🔍 Smart Viewport: Inspect details even on 4K textures with intuitive left-click dragging (pan) and scroll-wheel zooming.
* 📂 Privacy Focused: All processing happens locally in your browser; your images are never uploaded to any server.
🚀 How to Use
1. Upload Image: Drag an image into the Input Texture area or click to select a file.
2. Adjust Settings: Use the sidebar sliders to modify depth, blur, and sharpness parameters.
3. Select Format: Choose between OpenGL or DirectX mode based on your workflow requirements.
4. Preview & Navigate: Use the viewport to inspect the generated map and pan/zoom to check specific areas.
5. Export: Click the "Export Normal Map" button to download your high-quality PNG file.
🛠️ Technical Details
This project is built using modern web technologies and mathematical image processing techniques:
* Luminance Conversion: Images are converted to a Height Map using weighted luminance: $0.299R + 0.587G + 0.114B$.
* Sobel Operator: X and Y derivatives are calculated using Sobel/Scharr filtering for accurate gradient computation.
* Performance: Uses low-level data structures like Uint8ClampedArray and Float32Array for high-performance processing of large textures.
* UI: Designed with a sleek, dark-themed interface using Tailwind CSS.
📦 Installation
No installation is required to run this project locally:
1. Clone the repository:
git clone [https://github.com/Sroxyn/Normal-Map-Generator.git](https://github.com/Sroxyn/Normal-Map-Generator.git)

2. Open index.html in your preferred web browser.
📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.
🤝 Contributing
Contributions are welcome! Please open an Issue or submit a Pull Request for any bug reports or feature suggestions.
Developed with ❤️ by [Sroxyn]
