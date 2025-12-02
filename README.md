# MSBA 503 — Take-Home Assignment  
## Computer Vision Object Detection (YOLOv8 vs. Faster R-CNN)

**Author:** Alex Snyder  
**Course:** MSBA 503 — Programming Analytics II  
**Instructor:** Prof. Majumdar 
**Date:** December 2025  

---

## Assignment Description

This repository contains the code and output for the MSBA 503 Take-Home Assignment.  
The goal is to compare the performance of two object detection models:

- **YOLOv8 (Ultralytics)**
- **Faster R-CNN (TorchVision)**

Both models were evaluated on the same set of 10 images (not included in this repository per assignment instructions).  
Performance metrics captured:

- Inference time (seconds)
- Number of objects detected
- Average confidence score
- Additional non–deep learning metric (image brightness)

---

## Repository Structure
MSBA-503
   - take_home_assignment
   - msba503_takehome.ipynb # Fully commented assignment notebook
   - model_comparison_final.csv # Final comparison table exported from the notebook
   - README.md # Project documentation


---

## How to Run the Notebook

To reproduce the results:

1. Download or clone this repository.
2. Open:  
   `take_home_assignment/msba503_takehome.ipynb`
3. Ensure the following Python libraries are installed:
   - ultralytics  
   - torch, torchvision  
   - numpy  
   - pandas  
   - pillow (PIL)
4. Place your own sample images in a local `data/` directory.
5. Run all cells to generate detections and the comparison table.

---

## Output Included

- **model_comparison_final.csv**  
  Final cleaned table comparing YOLOv8 and Faster R-CNN across all metrics.

The full written responses for Part A(i) and Part A(ii) are included in the separate Word document submitted for grading.

---

## Repository Link

https://github.com/alexgsnyder/MSBA-503
