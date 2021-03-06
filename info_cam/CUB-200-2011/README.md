# InfoCAM: Informative Class Activation Map (CUB-200-2011)

**Acknowledgment: This repository is based on the implementation by:**
[ADL: Attention-based Dropout Layer for Weakly Supervised Object Localization
](https://github.com/junsukchoe/ADL/tree/master/Pytorch)\
Junsuk Choe, Hyunjung Shim, CVPR 2018

This repository contains implementation for infoCAM: Informative
Class Activation Map. This is with the CUB-200-2011
dataset. For more detailed information, please refer to the paper. 

## Installation

Please install all the necessary python packages, which is easy
and intuitive if one uses a package management system like Conda.

Please download the CUB-200-2011 dataset: 
[CUB-200-2011](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html).
Please unzip this file in '../CUB_200_2011'.

Please download the pretrained [ResNet50](https://drive.google.com/open?id=0B7fNdx_jAqhtbllXbWxMVEdZclE)
pretrained model and put in './pretrained/'. 

## Usage

Please refer to the bash files in './scripts'. For example, 
to run with backbone VGG, without ADL, one can type: 
```bash
bash scripts/run_vgg_no_ADL.sh
```

Training a model takes approximately 4 hours with two 
Nvidia 2080 Ti GPUs.

For more information, please refer to the original README file. 

## License
[CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/)