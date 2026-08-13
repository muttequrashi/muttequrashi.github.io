---
title: Multi-Camera Real-Time CV Pipeline
summary: DeepStream + GStreamer C++17 pipeline processing 4+ concurrent 30 FPS streams on Jetson.
tags:
  - Computer Vision
  - DeepStream
  - GStreamer
  - Jetson
  - C++
date: '2024-03-01'

external_link: ''
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
slides: ''
---

Real-time multi-camera system in C++17 using NVIDIA DeepStream SDK and GStreamer, processing 4 or more concurrent video streams at 30+ FPS on NVIDIA Jetson edge devices. PyTorch to ONNX to TensorRT (FP16 and INT8) model conversion pipeline delivered 3x inference speedup, with OpenVINO fallback for Intel hardware. CI/CD with GitHub Actions, Docker deployment, unit tests with Google Test.
