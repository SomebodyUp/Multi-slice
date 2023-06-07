# Multi-slice information sharing
> **Time** ***06/07/2023***
🤗

> **Improving single-shot multi-parametric mapping via multi-slice information sharing based on multiple overlapping-echo detachment imaging**

> **Chenyang Dai , Qinqin Yang , Jiechao Wang , Congbo Cai , Shuhui Cai**

## Abstract
Multi-parametric quantitative magnetic resonance imaging (qMRI) has important applications in clinic. Multiple overlapping-echo detachment (MOLED) imaging can achieve single-shot multi-parametric qMRI. However, the existing methods mainly focus on single-slice reconstruction. To improve the reconstruction quality of parametric maps by exploring data redundancy among adjacent slices, we proposed a multi-slice information sharing method via multiple modulation patterns of MOLED k-space and deep neural network. The results show that our method can effectively utilize the correlation information among adjacent slices and improve the reconstruction quality compared to the single-slice reconstruction method.

## Introduction

'Pulse Sequence':

<div align=center>
  <img width="359" alt="image" src="https://github.com/SomebodyUp/Multi-slice/assets/55176537/2b632b72-523c-4f37-9d6b-4eb569056cfd">
</div>

> **Fig. 1** (a)Generic MOLED pulse sequence. (b)A representative MOLED k-space and the corresponding MQMOLED image from the Fourier transform of the k-space. FT denotes Fourier transform. (C)Three modulation patterns (MP-A, MP-B and MP-C) of the k-space were designed, which were used alternately in adjacent slices.

> **3D Attention Gate Neural Network**

<div align=center>
  <img width="436" alt="image" src="https://github.com/SomebodyUp/Multi-slice/assets/55176537/86aeb8f2-dff0-49d1-be14-607de9c4d0f2">
</div>

> **Fig. 2** The flowchart of deep neural network reconstruction. The inputs of the neural network are the real and imaginary parts of the MOLED adjacent slice images. 

## To be continued ......
