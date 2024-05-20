# <a href = 'https://www.notion.so/toy-project-0b2300dbdc2148a08eedde20148bc0b4'>Autonomous Driving, Perception Toy Project 

## Goals

- Object Tracking
- Image Processing

## Definitions

- Docker를 사용한 환경 설정
- Python → CPP 변환으로 한정된 자원을 효율적으로 관리
- FastAPI를 사용한 Web 배포
- DL Model 사용 / Web 배포를 통해 MLOps 이해와 Model 경량화

## Dataset

- UA-DETRAC
- KITTI Vision Benchmark Suite
- Cityscapes
- Berkley DeepDrive

## Model

**YOLOv5 + DeepSORT**
> Object Detection → YOLOv5 <br>
> Tracking → DeepSORT(강력한 실시간 Object Tracking)

## Overview

1. 환경 설정 
2. Dataset 전처리 → Model의 맞는 형식으로 변환, 지정된 Dir 구조 설계
3. Model 설정 → Train 완료 된 Backbone Model 사용  
4. FastAPI Server 구현
5. Docker를 사용해 Model 배포 
6. 유지 보수 및 모니터링

## Skills

`C++` `Python` `OpenCV` `Linux` `Docker` `Github`
