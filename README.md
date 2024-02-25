## INTRODUCTION

A tumor is a collection of aberrant cells that form a tissue. These aberrant cells consume regular body cells, kill them, and continue to expand in size.

Brain tumor is one of these tumors. Nerve cells, brain cells, glands, and membranes that surround the brain are all affected. Imaging and pathology can both be used to diagnose a tumor.

An MRI (Magnetic Resonance Imaging) scan of a brain tumor produces a cross-section picture of the brain. In this report, we provide two models based on Artificial Convolutional Neural Networks that uses mathematical formulae and algebraic operations to analyze and predict if the tumor exists and to localize the area of tumor on MRI Images.

## PROCEDURE

![Flowchart Diagram AI Project](https://github.com/chaitanyaamle/Brain-Tumor-Diagnosis/assets/30501921/a6543e66-3606-44b2-9138-0ca432d01aba)

1.	Our primary goal in the first stage is to collect patient data in the form of MRI images. These MRI images are saved in a .csv format.
2.	This information should be entered into the RESNET DEEP LEARNING CLASSIFIER MODEL as an input.
3.	The RESNET DEEP LEARNING CLASSIFIER MODEL's job is to divide MRI scans into two categories: those in which a tumor is discovered and those in which a tumor is not discovered.
4.	As a result, if the tumor is not found, the patient is considered healthy.
5.	If a tumor is found, the information is sent to the RESUNET SEGMENTATION MODEL.
6.	Using the RESUNET SEGMENTATION MODEL, the exact location of the tumor is determined based on the pixelated level.

## OUTPUT

![image](https://github.com/chaitanyaamle/Brain-Tumor-Diagnosis/assets/30501921/dbc7bdd7-298e-4e12-a225-f4ea90171324)
![image](https://github.com/chaitanyaamle/Brain-Tumor-Diagnosis/assets/30501921/50af12e5-5d3e-4cc7-a12e-e58a18c1789e)

