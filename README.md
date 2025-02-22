# MeshGraphormer ✨✨


This is our research code of [Mesh Graphormer](https://arxiv.org/abs/2104.00272). 

Mesh Graphormer is a new transformer-based method for human pose and mesh reconsruction from an input image. In this work, we study how to combine graph convolutions and self-attentions in a transformer to better model both local and global interactions. 

 <img src="docs/graphormer_overview.png" width="650"> 

 <img src="docs/Fig1.gif" width="200"> <img src="docs/Fig2.gif" width="200"> <img src="docs/Fig3.gif" width="200">  <img src="docs/Fig4.gif" width="200"> 

 <img src="https://datarelease.blob.core.windows.net/metro/graphormer_demo.gif" width="200">

## Installation
Check [INSTALL.md](docs/INSTALL.md) for installation instructions.


## Model Zoo and Download
Please download our pre-trained models and other relevant files that are important to run our code. 

Check [DOWNLOAD.md](docs/DOWNLOAD.md) for details. 

## Experiments
We provide python codes for training and evaluation.

Check [EXP.md](docs/EXP.md) for details.


## License

Our research code is released under the MIT license. See [LICENSE](LICENSE) for details. 

We use submodules from third parties, such as [huggingface/transformers](https://github.com/huggingface/transformers) and [hassony2/manopth](https://github.com/hassony2/manopth). Please see [NOTICE](NOTICE.md) for details. 

Our models have dependency with SMPL and MANO models. Please note that any use of SMPL models and MANO models are subject to **Software Copyright License for non-commercial scientific research purposes**. Please see [SMPL-Model License](https://smpl.is.tue.mpg.de/modellicense) and [MANO License](https://mano.is.tue.mpg.de/license) for details.


## Contributing 

We welcome contributions and suggestions. Please check [CONTRIBUTE](docs/CONTRIBUTE.md) and [CODE_OF_CONDUCT](docs/CODE_OF_CONDUCT.md) for details. 


## Citations
If you find our work useful in your research, please consider citing:

```bibtex
@inproceedings{lin2021-mesh-graphormer,
author = {Lin, Kevin and Wang, Lijuan and Liu, Zicheng},
title = {Mesh Graphormer},
booktitle = {ICCV},
year = {2021},
}
```


## Acknowledgments

Our implementation and experiments are built on top of open-source GitHub repositories. We thank all the authors who made their code public, which tremendously accelerates our project progress. If you find these works helpful, please consider citing them as well.

[huggingface/transformers](https://github.com/huggingface/transformers) 

[HRNet/HRNet-Image-Classification](https://github.com/HRNet/HRNet-Image-Classification) 

[nkolot/GraphCMR](https://github.com/nkolot/GraphCMR) 

[akanazawa/hmr](https://github.com/akanazawa/hmr) 

[MandyMo/pytorch_HMR](https://github.com/MandyMo/pytorch_HMR) 

[hassony2/manopth](https://github.com/hassony2/manopth) 

[hongsukchoi/Pose2Mesh_RELEASE](https://github.com/hongsukchoi/Pose2Mesh_RELEASE) 

[mks0601/I2L-MeshNet_RELEASE](https://github.com/mks0601/I2L-MeshNet_RELEASE) 

[open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) 
