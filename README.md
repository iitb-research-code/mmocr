<div align="center">
  <img src="resources/mmocr-logo.png" width="500px"/>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">OpenMMLab website</font></b>
    <sup>
      <a href="https://openmmlab.com">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">OpenMMLab platform</font></b>
    <sup>
      <a href="https://platform.openmmlab.com">
        <i><font size="4">TRY IT OUT</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>

[![build](https://github.com/open-mmlab/mmocr/workflows/build/badge.svg)](https://github.com/open-mmlab/mmocr/actions)
[![docs](https://readthedocs.org/projects/mmocr/badge/?version=dev-1.x)](https://mmocr.readthedocs.io/en/dev-1.x/?badge=dev-1.x)
[![codecov](https://codecov.io/gh/open-mmlab/mmocr/branch/main/graph/badge.svg)](https://codecov.io/gh/open-mmlab/mmocr)
[![license](https://img.shields.io/github/license/open-mmlab/mmocr.svg)](https://github.com/open-mmlab/mmocr/blob/main/LICENSE)
[![PyPI](https://badge.fury.io/py/mmocr.svg)](https://pypi.org/project/mmocr/)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/open-mmlab/mmocr.svg)](https://github.com/open-mmlab/mmocr/issues)
[![Percentage of issues still open](https://isitmaintained.com/badge/open/open-mmlab/mmocr.svg)](https://github.com/open-mmlab/mmocr/issues)
<a href="https://console.tiyaro.ai/explore?q=mmocr&pub=mmocr"> <img src="https://tiyaro-public-docs.s3.us-west-2.amazonaws.com/assets/try_on_tiyaro_badge.svg"></a>

[📘Documentation](https://mmocr.readthedocs.io/en/dev-1.x/) |
[🛠️Installation](https://mmocr.readthedocs.io/en/dev-1.x/get_started/install.html) |
[👀Model Zoo](https://mmocr.readthedocs.io/en/dev-1.x/modelzoo.html) |
[🆕Update News](https://mmocr.readthedocs.io/en/dev-1.x/notes/changelog.html) |
[🤔Reporting Issues](https://github.com/open-mmlab/mmocr/issues/new/choose)

</div>

<div align="center">

English | [简体中文](README_zh-CN.md)

</div>
<div align="center">
  <a href="https://openmmlab.medium.com/" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219255827-67c1a27f-f8c5-46a9-811d-5e57448c61d1.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://discord.gg/raweFPmdzG" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218347213-c080267f-cbb6-443e-8532-8e1ed9a58ea9.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://twitter.com/OpenMMLab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346637-d30c8a0f-3eba-4699-8131-512fb06d46db.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://www.youtube.com/openmmlab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346691-ceb2116a-465a-40af-8424-9f30d2348ca9.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://space.bilibili.com/1293512903" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219026751-d7d14cce-a7c9-4e82-9942-8375fca65b99.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://www.zhihu.com/people/openmmlab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219026120-ba71e48b-6e94-4bd4-b4e9-b7d175b5e362.png" width="3%" alt="" /></a>
</div>

## Latest Updates

**The default branch is now `main` and the code on the branch has been upgraded to v1.0.0. The old `main` branch (v0.6.3) code now exists on the `0.x` branch.** If you have been using the `main` branch and encounter upgrade issues, please read the [Migration Guide](https://mmocr.readthedocs.io/en/dev-1.x/migration/overview.html) and notes on [Branches](https://mmocr.readthedocs.io/en/dev-1.x/migration/branches.html) .

v1.0.0 was released in 2023-04-06. Major updates from 1.0.0rc6 include:

1. Support for SCUT-CTW1500, SynthText, and MJSynth datasets in Dataset Preparer
2. Updated FAQ and documentation
3. Deprecation of file_client_args in favor of backend_args
4. Added a new MMOCR tutorial notebook

To know more about the updates in MMOCR 1.0, please refer to [What's New in MMOCR 1.x](https://mmocr.readthedocs.io/en/dev-1.x/migration/news.html), or
Read [Changelog](https://mmocr.readthedocs.io/en/dev-1.x/notes/changelog.html) for more details!

## Introduction

MMOCR is an open-source toolbox based on PyTorch and mmdetection for text detection, text recognition, and the corresponding downstream tasks including key information extraction. It is part of the [OpenMMLab](https://openmmlab.com/) project.

The main branch works with **PyTorch 1.6+**.

<div align="center">
  <img src="https://user-images.githubusercontent.com/24622904/187838618-1fdc61c0-2d46-49f9-8502-976ffdf01f28.png"/>
</div>

### Major Features

- **Comprehensive Pipeline**

  The toolbox supports not only text detection and text recognition, but also their downstream tasks such as key information extraction.

- **Multiple Models**

  The toolbox supports a wide variety of state-of-the-art models for text detection, text recognition and key information extraction.

- **Modular Design**

  The modular design of MMOCR enables users to define their own optimizers, data preprocessors, and model components such as backbones, necks and heads as well as losses. Please refer to [Overview](https://mmocr.readthedocs.io/en/dev-1.x/get_started/overview.html) for how to construct a customized model.

- **Numerous Utilities**

  The toolbox provides a comprehensive set of utilities which can help users assess the performance of models. It includes visualizers which allow visualization of images, ground truths as well as predicted bounding boxes, and a validation tool for evaluating checkpoints during training.  It also includes data converters to demonstrate how to convert your own data to the annotation files which the toolbox supports.

## Installation

MMOCR depends on [PyTorch](https://pytorch.org/), [MMEngine](https://github.com/open-mmlab/mmengine), [MMCV](https://github.com/open-mmlab/mmcv) and [MMDetection](https://github.com/open-mmlab/mmdetection).
Below are quick steps for installation.
Please refer to [Install Guide](https://mmocr.readthedocs.io/en/dev-1.x/get_started/install.html) for more detailed instruction.

```shell
conda create -n open-mmlab python=3.8 pytorch=1.10 cudatoolkit=11.3 torchvision -c pytorch -y
conda activate open-mmlab
pip3 install openmim
git clone https://github.com/open-mmlab/mmocr.git
cd mmocr
mim install -e .
```

## Get Started

Please see [Quick Run](https://mmocr.readthedocs.io/en/dev-1.x/get_started/quick_run.html) for the basic usage of MMOCR.

## [Model Zoo](https://mmocr.readthedocs.io/en/dev-1.x/modelzoo.html)

Supported algorithms:

<details open>
<summary>BackBone</summary>

- [x] [oCLIP](configs/backbone/oclip/README.md) (ECCV'2022)

</details>

<details open>
<summary>Text Detection</summary>

- [x] [DBNet](configs/textdet/dbnet/README.md) (AAAI'2020) / [DBNet++](configs/textdet/dbnetpp/README.md) (TPAMI'2022)
- [x] [Mask R-CNN](configs/textdet/maskrcnn/README.md) (ICCV'2017)
- [x] [PANet](configs/textdet/panet/README.md) (ICCV'2019)
- [x] [PSENet](configs/textdet/psenet/README.md) (CVPR'2019)
- [x] [TextSnake](configs/textdet/textsnake/README.md) (ECCV'2018)
- [x] [DRRG](configs/textdet/drrg/README.md) (CVPR'2020)
- [x] [FCENet](configs/textdet/fcenet/README.md) (CVPR'2021)

</details>

<details open>
<summary>Text Recognition</summary>

- [x] [ABINet](configs/textrecog/abinet/README.md) (CVPR'2021)
- [x] [ASTER](configs/textrecog/aster/README.md) (TPAMI'2018)
- [x] [CRNN](configs/textrecog/crnn/README.md) (TPAMI'2016)
- [x] [MASTER](configs/textrecog/master/README.md) (PR'2021)
- [x] [NRTR](configs/textrecog/nrtr/README.md) (ICDAR'2019)
- [x] [RobustScanner](configs/textrecog/robust_scanner/README.md) (ECCV'2020)
- [x] [SAR](configs/textrecog/sar/README.md) (AAAI'2019)
- [x] [SATRN](configs/textrecog/satrn/README.md) (CVPR'2020 Workshop on Text and Documents in the Deep Learning Era)
- [x] [SVTR](configs/textrecog/svtr/README.md) (IJCAI'2022)

</details>

<details open>
<summary>Key Information Extraction</summary>

- [x] [SDMG-R](configs/kie/sdmgr/README.md) (ArXiv'2021)

</details>

<details open>
<summary>Text Spotting</summary>

- [x] [ABCNet](projects/ABCNet/README.md) (CVPR'2020)
- [x] [ABCNetV2](projects/ABCNet/README_V2.md) (TPAMI'2021)
- [x] [SPTS](projects/SPTS/README.md) (ACM MM'2022)

</details>

Please refer to [model_zoo](https://mmocr.readthedocs.io/en/dev-1.x/modelzoo.html) for more details.

## Projects

[Here](projects/README.md) are some implementations of SOTA models and solutions built on MMOCR, which are supported and maintained by community users. These projects demonstrate the best practices based on MMOCR for research and product development. We welcome and appreciate all the contributions to OpenMMLab ecosystem.

## Contributing

We appreciate all contributions to improve MMOCR. Please refer to [CONTRIBUTING.md](.github/CONTRIBUTING.md) for the contributing guidelines.

## Acknowledgement

MMOCR is an open-source project that is contributed by researchers and engineers from various colleges and companies. We appreciate all the contributors who implement their methods or add new features, as well as users who give valuable feedbacks.
We hope the toolbox and benchmark could serve the growing research community by providing a flexible toolkit to reimplement existing methods and develop their own new OCR methods.

## Citation

If you find this project useful in your research, please consider cite:

```bibtex
@article{mmocr2021,
    title={MMOCR:  A Comprehensive Toolbox for Text Detection, Recognition and Understanding},
    author={Kuang, Zhanghui and Sun, Hongbin and Li, Zhizhong and Yue, Xiaoyu and Lin, Tsui Hin and Chen, Jianyong and Wei, Huaqiang and Zhu, Yiqin and Gao, Tong and Zhang, Wenwei and Chen, Kai and Zhang, Wayne and Lin, Dahua},
    journal= {arXiv preprint arXiv:2108.06543},
    year={2021}
}
```

## License

This project is released under the [Apache 2.0 license](LICENSE).

## To train a mmocr text recognition model on your dataset
1) Download the dataset and place it in the required folder.
2) First create a vocab file that consists of the characters to be expected in your dataset and store it in ```dicts``` folder.
3) Now write a config file for the dataset and store it in ```configs/textrecog/_base_/datasets``` folder.
4) Then write a config file for any of the models provided by mmocr and store it in ```configs/textrecog/model_name```. You may have to edit the base config file and the main config file according to your dataset.

## To train crnn model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```configs/textrecog/crnn/_base_crnn_mini-vgg.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
5) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_crnn_mini-vgg_5e_indic.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. ```crnn_mini-vgg_5e_indic.py``` is located in ```configs/textrecog/crnn/```
6) Checkpoints and training information logs will be saved in ```tools/work_dirs/crnn_mini-vgg_5e_indic``` directory.

## To train abinet model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```configs/textrecog/abinet/_base_abinet-vision.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
5) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_abinet_indic.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. ```abinet_indic.py``` is located in ```configs/textrecog/abinet/```
6) Checkpoints and training information logs will be saved in ```tools/work_dirs/abinet_indic``` directory.

## To train aster model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```configs/textrecog/aster/_base_aster.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
5) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_aster_indic.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. ```aster_indic.py``` is located in ```configs/textrecog/aster/```
6) Checkpoints and training information logs will be saved in ```tools/work_dirs/aster_indic``` directory.

## To train nrtr model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```nrtr``` we have 2 models of approach - ```modality-transform```, ```resnet31```.
5) For ```modality-transform``` model in ```configs/textrecog/nrtr/_base_nrtr_modality-transform.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
6) For ```resnet31``` model in ```configs/textrecog/nrtr/_base_nrtr_resnet31.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```. 
7) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_nrtr_indic_modality_transform.py}
   python ${path_to_train.py} ${path_to_nrtr_resnet_indic.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. ```nrtr_indic_modality_transform.py``` and ```nrtr_resnet_indic.py``` are located in ```configs/textrecog/nrtr/```
8) Checkpoints and training information logs will be saved in ```tools/work_dirs/nrtr_resnet_indic``` or ```tools/work_dirs/nrtr_indic_modality_transform``` directory.

## To train robust_scanner model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```configs/textrecog/robust_scanner/_base_robustscanner_resnet31.py.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
5) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_robustscanner_resnet_indic.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. ```robustscanner_resnet_indic.py``` is located in ```configs/textrecog/robust_scanner/```
6) Checkpoints and training information logs will be saved in ```tools/work_dirs/robustscanner_resnet_indic``` directory.
## To train svtr model on hindi dataset
1) Download the dataset and place it in the required folder.
2) Check the vocab file in ```dicts/hindi_vocab.txt``` directory.
3) In ```configs/textrecog/_base_/datasets/hindi_train.py```
   1. Change the ```hindi_textrecog_data_root``` to the path of the dataset folder containing ```train``` and ```test``` images.
   2. Change the ```ann_file``` to path of the JSON file containing annotations of train and test data in ```hindi_textrecog_train``` and ```hindi_textrecog_test``` respectively.
4) In ```svtr``` we have 4 models of approach - ```svtr-tiny```, ```svtr-small```, ```svtr-base```, ```svtr-large```.
5) For all models in ```configs/textrecog/svtr/_base_svtr-tiny.py``` change ```dict_file``` in ```dictionary``` to path of the vocab file i.e. ```dicts/hindi_vocab.txt```.
7) Now in terminal run the command
   ```bibtex
   python ${path_to_train.py} ${path_to_svtr_tiny_indic.py}
   python ${path_to_train.py} ${path_to_svtr-small_20e_st_mj.py}
   python ${path_to_train.py} ${path_to_svtr-base_20e_st_mj.py}
   python ${path_to_train.py} ${path_to_svtr-large_20e_st_mj.py}
   ```
   1. ```train.py``` is located in ```tools/train.py```
   2. model config files are located in ```configs/textrecog/svtr/```
8) Checkpoints and training information logs will be saved in ```tools/work_dirs/svtr_model_name``` directory.

## Steps for inference using detection
1) Download the model weights of one of the detection models.
   ```
   https://mmocr.readthedocs.io/en/latest/textdet_models.html
   ```
2) Run the file ```det_inference.py``` in ```inference``` folder in terminal.
   ```
   python det_inference.py
   ```
3) Enter the path for images.
4) Enter the path for detection model weights.
5) Enter the path for the detection model config file.
6) Enter the path for the output directory.
7) The results will be stored in the output directory in two folders.
   1. ```preds``` folder contains the json files.
   2. ```vis``` folder contains the result images.

## Steps for inference using recognition
1) Download the model weights of one of the recognition models.
   ```
   https://mmocr.readthedocs.io/en/latest/textrecog_models.html
   ```
2) Run the file ```rec_inference.py``` in ```inference``` folder in terminal.
   ```
   python rec_inference.py
   ```
3) Enter the path for images.
4) Enter the path for recognition model weights.
5) Enter the path for the recognition model config file.
6) Enter the path for the output directory.
7) The results will be stored in the output directory in two folders.
   1. ```preds``` folder contains the json files.
   2. ```vis``` folder contains the result images.

## Steps for inference using end-to-end OCR
1) Download the model weights of one of the detection models and one of the recognition models.
   ```
   https://mmocr.readthedocs.io/en/latest/textdet_models.html
   https://mmocr.readthedocs.io/en/latest/textrecog_models.html
   ```
2) Run the file ```inferencing.py``` in ```inference``` folder in terminal.
   ```
   python inferencing.py
   ```
3) Enter the path for images.
4) Enter the path for recognition model weights.
5) Enter the path for the recognition model config file.
6) Enter the path for detection model weights.
7) Enter the path for detection model config file.
8) Enter the path for output directory.
9) The results will be stored in output directory in two folders.
   1. ```preds``` folder contains the json files.
   2. ```vis``` folder contains the result images.
