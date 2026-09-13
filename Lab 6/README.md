## Lab 6 — Image Compression & Image Restoration

Transform-based compression techniques and noise-model-specific restoration filters.

- Image compression using:
  - Discrete Cosine Transform (DCT, block-based with zig-zag coefficient selection)
  - Haar Wavelet Transform
  - Hybrid DCT-Haar compression
  - Evaluated using PSNR and compression ratio
- Gaussian noise restoration using the mean-family filters:
  - Geometric mean filter
  - Harmonic mean filter
  - Contra-harmonic mean filter
- Gaussian noise restoration using order-statistic filters:
  - Median, Maximum, Minimum, Midpoint, Alpha-trimmed mean, Trimmed mean
- Comparative analysis of all restoration filters ranked by PSNR

**Tools:** OpenCV, NumPy, SciPy (`fftpack.dct/idct`, `ndimage`), Matplotlib
