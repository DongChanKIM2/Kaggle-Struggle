# Kaggle-Struggle
## 캐글 프로젝트

### 01 타이타닉 생존 예측
+ 변수 전처리 활용도에 따른 정확성 상승
+ One-hot encoding 적용 후 여러 Predict 결과 비교 후 가장 좋은 기법 선택

### 02 시계열 예측
#### 시계열 예측 사용주제
+ 비즈니스 예측
+ 과거의 습관 이해
+ 미래 예측
+ 현재 성과 평가
#### 시계열 예측 사용불가 주제
+ dependent variable y is constant ex)y=4
+ dependent variable is denoted as a mathematical function ex)y=sin(x)
#### 시계열 예측 구성요소
+ 트랜드 - 데이터의 상향, 하향
+ Seasonality - Ex)아이스크림은 여름시즌에 잘 팔림
+ Noise or Irregularity - Spikes at random interval
+ Cyclicity - behavior that repeats itself after large interval of time
#### 시계열 요구 조건
+ Stationarity - has constant mean / constant variance or standard deviation
+ Auto-covariance(자기공분산) should not depend on time 
#### P, Q 결정
+ From PACF(at y=0), get P
+ From ACF(at y=0), get Q
#### 그 외의 용어
+ ACF(Auto Correlation Function)
+ PACF(Partial Auto Correlation Function)






