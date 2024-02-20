[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/3DbKuh4a)
# Title (Please modify the title)
## Team

| ![박패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![최패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![오패캠](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [박패캠](https://github.com/UpstageAILab)             |            [이패캠](https://github.com/UpstageAILab)             |            [최패캠](https://github.com/UpstageAILab)             |            [김패캠](https://github.com/UpstageAILab)             |            [오패캠](https://github.com/UpstageAILab)             |
|                            팀장, 담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |

## 0. Overview
### Environment
- albumentations==1.3.1
ipykernel==6.27.1
ipython==8.15.0
ipywidgets==8.1.1
jupyter==1.0.0
matplotlib-inline==0.1.6
numpy==1.26.0
pandas==2.1.4
Pillow==9.4.0
timm==0.9.12


### Requirements
- _Write Requirements_

## 1. Competiton Info

### Overview

- 문서 분류 문제

### Timeline

-  February 5, 2024 - Start Date
-  February 19, 2024 - Final submission deadline

## 2. Components

### Directory

- baseline 코드 이해 및 복습


## 3. Data descrption

### Dataset overview

- train data
  - 1570
- test data
  - 3200


### EDA

- A.RandomBrightnessContrast: 밝기와 대비를 무작위로 조절
- A.GaussianBlur: 가우시안 블러를 적용하여 이미지를 흐리게 만들기
- A.CLAHE: CLAHE (Contrast Limited Adaptive Histogram Equalization)를 적용하여 이미지의 대비를 향상
- A.ElasticTransform: 탄성 변환(elastic transformation)을 적용하여 이미지를 뒤틀거나 찌그러뜨림
- A.CoarseDropout: 이미지에 무작위로 구멍을 추가

### Data Processing

- hyperparameter

- LR - 학습률(learning rate)
- EPOCHS - 전체 데이터에 대해 한번 훑어보는 횟수
- BATCH_SIZE -  한 번에 입력으로 주어지는 데이터 샘플의 수
- num_workers -  데이터 로딩에 사용되는 CPU의 워커(worker) 수

## 4. Modeling

### resnet

### CustomEfficientNet


## 5. Result

### Leader Board

- public - 0.6237
- private - 0.6266

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_
