EdgeGenSec AI — GAN-enhanced Intrusion Detection on Edge Devices
EdgeGenSec AI is a lightweight, edge-deployable Intrusion Detection System (IDS) enhanced with a Generative Adversarial Network (GAN) for improving detection of cyber-attacks using synthetic data. This system is optimized for devices like Raspberry Pi 5 (8GB) and uses quantized models for real-time performance.

🔍 Project Overview
Objective: Improve anomaly detection performance by training with a combination of real and synthetic attack data.

Components:

MobileNetV2 (Quantized) classifier for low-latency detection.

MobileGAN: A GAN used to generate high-quality synthetic attack data.

Discriminator: A model trained to distinguish real vs synthetic attack traffic.

Dataset: CICIDS2017

