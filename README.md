# Hand-gesture AI Challenge: Rock-Paper-Scissors 🎮

A real-time AI-powered Rock-Paper-Scissors game using computer vision for hand gesture recognition.

![Game Interface](media/image6.png)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technical Requirements](#technical-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [System Architecture](#system-architecture)
- [Performance](#performance)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview
This project implements an interactive Rock-Paper-Scissors game that uses computer vision for real-time hand gesture recognition and features an AI opponent. Players can play the classic game using natural hand gestures, competing against an intelligent computer opponent.

### Demo
![Gameplay Demo](media/image4.png)

## ✨ Features
- Real-time hand gesture recognition
- Intelligent AI opponent with adaptive gameplay
- Interactive user interface with live scoring
- Performance optimization for smooth gameplay
- Support for various lighting conditions
- Comprehensive error handling and recovery

## 💻 Technical Requirements

### Hardware Requirements
- CPU: Intel Core i5 8th Gen or equivalent
- RAM: 8GB minimum
- Webcam: 720p capable
- Storage: 500MB free space

### Software Requirements
```python
dependencies = {
    "python": "3.9.7",
    "opencv-python": "4.5.4",
    "pygame": "2.1.2",
    "tensorflow": "2.7.0",
    "numpy": "1.21.2",
    "mediapipe": "0.8.9.1"
}
```

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rps-ai-game.git
cd rps-ai-game
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure camera settings:
```bash
python setup.py configure
```

## 🎮 Usage

1. Start the game:
```bash
python main.py
```

2. Game Controls:
- Press 'SPACE' to start a new game
- Press 'ESC' to exit
- Show your hand gesture when the countdown reaches zero
- Wait for AI's move and see the result

### Hand Gestures
![Hand Gestures](media/image5.jpeg)

## 🏗 System Architecture

The system consists of four main components:

1. **Hand Gesture Detection Module**
   - OpenCV cascade classifier
   - MediaPipe hand landmark detection
   - 30 FPS processing rate

2. **Gesture Interpretation System**
   - Real-time gesture classification
   - Pattern recognition
   - State machine implementation

3. **Game Logic Controller**
   - Game state management
   - Score tracking
   - Round timing

4. **AI Opponent Module**
   - Strategic decision making
   - Pattern analysis
   - Adaptive difficulty

## 📊 Performance

- Gesture Recognition Accuracy: >90%
- Response Time: <50ms
- Frame Rates:
  * Camera/Detection: 30 FPS
  * Game Display: 60 FPS
- Resolution Support: up to 1920x1080

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Coding Standards
- Follow PEP 8 guidelines
- Include docstrings for all functions
- Add unit tests for new features
- Update documentation as needed

## 📝 License
This project is licensed under Sharda University Uzbekistan. See the [LICENSE](LICENSE) file for details.

## 📫 Contact

Nurmuhammad Isokjonov - nurmuhammad.isokjonov@ug.shardauniversity.uz

Academic Advisor: Dr. Pooja - pooja@shardauniversity.uz

Project Link: [https://github.com/yourusername/rps-ai-game](https://github.com/yourusername/rps-ai-game)

## 🙏 Acknowledgments
- Faculty of Engineering & Technology, Sharda University
- OpenCV Community
- MediaPipe Team
- TensorFlow Team

---
