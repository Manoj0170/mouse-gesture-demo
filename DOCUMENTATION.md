# 🖐️ Dynamic Gesture Mouse Control System

## 🎯 Project Overview

This is a **Dynamic Multi-Pose Gesture Mouse Control System** that transforms your webcam into a powerful mouse controller using AI-powered gesture recognition. The system supports three detection methods:

- **Hand Detection** (21 landmarks) - Traditional finger gesture control
- **Body Pose** (33 landmarks) - Full body gesture control  
- **Holistic** (100+ landmarks) - Combined face + hands + body control

## 🚀 Key Features

- **🔄 Dynamic Adaptation** - Automatically switches between pose types
- **🎯 High Accuracy** - Professional-grade smoothing and recognition  
- **🖥️ Real-time Control** - Sub-50ms latency for responsive interaction
- **🎨 Visual Feedback** - Clear indication of current gesture state
- **⚙️ Customizable** - Adjustable sensitivity and smoothing parameters

## 🎮 The 5 Core Mouse Functions

Every gesture maps to one of these essential mouse actions:

| Function | Purpose | Visual Indicator |
|----------|---------|------------------|
| **Stay at Rest** | Relaxation position | 🟡 Golden cursor |
| **Mouse Move** | Navigate cursor | 🟢 Green cursor |
| **Left Click** | Primary selection | 🔴 Red cursor |
| **Right Click** | Context actions | 🔵 Blue cursor |
| **Scroll** | Scroll content | 🟣 Purple cursor |

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI**: MediaPipe + TensorFlow.js
- **Vision**: Real-time pose/hand detection
- **ML**: k-NN classification with feature extraction

## 📁 Project Structure

```
mouse-gesture-demo/
├── index.html                 # 🏠 Navigation hub
├── gesture-trainer.html       # 🎓 Model training
├── gesture-tester.html        # 🧪 Model testing  
├── activities-center.html     # 🎮 Main application
├── files/
│   ├── default_gesture_model.json
│   └── default_mapping.json
├── DOCUMENTATION.md           # 📖 This documentation
├── README.md                  # 📋 Quick guide
└── LICENSE                    # License information
```

## 🔄 How It Works

### Train → Test → Use
1. **Train**: Select pose type, record gesture samples, train AI model
2. **Test**: Load model, verify accuracy with real-time predictions
3. **Use**: Control mouse with drawing, clicking, scrolling activities

## 🎨 Available Activities

### 🎨 Drawing Canvas
- Precision drawing with gesture control
- Color picker and brush size adjustment
- Real-time parameter tuning

### 📜 Scroll & Click Test  
- Interactive buttons for click testing
- Scrollable content areas
- Performance tracking

### 📹 Camera View
- Live pose detection visualization
- Landmark display with color coding
- Real-time gesture feedback

## 🚀 Getting Started

### For End Users:
1. Open `activities-center.html`
2. Load a pre-trained model
3. Start using gesture control immediately

### For Developers:
1. Open `gesture-trainer.html`  
2. Select your preferred pose detection type
3. Train custom gestures for your application
4. Integrate the model into your project

## ⚙️ Configuration & Tuning

### Smoothing Parameters (Real-time adjustable)
- **Buffer Size**: 3-10 frames (Best: 5)
- **EMA Alpha**: 0.1-0.9 (Best: 0.30)
- **Deadzone**: 0.001-0.010 (Best: 0.003)
- **Sensitivity**: 1.0-5.0 (Best: 2.5)
- **Gesture Frames**: 1-10 (Best: 3)
- **Scroll Threshold**: 0.003-0.020 (Best: 0.008)

## 📊 Performance

- **Frame Rate**: 30 FPS pose processing
- **Latency**: Sub-50ms gesture-to-action  
- **Accuracy**: >95% with proper training
- **Compatibility**: All modern browsers

## 🔧 Requirements

- **Browser**: Chrome, Firefox, or Safari (latest versions)
- **Camera**: Webcam access required
- **Connection**: Internet (for MediaPipe CDN)
- **Performance**: Modern computer (for real-time processing)

## 🎯 Use Cases & Potential Applications

### Current Applications
- **Accessibility** - Alternative input method for users with limited mobility
- **Presentation** - Hands-free presentation control
- **Gaming** - Gesture-based game interfaces
- **Art/Design** - Touch-free creative applications
- **Research** - Human-computer interaction studies

### Future Potential
- **Medical Applications** - Sterile environment interaction
- **Industrial Control** - Hands-free equipment operation
- **Education** - Interactive learning experiences
- **Smart Home** - Gesture-based home automation
- **Virtual Reality** - Enhanced VR interaction
- **Automotive** - In-car gesture control systems

## 💡 Pro Tips

- **Training**: Record 50+ samples per gesture for best accuracy
- **Lighting**: Ensure good lighting for better pose detection
- **Background**: Plain backgrounds improve detection quality
- **Gestures**: Make distinct, repeatable movements
- **Tuning**: Adjust smoothing parameters for your preference

## 🔍 Troubleshooting

- **Camera not working**: Check browser permissions
- **Poor recognition**: Ensure good lighting and distinct gestures
- **Slow performance**: Try hand detection instead of holistic
- **Cursor jumping**: Increase smoothing parameters

---

**🎯 Ready to control your computer with just gestures? Open `index.html` and get started!**