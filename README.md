<h1 align="center">🔥 HackFest Wildfire Detection</h1>
<p align="center">
  By Sumit Sah | Android Developer & AI Enthusiast<br>
  Runner-up at <b>OSM HackFest 2024</b> for wildfire detection solution
</p>

<p align="center">
  <a href="https://github.com/sumitsah250/HackFestWildFireDetection"><img src="https://img.shields.io/badge/GitHub-View%20Code-black?logo=github"></a>
  <a href="https://www.linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin"></a>
</p>

---

<h2 align="center">🚀 Overview</h2>

This repository contains my **HackFest 2024 project** for wildfire detection.  
The project uses **satellite imagery, image processing, and AI techniques** to detect potential wildfire regions early, helping authorities to respond faster and reduce damage.  

We achieved **runner-up** position at OSM HackFest 2024.  

---

<h2 align="center">📂 Project Structure</h2>

| Folder/File | Description |
|-------------|-------------|
| **images/** | Sample images used for testing and presentation |
| **Fire_detection (1).ipynb** | Jupyter notebook for fire detection ML/AI workflow |
| **Wildfire Radar (1).pptx** | HackFest presentation slides |
| **README.md** | Project overview and documentation |

---

<h2 align="center">🛠️ Tech Stack</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenCV-ImageProcessing-red?logo=opencv" />
  <img src="https://img.shields.io/badge/NumPy-DataProcessing-yellow?logo=numpy" />
  <img src="https://img.shields.io/badge/MachineLearning-ML-green?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
</p>

---

<h2 align="center">💡 Features</h2>

- **Wildfire Detection:** AI/ML-based detection using satellite and test images  
- **Real-Time Analysis:** Process and identify fire regions in input images  
- **Visualization:** Highlight detected areas on images for better clarity  
- **Presentation Ready:** Included slides for HackFest showcase  

---

<h2 align="center">📊 Example Usage</h2>

```python
# Example usage in Jupyter Notebook
import cv2
from fire_detection import detect_fire

# Load test image
img = cv2.imread('images/test_image.jpg')

# Detect fire regions
fire_mask = detect_fire(img)

# Show results
cv2.imshow('Detected Fire', fire_mask)
cv2.waitKey(0)
cv2.destroyAllWindows()
