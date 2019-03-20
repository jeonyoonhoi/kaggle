# Telco Customer Churn(Focused customer retention programs)



### Overview

##### Context

" 고객을 보유하기 위해 행동을 예측해라. 당신은 모든 관련된 고객 데이터를 분석할 수 있고, 관심 고객 보유 프로그램을 개발할 수 있다.  "[IBM Sample Data Sets]

##### Content

각 행은 고객을 나타내고 각 열은 메타데이터에 맞춰 서술된 고객의 attributes 를 나타낸다. 

**The data set includes information about : **

* Churn : 지난 달에 떠나간 고객 --> Target!! 
* 각 고객들이 가입했던 서비스 - phone, multiple lines, internet, online security, online backup, device protection, tech support, ad steamin TV and movies
* 고객 계정 정보 - 고객기간,  contract, payment method, paperless billing, monthly charges, and total charges.
* Demographic info - gender, age, range, and if they have partner and dependents 

##### Inspiration

이러한 유형의 모델을 탐색하고 대상에 대해 더 자세히 학습하라



### Evaluation

- Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

- The raw data contains 7043 rows (customers) and 21 columns (features).

- The “Churn” column is our target.



### Data

* file : ```WA_Fn-UseC_-Telco-Customer-Churn.csv```
* fileds : 

| Columns          | Description                | Type                                                         |
| ---------------- | -------------------------- | ------------------------------------------------------------ |
| customerID       |                            | A.unique value                                               |
| gender           | 고객 성별                  | A.female, male                                               |
| SeniorCitizen    | 고령자 여부                | #.(1,0)                                                      |
| Partner          | 배우자 여부                | A. (Y,N)                                                     |
| Dependents       | 자녀 여부                  | A.(Y,N)                                                      |
| tenure           | 고객이 회사를 이용한 달 수 | #                                                            |
| PhoneService     | 가입 여부                  | A.(Y,N)                                                      |
| MultipleLines    | 가입 여부                  | A.(Y,N, no phone service)                                    |
| InternetService  | 고객의 ISP                 | A.(DSL, Fiber optic, No)                                     |
| OnlineSecurity   | 가입 여부                  | A. (Y,N, no internet service)                                |
| OnlineBackup     | 가입 여부                  | A. (Y,N, no internet service)                                |
| DeviceProtection | 가입 여부                  | A. (Y,N, no internet service)                                |
| TechSupport      | 가입 여부                  | A. (Y,N, no internet service)                                |
| StreamingTV      | 가입 여부                  | A. (Y,N, no internet service)                                |
| StreamingMovies  | 가입 여부                  | A. (Y,N, no internet service)                                |
| Contract         | 고객의 계약 기간           | (Month-to-month, One year, Two year)                         |
| PaperlessBilling | 페이퍼리스 결제여부        | A. (Y,N)                                                     |
| PaymentMethod    | 결제 방식                  | A. (Eletronic check, Mailed check, Bank transfer(automatic), Credit card(automatic)) |
| MonthlyCharges   | 월별청구비용               | #                                                            |
| TotalCharges     | 총 청구 비용               | #                                                            |
| Churn            | 고객 이탈 여부             | Y, N                                                         |





### 캐글일지

**2018.11.26**

- 대회 참여 시작
- 대회 overview 확인 및 데이터셋 확인 

