

### Introduction

This is the research code for the CVIU 2017 paper: 

[Chao Ma](https://www.chaoma.info), [Chih-Yuan Yang](https://scholar.google.com/citations?user=eUbmKwYAAAAJ&hl=en), [Xiaokang Yang](http://english.seiee.sjtu.edu.cn/english/detail/842_802.htm), and [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/), " Learning a No-Reference Quality Metric for Single-Image Super-Rolution", CVIU 2017. 

For more details, please visit our [Project page](https://www.chaoma.info/sr-metric)

### Abstract

Numerous single-image super-resolution algorithms have been proposed in the literature, but few studies address the problem of performance evaluation based on visual perception. While most super-resolution images are evaluated by full-reference metrics, the effectiveness is not clear, and the required ground-truth images are not always available in practice. To address these problems, we conduct human subject studies using a large set of super-resolution images and propose a no-reference metric learned from visual perceptual scores. Specifically, we design three types of low-level statistical features in both spatial and frequency domains to quantify super-resolved artifacts, and learn a two-stage regression model to predict the quality scores of super-resolution images without referring ground-truth images. Extensive experimental results show that the proposed metric is effective and efficient to assess the quality of super-resolution images based on human perception. 


### Quick Start

run "demo.m"


### Citation

If you find the code and dataset useful in your research, please consider citing:

    @article{Ma-Metric-2017,
        title={Learning a No-Reference Quality Metric for Single-Image Super-Rolution},
        Author = {Ma, Chao and Yang, Chih-Yuan and Yang, Xiaokang and Yang, Ming-Hsuan},
        journal = {Computer Vision and Image Understanding},
        pages={1-16},
        Year = {2017}
    }
