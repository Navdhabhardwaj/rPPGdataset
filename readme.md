Description
---
This repository contains the Diverse rPPG Dataset, collected from North Indian participants for rPPG and physiological signal research. The original data were collected as high-resolution facial videos. To protect participant privacy, the research-access release does not contain the original facial images or videos. Instead, it provides ROI-level frame-wise mean RGB temporal measurements and ground-truth RR intervals.

Key Features:
---
1. Acquisition: 1080p @ 30 fps
2. Released data: ROI-level frame-wise mean RGB measurements + RR intervals
3. Ground truth: emWave Pro


Sample Data
---
The privacy-preserving release contains the following data modalities:

1. ROI-level frame-wise mean RGB temporal measurements
2. RR interval ground truth

No original facial images or videos are included in this release.

Data Format and Alignment — Please Read Before Use
---
The privacy-preserving release provides ROI-level RGB temporal signals and RR interval values (in milliseconds) as two separate streams for each subject.
1. The ROI-level RGB data are frame-wise temporal measurements, where each frame contains the mean R,G and B intensity values computed within predefined facial regions of interest.
2. The RR intervals are beat-to-beat measurements obtained from the emWave Pro sensor.
3. Individual RR values are not timestamped at the video-frame level.
4. Researchers should not attempt to align a single RR value with a single frame or individual RGB sample.


Download
---
The dataset is available for non-commercial academic research purposes. To request access:

1. Email to navdhabhardwaj009@gmail.com with the subject line:`Dataset Access Request – rPPG-26`.
2. Once we receive the completed and signed form, we will provide access to the privacy-preserving dataset.

> Note: This dataset is intended for academic research purposes only. The released data do not include the original facial images or videos.

---

## 📄 Citation

If you use this dataset in your research, please cite:

```
@inproceedings{10.1145/3774521.3774627,
author = {Bhardwaj, Navdha and verma, yashit and Bhavsar, Arnav},
title = {A New Diverse Dataset for rPPG Estimation, and Benchmarking with Standard Frameworks},
year = {2026},
isbn = {9798400719301},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},



