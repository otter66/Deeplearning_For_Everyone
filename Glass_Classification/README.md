## 유리 분류   

<br>   

### 데이터셋
- 원본 데이터셋 : 타입을 기준으로 정렬, Type(int)
- 변경 데이터셋 : 데이터의 랜덤 배치, Type(String)   

<br>   

### Type(유리 종류)의 분포   
<img align='left' src="https://raw.githubusercontent.com/otter66/Deeplearning_For_Everyone/master/Glass_Classification/images/type_distribution.png"  width="300">   

1. building windows float processed   
2. building windows non float processed   
3. vehicle windows float processed   
4. vehicle windows non float processed (none in this database)    
5. containers   
6. tableware   
7. headlamps   

<br>   

### 특성 분포
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/features_RI_Na_Ma.png?raw=true"  width="700">    
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/features_Al_Si_K.png?raw=true"  width="700">    
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/features_Ca_Ba_Fe.png?raw=true"  width="700">    

<br>   

### 상관관계 (1)
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_1.png?raw=true"  width="600">   
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_Na_1.png?raw=true"  width="900">   
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_Al_1.png?raw=true"  width="900">   
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_Ba_1.png?raw=true"  width="900">   

<br>   

### 상관관계 (2)   
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_2.png?raw=true"  width="900">   
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/correlation_Na_Al_Ba.png?raw=true"  width="600">   


<br><br><br>   

### 학습곡선 : 정렬 데이터 사용 모델
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/original_model_train.png?raw=true"  width="300">   

### 학습곡선 : 랜덤 데이터 사용 모델
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/transformation_model_train.png?raw=true"  width="300">   

### 학습곡선 : 랜덤 데이터 사용, 테스트 학습 구분 모델
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/transformation_model_train_test.png?raw=true"  width="300">   

### 학습곡선 : 랜덤 데이터 사용, k-fold 학습 모델
<img src="https://github.com/otter66/Deeplearning_For_Everyone/blob/master/Glass_Classification/images/transformation_model_kfold_train.png?raw=true"  width="300">   


<br><br><br>   

---
### 데이터셋의 출처
- [UCI](https://archive.ics.uci.edu/ml/datasets/Glass+Identification)
- [kaggle](https://www.kaggle.com/datasets/uciml/glass)
