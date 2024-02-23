# SEPO-C-application
## Introduction
This application detecting cells in images to assess the progress of cell synthesis during the cultured meat process.

(어플리케이션 개발 이유 : 배양육 재배 과정에서 세포 갯수 및 퓨전 인덱스 중요성)
### Fusion Index
Fusion index is a method for determining muscle cell myotubule formation.

(탐지 및 분류 알고리즘)

(겹치는 세포를 구분하는 알고리즘)

## Process
![SEPO-C 3](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/293c4eba-1335-4694-b705-86004d443cbf)
### 1.Image load
- Click the [Open Folder] button - load images from the file path
### 2.Detection
- Click the [Color Detection] button - Detection is performed on the image and the results are displayed on the right panel.
- The right panel displays the number of cells on myotube('IN' class), the number of cells outside myotube('OUT' class),the total number of cells, and the Fusion Index.
### 3.Extract results
- When performing image dection, the results are saved as a csv file.

## Features
![cell detection program structure_eng](https://github.com/SEPO-C/SEPO-C-application/assets/49020136/f72a9104-fea1-4748-b3fc-cd4e3b4a4e09)
- Cell detection based on color (HSV value)
- Cell In/Out classsfication based on learned AI model
- Perform detection by specific image

## Requirements
- Pytorch
- PyQt5
- Numpy
- OpenCV

## Installation
Download exe file [here](https://docs.google.com/uc?export=download&id=1aDF72Uoa4vq_kG-4fzViry52TYHmjfSW&confirm=t) from Goolge drive


## Contact Us
If you have any questions or provide your cell images, please contact us by email(kc.jeong-isw@chungbuk.ac.kr, gc.jo-isw@chungbuk.ac.kr).
