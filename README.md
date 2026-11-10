# TextureSnap Studio — Desktop PBR Engine

[![Download Latest Release](https://img.shields.io/badge/Download-TextureSnap.exe_(v1.0.9)-2563eb?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Kl3tus/texturesnap-desktop/releases/latest)
[![Google Play](https://img.shields.io/badge/Google_Play-TextureSnap_Android-059669?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.solidtakegames.texturesnap)
[![License](https://img.shields.io/badge/License-Commercial%20%2F%20Closed%20Source-d97706?style=for-the-badge)](https://paypal.me/Kl3tus)

High-performance desktop workstation edition of **TextureSnap: 3D Scanner & PBR**, bringing on-device surface de-lighting, tangent-space normal synthesis, cavity ambient occlusion extraction, ORM channel packing, and dual-axis seamless tiling to Windows game development and 3D modeling environments.

Distributed as a self-contained, standalone native binary. Zero installation, zero Python dependencies, and zero setup required.

---

## ⚡ Quick Start (Windows Standalone)

1. **[Download TextureSnap.exe from GitHub Releases](https://github.com/Kl3tus/texturesnap-desktop/releases/latest)**
2. Double-click **`TextureSnap.exe`** to launch immediately.
3. Select any reference photo (concrete, wood, brick, fabric, soil, foliage) or click **Open Live Camera Viewfinder** for direct macro capture.
4. Adjust your normal strength, roughness threshold, and ambient occlusion bias.
5. Click **Generate All PBR Maps** and export your game-ready texture pack!

---

## 🛠️ Workstation Pipeline & Capabilities

### 1. High-Pass Poisson Surface De-Lighter
- Strips away harsh camera flash, directional sunlight, lens vignette, and non-uniform lighting gradients.
- Preserves micro-surface chrominance ratios and intrinsic albedo based on Retinex color constancy algorithms.

### 2. Tangent-Space Normal Map Synthesizer
- High-frequency surface normal vectors computed via multi-scale Sobel and Scharr differential kernels.
- Instant toggle between **DirectX** (Invert Green / UE5) and **OpenGL** (Blender, Unity, Godot) normal formats.

### 3. Cavity Ambient Occlusion & Roughness Extraction
- Concavity curvature falloff evaluates micro-crevices and geometric contact shadows.
- Micro-relief roughness mapping with dynamic contrast scaling.

### 4. Game Engine ORM Channel Packing
- Automatically composites critical PBR channels into a single high-efficiency map:
  - **Red Channel:** Ambient Occlusion (AO)
  - **Green Channel:** Roughness
  - **Blue Channel:** Metallic (Customizable)
- 100% compliant with **Unreal Engine 5**, **Unity HDRP**, and **Godot 4** standard PBR shaders.

### 5. Interactive 3D Material Orbit Viewport
- Real-time CPU-shaded 3D PBR sphere rendered at 60+ FPS via vectorized microfacet lighting equations.
- Click and drag directly on the sphere to orbit directional light sources and inspect specular glint, roughness falloff, and surface bump depth.

### 6. Live USB & Webcam Viewfinder
- Real-time video streaming with AR alignment reticles and crosshairs.
- One-click freeze & synthesize workflow optimized for macro lenses, USB microscopes, and tethered capture.

### 7. Automated Studio Batch Folder Pipeline
- Multi-threaded batch processor processes entire directories of reference images in seconds.
- Automatically organizes and names outputs (`_BaseColor.png`, `_Normal.png`, `_Roughness.png`, `_AO.png`, and `_ORM.png`).

### 8. Dual-Axis Seamless Tiling Synthesizer
- Cosine boundary falloff eliminates edge borders for infinite, seam-free material wrapping.

---

## 👑 TextureSnap Pro Lifetime ($10)

TextureSnap provides an unlimited free tier supporting up to 1024×1024 resolutions and standard PBR maps.

### Pro Unlocks:
- 🌟 **4096×4096 (4K Ultra)** high-resolution map synthesis
- 🌟 **Complete ORM Channel Packing** for game engines
- 🌟 **Dual-Axis Seamless Tiling Synthesizer**
- 🌟 **Studio Multi-Threaded Batch Pipeline**

### Activation:
1. In the app, click **UPGRADE TO PRO ($10)**.
2. Scan the in-app PayPal QR code or pay $10 at [paypal.me/Kl3tus](https://paypal.me/Kl3tus).
3. Include your unique **Hardware ID** (displayed in the activation modal) in your transaction note.
4. Enter your issued cryptographic Pro Activation Key to unlock Pro permanently on your machine.
*(B2B Studio Partners can enter their assigned studio passcodes directly).*

---

## 📱 Mobile Companion

Scan textures in the field with your phone camera:  
👉 **[TextureSnap on Google Play Store](https://play.google.com/store/apps/details?id=com.solidtakegames.texturesnap)**

---

&copy; 2026 Solid Take Games. Developed by Mikel Bryan.
All rights reserved. Proprietary and confidential commercial distribution.
