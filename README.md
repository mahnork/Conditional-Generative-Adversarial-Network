 Seg2Brain: Brain Image Synthesis from Segmentation Maps using Pix2Pix (cGAN)

This repository contains an implementation of a Conditional GAN based on the Pix2Pix framework for translating medical segmentation maps into realistic brain MR images. The model learns a mapping from segmentation labels to anatomical brain structures using paired image data, enabling high-quality synthesis useful in data augmentation, simulation, and analysis.

Features:
Based on the Pix2Pix architecture with U-Net generator and PatchGAN discriminator.

Preprocessing pipeline for paired image datasets.

TensorFlow 2.x implementation with customizable training loop.

Real-time visualization of generated images during training.

Designed for 256×256 medical images (modifiable).

Dataset:
Expects a directory of side-by-side (concatenated) image pairs (e.g., left: segmentation, right: real brain MRI).

Dataset directory should be structured with training/validation/test folders.

Use Cases:
Medical image augmentation

Synthetic data generation for segmentation models

Research on anatomy-preserving translation
