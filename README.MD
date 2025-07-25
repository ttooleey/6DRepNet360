[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-robust-and-unconstrained-full-range/head-pose-estimation-on-biwi)](https://paperswithcode.com/sota/head-pose-estimation-on-biwi?p=towards-robust-and-unconstrained-full-range)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-robust-and-unconstrained-full-range/head-pose-estimation-on-cmu-panoptic-300w-lp)](https://paperswithcode.com/sota/head-pose-estimation-on-cmu-panoptic-300w-lp?p=towards-robust-and-unconstrained-full-range)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-robust-and-unconstrained-full-range/head-pose-estimation-on-aflw2000)](https://paperswithcode.com/sota/head-pose-estimation-on-aflw2000?p=towards-robust-and-unconstrained-full-range)
# <div align="center"> **6DRepNet360** </div>

<p align="center">
  <img src="https://github.com/thohemp/archive/blob/main/6drepnet360.gif" alt="animated" />
</p>

## Overview

This is a PyTorch implementation of 6DRepNet360 specified in 
["Towards Robust and Unconstrained Full Range of Rotation Head Pose Estimation"](https://ieeexplore.ieee.org/document/10477888) 
,  IEEE Transactions on Image Processing 2024

## Models
|Model| Description|Download|
|---|---|---|
|6DRepNet360 Full Rotation | Fine-tuned on 300W-LP + Panoptic|  [Download](https://cloud.ovgu.de/s/TewGC9TDLGgKkmS/download/6DRepNet360_Full-Rotation_300W_LP+Panoptic.pth)
|6DRepNet360 | Fine-tuned on 300W-LP | [Download](https://cloud.ovgu.de/s/wWCitDxp9t79xkP/download/6DRepNet360_300W_LP.pth)


## Usage

For usage instructions, please refer to the README.md in the example directory.

## **Citing**

If you find our work useful, please cite the paper:

```BibTeX
@ARTICLE{10477888,
  author={Hempel, Thorsten and Abdelrahman, Ahmed A. and Al-Hamadi, Ayoub},
  journal={IEEE Transactions on Image Processing}, 
  title={Toward Robust and Unconstrained Full Range of Rotation Head Pose Estimation}, 
  year={2024},
  volume={33},
  number={},
  pages={2377-2387},
  doi={10.1109/TIP.2024.3378180}}
```
