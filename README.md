# Group Project
## Title: ECG-Gated High Frame Rate Echocardiography with Respiratory Motion Correction
This group project was done by **collaboration between 9 group members** from engineering and medicine departments. The entire project involves ECG signal and Ultrasound image processing, and I was taking part in ECG signal processing part.

1. [Project Introduction](#intro)
2. [Group Report](#thesis)
3. [Poster](#ps)
4. [Code](#code)

<a name="intro"></a>
## 1. Project Introduction

The quantification of myocardial perfusion is an important measure in diagnosis cardiac disease, such as, coronary artery disease. Such measure is often computed by pixel wise substractions between consequtive imaging frames. This requires the same object remains at the same shape and coordinate in each frame. However, heart is like a pump which experiencing **non-rigid transformation** from time to time. Moreover, heart also has a **rigid translational motion** due to the mechanicm of breathing. Thus, the aim of the project is to remove two source of motions and hence improve myocardial perfusion quantification.

Although heart is similar to a pump that constantly dialates and contracts, heart do transmit us a signal "ECG" that inform us the instant of dilation or contraction. Therefore, we detect certain features of real-time ECG signals and then trigger ultrasound platform, so the frames are only taken when heart was in a particular shape, namely phase. Hence the **non-rigid transformation** was resolved by **ECG signals processing**. The **rigid translational motion** was removed by **image registration techniques**, where we translate the rigid object in different frames to a common coordinate. 

<a name="intro"></a>
## 2. Group Report

The group report can be accessed by click [Final.pdf](https://github.com/asdxaasas/3rdYearProject/blob/master/Final.pdf)

<a name="ps"></a>
## 3. Poster

The postered for this project can be accessed by click [poster.pdf](https://github.com/asdxaasas/3rdYearProject/blob/master/poster.pdf)

<a name="code"></a>
## 4. Code

The code for the signal processing part can be accessed from [get_graph.m](https://github.com/asdxaasas/3rdYearProject/blob/master/get_graph.m) 
The code does not run without the physical unit that input the real-time ECG signal, but the ECG signal feature detection will still work if you use stored ECG signals, such as data from [physiobank database](https://archive.physionet.org/physiobank/database/#ecg)



