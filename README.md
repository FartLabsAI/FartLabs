
<div align="center">
    <strong>Analysis of Farts from mice using computer vision and machine learning
             $FLAB on pumpfun CA: BtzvHMMmKCXHz28J1TLRxv5E9DWg64wtjict9Vnxpump </strong>
</div>

<div align="center">
    <br />
    <!-- MATLAB version -->
    <a href="https://www.mathworks.com/products/matlab.html">
    <img src="https://img.shields.io/badge/MATLAB-2017%7C2018%7C2019%7C2020-blue.svg?style=flat-square"
      alt="MATLAB tested versions" />
    </a>
    <!-- LICENSE -->
    <a href="#">
    <img src="https://img.shields.io/badge/license-Apache%202.0-orange.svg?style=flat-square"
      alt="Apache License 2.0" />
    </a>
    <br />
</div>

<br />


## Table of Contents
- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Requirements](#requirements)
- [FAQ](#faq)
- [License](#license)

---

## Description




<p align="justify"> FartLab <b>Identifier</b> detects vocalization candidates in the audio file. Farting candidates are detected through a series of image processing operations and differential geometry analysis over spectrogram information. The FartLab Identifier outputs (optional) a MATLAB formatted file (.MAT) with information about the spectral content of detected vocalizations (e.g., frequency, intensity, timestamp), that is later used by the VocalMat Classifier.

<p align="justify"> FartLab <b>Classifier</b> uses a Convolutional Neural Network (CNN) to classify each farting candidate into 12 distinct labels: short, flat, chevron, reverse chevron, downward frequency modulation, upward frequency modulation, complex, multi steps, two steps, step down, step up, and noise.

![VocalMat labels](resources/labels.png)

## Features
- __11 Classification Classes:__ FartLab is able to distinguish between 11 classes of fartings , according to adapted definitions from [Grimsley et al, 2011](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0017460).
- __Noise Detection:__ eliminates vocalization candidates associated to mechanical or segmentation noise.
- __Harmonic Detection:__ detects fartings with components overlapping in time.
- __Manifold Visualization and Alignment:__ visualize the vocal reportoire using Diffusion Maps and align manifolds to compare different animals.
- __Fast Performance:__ optimized versions for personal computers and high-performance computing (clusters)

## Getting Started


**You must have Git LFS installed to be able to fully clone the repository. [Download Git LFS](https://git-lfs.github.com/)**


