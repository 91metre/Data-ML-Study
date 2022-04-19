# k-NN
## Customer Prediction 
k-NN을 활용하여 새로운 고객의 정보가 주어졌을 때 이 고객이 개인 대출 상품을 가입할 지를 예측해 보고자 한다.

CommomBank.csv 파일은 Common Bank의 예금계좌를 소유하고 있는 5,000명의 고객 정보 데이터로 다음과 같은 정보를 포함하고 있다.

• ID : 고객 ID  
• Age : 나이  
• Experience : 경력  
• Income : 연간 수입 ($1,000)  
• ZIP.code : 우편번호  
• Family : 가족 구성원 수  
• CCAvg : 월간 평균 신용카드 사용액 ($1,000)  
• Education : 1 (Undergraduate), 2 (Graduate), 3 (Advanced)  
• Mortgage : 주택 담보액  
• PersonalLoan : 개인 대출 상품 가입 여부(Reject or Accept) (0/1)  
• SecuritiesAccount : Securities account 소유 여부 (0/1)  
• CDAccount: CD account 소유 여부 (0/1)  
• Online : 온라인 뱅킹 사용 여부 (0/1)  
• CreditCard : Common Bank의 신용카드 소유 여부 (0/1)  

1. 먼저 ID와 ZIP.code는 feature에서 제외한다. 그리고 z-score normalization을 활용하여 모든 feature들의 scale을 일치시킨다.  
첫 4,000명의 데이터를 training set으로, 나머지 1,000명의 데이터를 test set으로 사용하고, training set과 test set에서의 target variable의 분포를 비교해 보자.

2. 5-NN을 적용하고, 결과를 분석해보자.

3. Training set 중에서 마지막 800명의 데이터를 validation set으로 사용하여, 다양한 k 값에 대해 k-NN을 적용해 보고 예측 성능을 비교해 보자. k가 어떤 값을 가질때 모델의 성능이 가장 우수한가?

4. Training set에 대해 5-fold cross validation을 5회 반복하여 best k 값을 찾아보자. Best k 값으로만들어지는 최종 model에 test set을 적용하여 model의 성능을 report하자.

5. 3번과 4번에서 활용한 training 방식의 장단점을 비교해보자.
