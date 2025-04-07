# 🏠 부동산 허위매물 분류 프로젝트

이 프로젝트는 **부동산 플랫폼에 등록된 매물 정보가 허위인지 여부를 분류**하는 머신러닝 모델을 개발한 작업입니다.
[데이콘 주소](https://dacon.io/competitions/official/236439/overview/description)

## 📌 주요 내용

- **데이터 전처리**  
  - 결측값 처리  
  - 이상치 제거  
  - 범주형 변수 인코딩 등  

- **모델 학습**  
  - RandomForestClassifier 기반 분류 모델 사용  

- **성과 평가**  
  - 정확도, F1-score

- **시각화**  
  - 변수 중요도 시각화  
  - 혼동 행렬을 통한 예측 결과 분석  

- **목표**  
  - 부동산 플랫폼의 **허위매물 자동 탐지 시스템** 기반 마련
  
- **최종 모델 성능**  
  - LightGBM parameter tuning with custom parameter
  - private score = 0.8905
