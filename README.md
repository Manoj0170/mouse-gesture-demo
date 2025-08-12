# 🖐️ Hand Gesture Mouse Control

> **Live Demo:** [https://your-username.github.io/mouse-gesture-demo](https://your-username.github.io/mouse-gesture-demo)

A real-time web application that enables computer mouse control using hand gestures captured through a webcam. Built with MediaPipe, TensorFlow.js, and advanced computer vision algorithms.

![Hand Gesture Demo](https://img.shields.io/badge/Demo-Live-brightgreen) ![Browser Support](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 **[Try the Live Demo →](https://your-username.github.io/mouse-gesture-demo)**

## ✨ Features

### 🎮 **5 Core Gesture Functions**
- **Stay at Rest** - Hand relaxation position (Golden cursor)
- **Mouse Move** - Navigate cursor around screen (Green cursor)  
- **Left Click** - Primary selection action (Red cursor)
- **Right Click** - Context actions/erase mode (Blue cursor)
- **Scroll** - Scroll content up/down (Purple cursor)

### 🎯 **Interactive Activities**
- **🎨 Drawing Canvas** - Create digital artwork using gestures
- **📜 Scroll & Click Test** - Practice accuracy with interactive buttons
- **📹 Camera View** - Real-time hand tracking visualization

### 🎓 **Machine Learning Tools**
- **Gesture Trainer** - Train custom gesture recognition models
- **Gesture Tester** - Test and validate trained models
- **k-NN Classification** - Advanced feature extraction and learning

### ⚡ **Advanced Technology**
- **Multi-layer Smoothing** - Eliminates hand tracking jitter
- **Perfect Cursor Continuity** - No jumps between gestures
- **Real-time Processing** - 30 FPS gesture recognition
- **Cross-browser Compatibility** - Works on all modern browsers

## 🎯 Quick Start

### **Option 1: Use Live Demo (Recommended)**
1. Visit: **[Live Demo Link](https://your-username.github.io/mouse-gesture-demo)**
2. Click **"Activities Center"** for the main experience
3. Grant camera permission when prompted
4. Raise your hand and start controlling the cursor!

### **Option 2: Run Locally**
1. Clone this repository
2. Open `index.html` in a modern web browser
3. Grant camera permissions
4. Start using gesture control!

```bash
git clone https://github.com/your-username/mouse-gesture-demo.git
cd mouse-gesture-demo
# Open index.html in your browser
```

## 🖥️ Browser Requirements

- **Chrome 88+** (Recommended)
- **Firefox 85+**
- **Safari 14+** 
- **Edge 88+**
- **HTTPS required** for camera access (auto-enabled on GitHub Pages)

## 🎨 How to Use

### **Basic Gesture Control:**
1. **Navigate** - Point with your index finger to move cursor
2. **Click** - Make a fist to click at cursor position
3. **Draw** - Hold fist gesture while moving to draw lines
4. **Erase** - Peace sign gesture to erase/right-click
5. **Rest** - Open palm to keep cursor stationary

### **Training Custom Gestures:**
1. Open **Gesture Trainer**
2. Configure 2-10 custom gestures
3. Record 50+ samples per gesture
4. Train the model and download
5. Load model in **Activities Center** for use

## 🏗️ Technical Architecture

### **Technology Stack:**
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Computer Vision:** MediaPipe Hands (Google)
- **Machine Learning:** ml-matrix library, k-NN classification
- **Real-time Processing:** WebRTC, Canvas 2D API
- **Deployment:** Static hosting (GitHub Pages compatible)

### **Performance Characteristics:**
- **Frame Rate:** 30 FPS gesture processing
- **Latency:** <50ms gesture-to-action response
- **Loading:** 2-3 seconds initial load
- **Memory:** Efficient MediaPipe integration

### **Smoothing Pipeline:**
```
Raw MediaPipe Data → Rolling Average → Deadzone Filter → EMA Smoothing → Cursor Position
```

## 📱 Demo Screenshots

*[Add screenshots of your app in action here]*

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **MediaPipe** by Google for hand tracking technology
- **ml-matrix** for machine learning utilities
- **GitHub Pages** for free hosting
- The open-source community for inspiration and tools

## 📞 Contact

- **Demo:** [https://your-username.github.io/mouse-gesture-demo](https://your-username.github.io/mouse-gesture-demo)
- **Repository:** [https://github.com/your-username/mouse-gesture-demo](https://github.com/your-username/mouse-gesture-demo)
- **Issues:** [Report bugs or request features](https://github.com/your-username/mouse-gesture-demo/issues)

---

⭐ **Star this repository if you found it useful!**

🖐️ **Built with gesture recognition technology - Control your computer with just hand movements!**