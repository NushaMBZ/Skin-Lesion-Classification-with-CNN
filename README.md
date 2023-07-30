This repository focuses on the application of Convolutional Neural Network (CNN) architectures for the classification of skin lesions. Four popular CNN models, namely EfficientNet-B3, VGG16, DenseNet, and Inception V3, have been implemented and evaluated on a dataset of skin lesion images.

## Results
### Phase 01
|Models| Base Model |EfficientNet-B3 | VGG16 | DenseNet | Inception V3 |
|-|-|-|-|-|-|
|Data Augmentation|False|False|False|False|False|
|Optimizer|Adam|Adam|Adam|Adam|Adam|
|LR| 0.001| 0.001| 0.001| 0.001| 0.001| 0.001|
|LF|SparseCategoricalCrossentropy|CategoricalCrossentropy|CategoricalCrossentropy|CategoricalCrossentropy|CategoricalCrossentropy|
|Parameters|85,867|10,783,535|14,716,227|12,647,875|21,808,931|
|Depth|10|5|7|8|7|
|Validation|68%|72%|68%|73%|71%|
|Link|[BM](https://github.com/Thlurte/Skin-Lesion-Classification-with-CNN/blob/main/Base%20Model/CV_C_M_857.ipynb)|[EFB3](https://github.com/Thlurte/Skin-Lesion-Classification-with-CNN/blob/main/EfficientNet-B3/CV_C_M_859.ipynb)|[VGG16](https://github.com/Thlurte/Skin-Lesion-Classification-with-CNN/blob/main/VGG16/CV_C_M_860.ipynb)|[IV3](https://github.com/Thlurte/Skin-Lesion-Classification-with-CNN/blob/main/Inception%20V3/CV_C_M_862.ipynb)|

## Dataset
[Melanoma Detection Dataset](https://www.kaggle.com/datasets/wanderdust/skin-lesion-analysis-toward-melanoma-detection)
