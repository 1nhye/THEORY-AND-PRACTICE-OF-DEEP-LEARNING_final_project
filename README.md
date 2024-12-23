# Deepfake Detection <!-- omit from toc -->

<div align="center">
<h3>24-2 딥러닝 이론과 실재 final project</h3>

<em>딥페이크 탐지 모델</em>

</div>


## 문제 정의
### 불법 음란물 유포로 인한 피해 확산 <!-- omit from toc -->
생성형 AI의 발전과 함께 다양한 문제가 발생하고 있으며, 최근 주목받고 있는 문제 중 하나는 딥페이크 기술을 이용한 음란물 생성 및 유포입니다. 2023년 미국 사이버보안 업체 Security Hero의 보고서에 따르면, 딥페이크 포르노 범죄율이 가장 높은 나라는 대한민국으로, 사태의 심각성을 보여줍니다.


### 유명인사 이외의 일반인에 대한 딥페이크 영상 유포 <!-- omit from toc -->
기술 발전과 편리함의 증가로 인해 이제는 유명인뿐만 아니라 일반인들도 딥페이크 음란물의 피해자가 되고 있습니다. 예를 들어, 2023년 기준 딥페이크 음란물로 피해를 입은 10대 청소년은 86명이었으나, 2024년 8월까지 그 수가 238명으로 급증했습니다.


## 세부 목표

1. 범용적이고 광범위한 딥페이크 탐지 솔루션 개발
2. 각종 모델들의 성능 비교 및 분석
3. 실시간 딥페이크 탐지 서비스 구현


## How to run
`python final_inference_roi.py --video_path ./chimchak.mp4 --config_path /root/THEORY-AND-PRACTICE-OF-DEEP-LEARNING_final_project/25th-conference-fakebusters/model/roi_extractor/config.yaml`
