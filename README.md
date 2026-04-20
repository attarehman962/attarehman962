# Atta Ur Rehman

> Data Scientist | Computer Vision Engineer | High-Performance Computing

> **Note:** GitHub README files do not support active HTML/CSS animations in the rendered profile. The code below can be used as a website banner, but it will display as plain text in GitHub.

## 🌐 Banner HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Animated GitHub Banner</title>
    <style>
      body {
        margin: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f0f0f0; /* Light background to test */
      }

      .banner-container {
        width: 1000px; /* Standard GitHub Header Width */
        height: 250px;
        background-color: #24292e; /* GitHub dark theme background */
        display: flex;
        justify-content: center;
        align-items: center;
        font-family:
          "Courier New", Courier, monospace; /* Monospace font looks like code */
        color: #ffffff;
        border-radius: 6px;
        overflow: hidden;
      }

      .typing-text {
        font-size: 3em;
        font-weight: bold;
        white-space: nowrap;
        overflow: hidden; /* Keeps text hidden until revealed */
        border-right: 4px solid #ffffff; /* The cursor */
        width: 0; /* Start with no text visible */
        animation:
          typing 3.5s steps(30, end) forwards,
          /* Typewriter effect */ blink-cursor 0.75s step-end infinite; /* Cursor blink */
      }

      /* The Typing Animation */
      @keyframes typing {
        from {
          width: 0;
        }
        to {
          width: 100%;
        } /* Adjust percentage based on text length */
      }

      /* The Cursor Animation */
      @keyframes blink-cursor {
        from,
        to {
          border-color: transparent;
        }
        50% {
          border-color: #ffffff;
        }
      }
    </style>
  </head>
  <body>
    <div class="banner-container">
      <div class="typing-text">I am a Web Developer.</div>
    </div>
  </body>
</html>
```

## 👋 About Me

I am a Computer Scientist specializing in Artificial Intelligence and High-Performance Automation. I bridge the gap between low-level optimization (C++) and modern deep learning frameworks (Python).

- 🎓 3rd-year Computer Science student at FAST-NUCES
- 🧠 Focused on Computer Vision, Medical Imaging, and Anomaly Detection
- ⚙️ Experienced in building AI systems, optimizing C++ code, and deploying models in production
- 📡 Currently working on unsupervised learning for medical diagnosis

## 💼 Skills

| Domain             | Tools & Technologies                                                                                                                                                                                                                                                                                                          |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Programming        | ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)                                                                                                                    |
| AI & Deep Learning | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![MONAI](https://img.shields.io/badge/MONAI-000000?style=for-the-badge&logo=monai&logoColor=white) |
| Computer Vision    | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![Image Processing](https://img.shields.io/badge/Image%20Processing-000000?style=for-the-badge&logo=opencv&logoColor=white)                                                                                             |
| Data & Analytics   | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)                                                                                                                      |
| Tools & Deployment | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)                                                                                                                            |

## 🚀 Major Projects

### 1. Medical Imaging & Diagnostic AI

- Built end-to-end pipelines for medical image preprocessing, segmentation, and anomaly detection
- Used MONAI and PyTorch to design models for robust diagnosis support
- Optimized runtime and memory usage for faster inference on large medical volumes

### 2. Computer Vision Systems

- Developed custom image segmentation and object detection solutions
- Applied statistical analysis and predictive modeling to improve accuracy
- Worked with real-world image datasets and deployment-ready architectures

### 3. Algorithmic Trading Bots

- Designed automated trading systems using Python and real-time financial APIs
- Implemented signal generation, backtesting, and execution strategies
- Focused on robustness, latency, and reliable data handling

### 4. Performance Optimization in C++

- Optimized algorithms and memory layouts for high-performance applications
- Bridged low-level C++ efficiency with high-level AI workflows
- Improved speed and scalability for compute-intensive tasks

## 📫 Contact

- GitHub: [@attarehman962](https://github.com/attarehman962)
- Location: Peshawar, Pakistan

---

> I combine AI research, computer vision engineering, and high-performance computing to build solutions that are both intelligent and efficient.
