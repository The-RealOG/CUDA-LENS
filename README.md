# CUDA LENS 🚀
> Real-time image processing with CUDA acceleration

**CUDA LENS** is a fast and lightweight image filtering application built using **CUDA** and **OpenCV**. It demonstrates how GPU acceleration can dramatically outperform CPU-based image processing, especially on high-resolution images and real-time video feeds.

## 🧠 Features

- ⚡ CUDA-accelerated image filters
- 🎨 Filter options: Grayscale, Gaussian Blur, Edge Detection (Sobel), Sharpen
- 📸 Real-time webcam mode
- 📁 Batch processing for folders of images
- 📊 Benchmarking: Compare CUDA vs CPU filter performance

## 🛠️ Tech Stack

- **C++**
- **CUDA**
- **OpenCV**
- (Optional) **Python** wrapper or CLI
- (Optional) **Qt** for GUI (future update)


## 🚀 Getting Started

### Prerequisites
- CUDA Toolkit (v11+)
- OpenCV installed with C++ bindings
- CMake / Make

### Build Instructions

```bash
git clone https://github.com/the-realOG/CUDA-LENS.git
cd "CUDA LENS"
mkdir build && cd build
cmake ..
make
./CUDA LENS
