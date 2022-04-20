# Natural Language Processing and Prediction with ML Models

## Sentiment Analysis on Twitter Dataset

### “Tweets.csv” 파일은 트위터에서 미국의 6개 항공사(American, Delta, SouthWest, United, US Airways, Virgin America)를 언급하는 tweet 14,640개에 대한 정보를 수집한 데이터셋이다. 본 과제에서는 tweet 텍스트로부터 positive/negative/neutral 여부를 판별하기 위한 모델을 만들어본다.

• airline_sentiment: “positive”, “negative”, “neutral”  
• text: tweet 텍스트  

#### 1. 모델을 수립하기 전에 데이터의 특성을 분석한다. 시각화 도구를 적절히 활용하자.

#### 2. 텍스트 데이터에 bag-of-words 기법을 적용하기 위해 적절한 preprocessing을 수행하고, 그 결과를 분석해보자.

#### 3. 계산시간을 줄이기 위해서 첫 5,000개의 데이터만 training set으로 사용하고, 나머지 모든 데이터를 test set으로 사용한다. Training set을 사용하여 predictive model을 만들어보자.

A. 지금까지 학습한 모델을 최대한 활용해보고, 분석 과정과 결과를 report하자. 
사용하는 모델, 모델에 포함되는 파라미터에 대한 튜닝, 모델에 포함되는 feature의 수, DTM/TF-IDF 사용 여부 등이 classification accuracy에 영향을 미칠 수 있다.
[주의: 모델을 수립할 때에는 test set을 사용하여 성능을 비교할 수 없다.]  
B. 최종적으로 선택한 모델은 무엇이며 test set에 대한 accuracy는 얼마인가?  
C. 세 class (positive, negative, neutral) 중에서 어떤 class를 분류하기 어려운가?  
