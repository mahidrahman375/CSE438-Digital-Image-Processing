## Lab 7 — Image Segmentation & Morphological Operations

Segmentation techniques applied to a brain tumor MRI, plus edge/line detection on an X-ray.

- Binary tumor mask generation (Otsu thresholding) followed by:
  - Morphological dilation
  - Morphological erosion
- Line detection using Canny edge detection + Probabilistic Hough Transform (applied to a hand X-ray)
- Tumor segmentation using:
  - Region growing
  - Region splitting and merging (quadtree-based)
  - Marker-controlled watershed segmentation
  - Quadtree segmentation
- Side-by-side visual summary comparing all segmentation approaches

**Tools:** OpenCV, NumPy, scikit-image (`filters`, `morphology`, `measure`, `segmentation`, `exposure`), Matplotlib
