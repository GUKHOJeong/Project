# Project

### 기후데이터를 이용한 전력량 예측 모델 


## Team Main Image 
<img src="https://github.com/GUKHOJeong/EST_Project/blob/main/First_Project/energy_consumption_prediction/image/cat_lightning.png?raw=true" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="cat_lightning"></img>



## Project Structure 
```
├──  Data 
    ├── Cleaned
        ├──  preprocessed Weather
        ├──  preprocessed electricity
        ├──  preprocessed Gas 
        ├──  Result Data
    ├── Original
        ├──  Origin Weather
        ├──  Origin electricity
        ├──  Origin Gas
├──  doc : 프로젝트 기획서/ 최종 결과서 
├──  test
    ├── test : NN test
    ├── Second_test : 모델링 코드/시각화 코드 test(작성자가 주로 사용)
├── data_extraction:데이터 추출 코드
├── energy_consumption_prediction : 메인 코드 
```


## Data 
 Weather(기후데이터), electricity(전력데이터), Gas(가스데이터)



## Model

- Linear Regression
- ElasticNet
- Support Vector Regression (SVR)
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- XGBoost Regressor
- Stacking Regressor (Base = High metric by combination)
- NN
- Time Series Analysis


## Metric

- MAE(Mean Abs Error)
- RMSE(Root Mean Square Error)
- R² 
- Adjusted R² : why? 특성이 많아지면 R² 높아지므로 이를 방지하기위해서 사용 
- Best Hyper Param : GridSearch를 통한 베스트 하이퍼 파라미터


## Project Team Member 
- [Jeong Gukho](https://github.com/GUKHOJeong/)
- [Jeong Woogun]()
- [Kim Hyungeun](https://github.com/hyungeunkk)
- [Kim Juneon]()
- [Kimm Soo Min](https://github.com/somnio-kimm)
