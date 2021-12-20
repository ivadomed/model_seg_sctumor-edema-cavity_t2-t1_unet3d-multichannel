# Multiclass tumor segmentation model
Model to segment spinal cord tumor, edema, and cavity using as input T2w and gadolinium-enhanced T1w MRI scans.

## Overview of the model

![Model](model_output.png)

## Data
The model was trained using the private data acquired from Beijing Tiantan Hospital, Capital Medical University from October 2012 to September 2018 (internally stored: git-annex/datasets/beijing-tumor). 

## Training
The training was done using [ivadomed](ivadomed.org) v2.6.1 with this [configuration file](https://github.com/ivadomed/model_seg_sctumor-edema-cavity_t2-t1_unet3d-multichannel/blob/main/model_seg_sctumor-edema-cavity_t2-t1_unet3d-multichannel.json).

## Citation

For more details on the implementation see the [full paper](https://doi.org/10.1016/j.nicl.2021.102766).

```
@article{LEMAY2021102766,
title = {Automatic multiclass intramedullary spinal cord tumor segmentation on MRI with deep learning},
journal = {NeuroImage: Clinical},
volume = {31},
pages = {102766},
year = {2021},
issn = {2213-1582},
doi = {https://doi.org/10.1016/j.nicl.2021.102766},
url = {https://www.sciencedirect.com/science/article/pii/S2213158221002102},
author = {Andreanne Lemay and Charley Gros and Zhizheng Zhuo and Jie Zhang and Yunyun Duan and Julien Cohen-Adad and Yaou Liu},
keywords = {Deep learning, Automatic segmentation, Spinal cord tumor, MRI, Multiclass, CNN}
}
```

Lemay, A., Gros, C., Zhuo, Z., Zhang, J., Duan, Y., Cohen-Adad, J., & Liu, Y. (2021). Automatic multiclass intramedullary spinal cord tumor segmentation on MRI with deep learning. NeuroImage. Clinical, 31, 102766. https://doi.org/10.1016/j.nicl.2021.102766
