# SEPO_FI application: A Deep Learning-Based Software to Calculate Fusion Index of Muscle Cells
## Introduction
This software is designed for counting and classifying muscle cell nuclei to calculate the fusion index, highlighting its importance in biological and biomedical research.

- **Nuclei Counting:** Counts total number of cell nuclei.
- **Classification:** Determines whether nuclei are inside (In) or outside (Out) the myotubes.
- **Fusion Index Calculation:** Automatically computes the fusion index, a critical measure of cultured muscle cell maturity and development.
  $$\text{Fusion Index} = \frac{N_{\text{In}}}{N_{\text{In}} + N_{\text{Out}}}$$
- **Streamlined Evaluation:** Enhances research efficiency by automating the fusion index evaluation process.
![SEPO_FI](https://github.com/user-attachments/assets/1f164373-149e-4405-a8c1-d720251c47c0)



## Installation
Download the executable file from Google Drive:
- [Download exe file here](https://docs.google.com/uc?export=download&id=1M9yUcMNlvRuqou5VnMbUmXeAoLGSH_O1&confirm=t)
## How to Use
Follow these steps to operate the software:

### 1. Image Load
- Click the `[Open Folder]` button to load images from the file path.

### 2. Detection
- Click the `[Detection]` button to perform detection on the loaded images.
- The right panel will display:
  - Number of cells on myotube (`IN` class).
  - Number of cells outside myotube (`OUT` class).
  - Total number of cells.
  - Fusion Index.

### 3. Extract Results
- Detection results are saved when the `[Export CSV]` button is pressed, exporting the evaluation outcomes to a CSV file.

## Application Requirements
Ensure the following dependencies are installed to utilize this software optimally:

- **Pytorch**: Version 1.21.>
- **PyQt5**: Version 5.15.>
- **Numpy**: Version 1.23.>
- **OpenCV**: Version 4.9.>
- **Cuda**: Recommended for significantly enhanced performance.
  - Note: Without Cuda, processing times may be considerably longer, which could affect user experience.



## Features
- Cell detection based on color (HSV value)
- Cell In/Out classsfication based on learned AI model
  ![Fig 8  Step 2  CNN model](https://github.com/user-attachments/assets/81392ca5-13ff-4c4c-a2d5-2784c5389409)
- Image display
  - The detected images are displayed by boxes and can be zoomed using the controls + mouse wheel or bar at the bottom.
  ![zoom image](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/d795db92-618f-4a71-8991-8f81bd1fb230)




## Contact Us
If you have any questions or provide your cell images, please contact us by email(kc.jeong-isw@chungbuk.ac.kr, gc.jo-isw@chungbuk.ac.kr).
