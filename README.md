# 🎯 Real-Time Object Detection App

Web application for real-time object detection using TensorFlow.js and the COCO-SSD model.

![Object Detection Demo](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)

## ✨ Features

- 🎥 Real-time detection via webcam
- 🖼️ Image upload and analysis
- 🏷️ Detects 80+ objects (people, animals, vehicles, everyday items)
- 📊 Live statistics (FPS, object count)
- 🎨 Modern and responsive interface

## 🚀 Installation

No installation required! It's a single HTML file.

```bash
# Clone the repo
git clone https://github.com/your-username/object-detection-app.git

# Open the file
open object-detection.html
```

Or use Live Server in VS Code for automatic reload.

## 💻 Usage

1. Open `object-detection.html` in your browser
2. Click **"Start Webcam"** for real-time detection
3. Or click **"Upload Image"** to analyze an image

The model automatically detects objects and displays:
- Green bounding boxes
- Labels with confidence percentage
- Number of detected objects

## 🎯 Detected Objects

The COCO-SSD model can identify 80 object categories including:
- 👤 People
- 🐕 Animals (dog, cat, horse, bird...)
- 🚗 Vehicles (car, bicycle, motorcycle, bus...)
- 🍌 Food (banana, apple, pizza...)
- 💺 Furniture and everyday objects

## 🛠️ Technologies

- TensorFlow.js 4.11.0
- COCO-SSD Model 2.2.3
- HTML5 Canvas
- WebRTC (getUserMedia)

## 📱 Compatibility

- ✅ Chrome / Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Works on Mac, Windows, Linux

## 📄 License

MIT

## 🤝 Contributing

PRs are welcome! Feel free to open an issue for any suggestions.

---

Made with ❤️ and TensorFlow.js
