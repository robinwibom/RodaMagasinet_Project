# RodaMagasinet_VirtualMuseum

## Project Overview
This repository contains the work conducted during the **TSBB11 - Images and Graphics, Project Course CDIO**, focused on re-imagining and reviving historic art using computer vision, machine learning and computer graphics. Our project aimed to digitally recreate and present the historic mural on the "Röda Magasinet" building through 3D reconstruction, image recoloring, and virtual visualization.

### Goals:
1. Reconstruct the "Röda Magasinet" building in 3D using **Structure from Motion (SfM)**.
2. Restore and colorize historic grayscale images using **machine learning** and **manual editing**.
3. Create an interactive virtual museum using **Unreal Engine**.
4. Explore **monocular depth estimation** to create 3D-like models from single images.
5. Test **dense feature matching**  (used here for interpolating views between historical images).

---

## Key Components

### 1. 3D Reconstruction
- **COLMAP**: [colmap](https://colmap.github.io/), The resulting model were optimized with meshlab and blender for use in Unreal Engine.

### 2. Image Recoloring
Two approaches were explored:
- **Photoshop Neural Filters**: For manual adjustments and AI-based colorization.
- **DeOldify**: [DeOldify](https://deoldify.ai/)

### 3. Monocular Depth Estimation
We employed **MoGe** (Monocular Geometry Estimation), [MoGe](https://wangrc.site/MoGePage/), The resulting models were optimized with meshlab and blender for use in Unreal Engine.

### 4. Dense Feature Matching
We utilized **RoMa**, a robust dense feature matching model, to interpolate views between sparse historical images. [RoMa](https://parskatt.github.io/RoMa/)

### 5. Virtual Museum
The final reconstructed building and recolored images were integrated into a **virtual museum** built using **Unreal Engine 5**. The museum provides an engaging, interactive way to experience the restored art and building.

---

## How to Use:
1. **Download**  
   Visit the following link to download the desired version: [Google Drive Link To Demos](https://drive.google.com/drive/folders/1MXiU92qgDcH8faPy4cuYynGJqp206S4X?usp=sharing).  

2. **Extract**  
   Unzip the downloaded file and locate `RM_Museum.exe`.  

3. **Run the Program**  
   Double-click on `RM_Museum.exe`. If Windows displays a warning:  
   - Click **Advanced Options**.  
   - Select **Run Anyway**.  

4. **Install Pre-Requisites**  
   If prompted, install any required dependencies to ensure the program functions correctly.

## Acknowledgments
This project was a collaboration between:
- **Linköping Municipality**
- **Computer Vision Laboratory (CVL), Linköping University**
- **AI Sweden**

We thank these organizations for their support and resources.


