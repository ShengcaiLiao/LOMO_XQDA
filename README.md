# LOMO_XQDA
Person Re-identification by Local Maximal Occurrence Representation and Metric Learning

# News

[Python implementation of LOMO feature extractor](https://github.com/dongb5/LOMO-feature-extractor)

# Introduction

This MATLAB package provides the LOMO feature extraction and the XQDA metric learning algorithms proposed in our CVPR 2015 paper [1].

Project page: https://liaosc.wordpress.com/2019/01/13/lomo_xqda/

# Contents

The package contains the following components.

1. /code: MATLAB codes for the LOMO feature extraction and the XQDA metric learning algorithms, as well as two demos showing how to use these two algorithms. Two functions for computing the Mahalanobis distance and the CMC curves are also provided for the evaluation purpose.

2. /bin: MEX functions for the Retinex image preprocessing. Since we are not allowed to release its source code, we provide MEX functions for both Windows and Linux, x86 and x64 platforms.

3. /images: two sample images from the VIPeR database, used to demonstrate the LOMO feature extraction.

4. /data: the extracted LOMO features for the VIPeR, QMUL Grid, CUHK Campus, and CUHK03 databases. Due to the size of the feature files, they are provided as separate downloads.

5. /results: the CMC curves reported in our CVPR 2015 paper. You can draw these curves for performance comparison.

# Usage

For a quick start, run the Demo_LOMO.m code for a demo of feature extraction, and download the extracted LOMO features on the VIPeR database from the project page and place it in the data subfolder, then run the Demo_XQDA.m example for metric learning and performance evaluation on the VIPeR database. You can run this script to reproduce our CVPR 2015 results.

# Version

Version: 1.0  
Date: 2015-05-06
 
# Author
Shengcai Liao  
Institute: National Laboratory of Pattern Recognition, 	Institute of Automation, Chinese Academy of Sciences

Email: scliao@ieee.org

# Citation

[1] Shengcai Liao, Yang Hu, Xiangyu Zhu, and Stan Z. Li. “Person re-identification by local maximal occurrence representation and metric learning.” In IEEE Conference on Computer Vision and Pattern Recognition, 2015.

@InProceedings{Liao_2015_CVPR,  
author = {Liao, Shengcai and Hu, Yang and Zhu, Xiangyu and Li, Stan Z.},  
title = {{Person Re-Identification by Local Maximal Occurrence Representation and Metric Learning}},  
booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},  
month = {June},  
year = {2015}  
}
