# My Project Plan
***Note***: This document is written merely as an illustrative example, and does not provide any working guide to an actual project.

### Proposal
---
I am planning to make a computer vision software that detects objects in images.  
In order to build it, I will use opencv, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org) or [PyTorch](https://pytorch.org), and other open-source software. 

For example, the objects in the following images were detected using [mmdetection](https://github.com/open-mmlab/mmdetection):

![image](https://github.com/user-attachments/assets/e24e27df-440e-4a8c-b39e-441ecd3fd762)

---

### Dependencies

- python
- opencv-python
- tensorflow
- openmmlab
- package manager

### Installation

In a bash terminal, run the following commands (*Do NOT actually run these commands in your computer*): 
```sh
$ sudo apt update
$ conda create -n cv_detection
$ conda activate cv_detection
$ python --version
$ python example.py
