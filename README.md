# SEPO-CMR-application

## Introduction
This software is designed to count and classify the nuclei of muscle cells, with the aim of calculating the fusion index of cultured meat, ultimately demonstrating the application’s relevance in both the biological and biomedical research fields. In

\begin{equation}
\text{Fusion Index} = \frac{N_{\text{In}}}{N_{\text{In}} + N_{\text{Out}}}
\label{eq:fusion_index}
\end{equation}

(어플리케이션 개발 이유 : 배양육 재배 과정에서 세포 갯수 및 퓨전 인덱스 중요성)
### Fusion Index
Fusion index is a method for determining muscle cell myotubule formation.

(탐지 및 분류 알고리즘)
![Overview_Version2](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/ddcd7671-cb5b-408a-a641-1bf20b935e42)

(겹치는 세포를 구분하는 알고리즘)


## Installation
Download exe file [here](https://docs.google.com/uc?export=download&id=1aDF72Uoa4vq_kG-4fzViry52TYHmjfSW&confirm=t) from Goolge drive

## Process
![SEPO-C 3](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/293c4eba-1335-4694-b705-86004d443cbf)
### 1.Image load
- Click the [Open Folder] button - load images from the file path
### 2.Detection
- Click the [Detection] button - Detection is performed on the image and the results are displayed on the right panel.
- The right panel displays the number of cells on myotube('IN' class), the number of cells outside myotube('OUT' class),the total number of cells, and the Fusion Index.
### 3.Extract results
- When performing image dection, the results are saved as a csv file.

###

## Features
- Cell detection based on color (HSV value)
- Cell In/Out classsfication based on learned AI model
- Perform detection by specific image
- Image display
![zoom image](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/d795db92-618f-4a71-8991-8f81bd1fb230)
The detected images are displayed by boxes and can be zoomed using the controls + mouse wheel or bar at the bottom.
## Requirements
- Pytorch 1.21.xx
- PyQt5 5.15.xx
- Numpy 1.23.xx
- OpenCV 4.9.xx


## Contact Us
If you have any questions or provide your cell images, please contact us by email(kc.jeong-isw@chungbuk.ac.kr, gc.jo-isw@chungbuk.ac.kr).
