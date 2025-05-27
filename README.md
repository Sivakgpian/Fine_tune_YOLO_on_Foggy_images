# Edge Object Detection Pipeline for Low-Light and Foggy Environments

## Overview
This project implements an object detection pipeline tailored for challenging environments such as low-light, foggy, and blurred video feeds typically captured by drones or underwater cameras. The solution is optimized for deployment on resource-constrained edge devices like NVIDIA Jetson Nano and Raspberry Pi 4.

## Features
- Pretrained and fine-tuned YOLOv8 model for robust object detection under adverse conditions.
- Dataset: Foggy Cityscapes with custom augmentations to simulate fog and blur effects.
- Comprehensive pipeline including preprocessing, training, evaluation, and inference scripts.
- Optimized model export using ONNX and TensorRT for efficient edge deployment.
- Performance benchmarks comparing CPU and GPU inference speeds and latency.

## Repository Contents
- `dataset/` — Processed dataset and augmentation scripts.
- `models/` — Pretrained and fine-tuned model weights.
- `scripts/` — Code for preprocessing, training, evaluation, and inference.
- `deployment/` — ONNX and TensorRT optimized models and deployment guides.
- `output_logs/` — Scripts and results for FPS and latency benchmarking.

## Usage
Refer to the `scripts/` directory for instructions on running preprocessing, training, and inference. Use the `deployment/` folder for deployment on Jetson Nano or Raspberry Pi 4.

## Requirements
- Python 3.8+
- PyTorch
- ONNX Runtime
- TensorRT (for deployment optimization)
- OpenCV

## License

---

Thank you for exploring this project. Contributions and feedback are welcome!
