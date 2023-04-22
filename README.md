# STUDY-Sales_Modeling

> [ML 강의](https://github.com/Chaewon-Leee/TIL/tree/main/ML) 수강 이후, 모델링 과정을 진행해보고자 함
> [전처리 과정을 거친 데이터](https://github.com/Chaewon-Leee/STUDY-Sales_Feature_Engineering) 활용

### 가게 매출액 예측 프로젝트

- 애콰도르의 위치한 가게 품목별 매출액 예측

- **Data info**

  - [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/submissions)

  ```markdown

  ```

# Kaggle Seminar - \***\*Store Sales\*\***

![스크린샷 2023-01-19 오후 5.56.59.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/163db73f-678f-4164-96b2-2c8aaed2b603/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-01-19_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.56.59.png)

[KaggleSeminar.ipynb](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/02b7410f-e76e-46e7-9f94-36c355447d02/KaggleSeminar.ipynb)

### 가게 매출액 예측 프로젝트

- Feature Engineering 이후, modeling 진행

- **Data info**

[Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/submissions)

```markdown
- all_of_df.csv : 데이터 전처리 이후, 어떠한 Feature Selection을 거치지 않은 데이터
- RFE_df.csv : 데이터 전처리 이후, FRE를 통해 Feature Selection을 거친 데이터
```

- **절차**

1.  모델 탐색
    1. 회귀 문제를 풀기 위한 다양한 모델 탐색
    2. 모델들의 default 성능 비교
    3. 가장 성능이 좋은 `모델 선정`
2.  하이퍼파라미터 튜닝
    1. 선정된 모델 파라미터 튜닝 → Local, Colab, Backend AI 시도
    2. ‘feature selection`과 더불어 성능 향상 목표

- **After Seminar**
  | 회고 | 내용 |
  | :----------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | 하이퍼파라미터 | - **로컬 컴퓨터에서 처리하지 못하는 경우, 시도할 수 있는 방법**에 대해 고안해보기 <br>- 중간중간 컴퓨터가 다운 됐을시, 대처가 어려움 |
  | feature selection | - 선정한 모델에 대해 feature selection을 재진행하였으나, 오히려 성능이 떨어짐 <br>- feature selection에 대해 좀 더 공부할 필요가 있음 |
  | 모델 성능 비교 | - 모델 성능 비교시, 비교만 하고 끝내는 것이 아닌 **평가지표에 따른 해석이 필요** |
  | 전체적인 완성도 | - 전체적으로 완성도가 떨어져 아쉬움… 이후, 재도전하면 좋을 듯함 <br>- **다음엔 꼭 완성도 높이는데에 목표!** |

- **Additional Project**
  - [Check](https://github.com/Chaewon-Leee/TIL/tree/main/ML)
