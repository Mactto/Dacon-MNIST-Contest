# Dacon-MNIST-Contest

---

 ### MNIST 변형 데이터 예측 대회
 1. 목표 : 글자에 가려진 숫자 예측
 2. 주최 : DACON
 3. 대회 링크 : [https://dacon.io/competitions/official/235626/overview/](https://dacon.io/competitions/official/235626/overview/)
 
---

#### 개발 환경

* 사용환경 : Jupyter Notebook   
* 사용언어 : Python   
* 사용 프레임워크 : Tensorflow 2.0

---

#### 데이터 셋
train.csv : 훈련 데이터 (2048개)    
test.csv : 검증 데이터 (20480개)    
submission.csv : 제출 양식    

---

#### 분석

※ 특이하게도 훈련데이터 셋보다 검증 데이터 셋이 훨씬 많음 ( 2048(train) < 20480(test) )   

* 샘플 이미지 출력 결과

[ D ] 라는 알파벳 안에 어떤 숫자가 가려져 있음 (노란색 부분이 숫자)    
Augmentation 적용 필요 -> ImageGenerator 사용
