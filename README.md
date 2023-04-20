## 简介

乳腺疾病检测一直是一个很值得研究的课题，[RSNA 2023乳腺疾病分类竞赛](https://www.kaggle.com/competitions/rsna-breast-cancer-detection) 为我们提供了丰富的乳腺图像和EHR数据信息，然而这些图像是需要进行处理的，本repo旨在构建分类、检测、分割全方位的RSNA数据使用格式。

## 开发

1. 使用[dicom-resized-png-jpg](https://www.kaggle.com/code/theoviel/dicom-resized-png-jpg) （[备用](https://github.com/mpu-tt/rsna-breast-dataset/blob/main/code/1-dicom-resized-png-jpg.ipynb) ）对原始`Dicom`图转为`png/jpg`图，转为的图像大小支持[256-1GB](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-256-pngs) 、[512-4GB](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-512-pngs) 、[768-8GB](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-768-pngs) 、[1024-14GB](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-1024-pngs) 。

## 资源

1. [RSNA2023乳腺疾病原始数据-200+GB](https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data) ，包含病人元信息和Dicom乳腺信息
2. [RSNA2023乳腺疾病PNG图256尺寸数据](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-256-pngs) 
3. [RSNA2023乳腺疾病PNG图512尺寸数据](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-512-pngs) 
4. [RSNA2023乳腺疾病PNG图768尺寸数据](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-768-pngs) 
5. [RSNA2023乳腺疾病PNG图1024尺寸数据](https://www.kaggle.com/datasets/theoviel/rsna-breast-cancer-1024-pngs)
