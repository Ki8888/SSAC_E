# 세 가지 품종의 아이리스 분류하기


## 목표  

- scikit-learn에 내장되어 있는 예제 데이터셋의 종류를 알고 활용할 수 있다.
- scikit-learn에 내장되어 있는 분류 모델들을 학습시키고 예측해 볼 수 있다.
- 모델의 성능을 평가하는 지표의 종류에 대해 이해하고, 활용 및 확인해 볼 수 있다.
- Decision Tree, SGD, RandomForest, 로지스틱 회귀 모델을 활용해서 간단하게 학습 및 예측해 볼 수 있다.
- 데이터셋을 사용해서 스스로 분류 기초 실습을 진행할 수 있다.


## 연습  

* sklearn datasetd에서  아이리스 데이터셋 불러오기
* 수치데이터를 row로, 아이리스의 4가지 특징을 컬럼으로 데이터프레임 생성
* 아이리스 데이터는 균등한편
* 아이리스 타겟데이터를 기존 데이터프레임에 추가
* train_test_split 이용 데이터 분할 후 훈련


## 실습

* sklearn dataset에서 손글씨, 와인, 유방암 데이터 분류하기

* 학습가능한 형태로 데이터 가공

* train_test_split으로 데이터 분할

* 다양한 분류모델로 학습시킴 - DecisionTree, RandomForest, 

  ​												SVM, SGD Classfier, Logistic Regression

* classification report로 accuracy, precision, recall, f1 score등 확인하여,

  각 데이터마다 가장 성능 좋은 모델 찾기 진행
  

# 소감

프로그램에서 제공하는 잘 정리되어있는 기초 데이터로 기본적인 모델로 학습을 진행해봤다.

기본적인 모델임에도 정확도가 90%정도 나왔지만, 다른 수치들도 신경써야 신뢰할 수 있는 모델을 생성할 수 있다. 

데이터의 문제로 수치가 1로 나와버리는 경우를 개선할 필요가 있어보인다.