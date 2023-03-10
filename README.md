# SVM 시스템

![SVM 시스템](/uploads/3bb93b090a1ad9baf2e30661eecf5712/output.gif)

본 프로젝트(이하 **SVM 시스템**)의 WIKI는 후임 담당자, 혹은 N기 교육생이 **SVM 시스템**를 실행 및 테스트를 하거나 **SVM 시스템**에 사용된 외부 서비스를 사용하기 위한 코드 학습과 개선에 도움이 되고 코드를 활용할 수 있도록 하기 위해 작성되었습니다.

**SVM(Surround View Monitor), 차량 주변 360도를 Top View로 확인하는 운전 보조 시스템**

> 많은 운전자들이 자동차 주차 시 사각지대로 인해 어려움을 겪습니다. 이는 자동차의 크기가 클수록, 길이 좁아질수록 정도가 심해집니다. \
> \
> 이러한 문제점을 해결하고자 SVM(Surround View Monitor) 시스템은 차량의 전후좌우 4방향의 카메라 영상을 합성한 Top View 영상을 제공합니다. \
> \
> SVM 시스템을 통해 주차 및 주행 시 사고를 줄이고 편리함을 제공받을 수 있습니다.


## 팀원
김기한, 김이랑, 김필재, 박주현(팀장), 임영선, 임진현

## 프로젝트 기간
2022.10.11 ~ 2022.11.21 (7주)

### 대표 기술스택

1. Language: Python(3.8.13)
2. Library : openCV (4.6.0)
3. IDE : Visual Studio Code (1.70.0)

## 프로젝트 파일 구조

```
📦7th_svm
├─ 📂camaraTool
├─ 📂data
│  ├─ 📂asset
│  ├─ 📂images
│  │  ├─ 📂extrinsic_images
│  │  ├─ 📂intrinsic_images
│  │  └─ 📂original_images
│  └─ 📂output
├─ 📂exec
├─ 📂extrinsicCalibration
├─ 📂intrinsicCalibration
├─ 📂imageManipulation
├─ 📜main.py
├─ 📜README.md
└─ 📜test.py
```



## 구현 과정

### 1. 왜곡보정
### 2. 시점변환
### 3. 합성 / 색 보정
### 4. FPS 최적화
