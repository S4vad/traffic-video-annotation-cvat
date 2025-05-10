# Traffic Video Annotation – Vehicle & Road Feature Labeling

## 📌 Overview
This project demonstrates object and road feature annotation on traffic video data using **CVAT** (Computer Vision Annotation Tool). The video data was processed to track and label various road users and environmental features critical to computer vision and autonomous driving systems.

## 📁 Files Included
- `annotated_data.zip`: Exported annotations from CVAT.
- [`annotation_demo.mp4`](https://drive.google.com/drive/folders/1dzhTByfQ_6UnoO4rIO46q9X7IJ8J3B2Z?usp=drive_link): Screen recording showing annotation process and labeling.
- `README.md`: Project overview and instructions followed.

---

## ✅ Labeling Tasks Performed

### 1. Semantic Segmentation (Vehicle Masking)
- Pixel-level segmentation of vehicles.
- Labeled classes: **car**, **bus**, **truck**, **motorcycle**.

### 2. Lane Marking & Road Feature Annotation
- Lane boundaries and road edges annotated with types:
  - **Solid**, **dashed**, **double lines**, etc.
- Added features:
  - **Pedestrian crossings**, **traffic islands**, **speed bumps**.

### 3. Vehicle Pose Estimation (Keypoint Annotation)
- Keypoints for **wheels**, **headlights**, **taillights**, **front**, and **rear** labeled.
- Useful for **motion tracking** and **vehicle behavior analysis**.

---

## 🧠 Object Tracking and Attributes

- Tracked and labeled:
  - **Vehicles**, **pedestrians**, **cyclists**, **traffic signs**.
- Assigned consistent object IDs across frames.
- Added object-level attributes:
  - `moving`, `stopped`, `turning`, `jaywalking`, etc.
- Marked visibility: `fully visible`, `partially occluded`, `heavily occluded`.
- Traffic lights were linked to respective lanes with states:
  - `red`, `yellow`, `green`.

---

## 🛠️ Annotation Guidelines Followed
- Tight and accurate bounding boxes.
- Ignored blurry or occluded objects.
- Focused only on the specified object classes.

---

## 💡 CVAT Shortcut Keys

- `F`: Move forward 1 frame  
- `D`: Move backward 1 frame  
- `V`: Move forward 10 frames  
- `C`: Move backward 10 frames  
- `Shift + Click`: Add new point (e.g., for polygon or polyline)  
- `Alt + Click (on point)`: Delete a point  
- `O`: Delete a skeleton point  

These shortcuts help speed up the annotation process significantly.

---


## 🔗 Notes
> ⚠️ **Note:** CVAT does not export video with annotation overlays, so a screen recording is shared via [Google Drive](https://drive.google.com/drive/folders/1dzhTByfQ_6UnoO4rIO46q9X7IJ8J3B2Z?usp=drive_link) to demonstrate the visual annotations.  
> Annotations are also exported as a `.zip` file for reuse or validation.


---

## 🚀 Tools Used
- **CVAT** – Annotation platform.
- **OpenCV** – For preprocessing and video review.
- **Git** – Version control.
