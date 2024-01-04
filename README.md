# graduation_capston - 연령과 감정 예측을 이용한 키오스크 시스템

## 프로젝트 소개
CNN 기반 딥러닝 모델 VGG16을 이용하여 사람 얼굴을 학습하여 사용자의 연령과 감정을 예측하여 그에 맞는 메뉴를 추천해주는 키오스크 시스템 을 개발하였습니다. 

## 개발 기간
2023.09~2023.12

## 개발 환경
- Google Colab Pro plus
- Visual Studio Code
---

### <age 예측 수행>

- 사용한 데이터셋 : UTK Faces 데이터셋 + Facial Age 데이터셋

- 사용한 모델 : VGG16 모델

- 수행 환경 : Colab pro plus+


* vgg16_age.ipynb : vgg16 모델을 이용하여 데이터셋 학습 진행한 파일 (딥러닝 1차 학습)

* Change_Darked.ipynb : 딥러닝 학습의 낮은 정확도 해결하기 위해 다양한 촬영 환경 고려하여 기존 데이터셋을 어둡게 변경시키는 것 진행한 파일

* Change_Lighted.ipynb : 딥러닝 학습의 낮은 정확도 해결하기 위해 다양한 촬영 환경 고려하여 기존 데이터셋을 밝게 변경시키는 것 진행한 파일

* darked_UTK.csv : 모델 학습을 위한, 라벨링 되어 있는 csv 파일

* lighted_UTK.csv : 모델 학습을 위한, 라벨링 되어 있는 csv 파일
