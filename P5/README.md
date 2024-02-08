# Project 5

### subject : 집값 예측 [DL]

<img src='https://github.com/Choe-minsung/project-study/blob/11dd361cbdefa71277c72591f6ce934e35f38ee6/P4/src/1st_price_house.png' width='700'/>

- duration : 2023.11.06 ~ 2023.11.13
- stack : Python (Jupyter Notebook)
- member : **PM** 1 / 기술 3
- my role : **PM**

#### pipeline
1. 데이터탐색, 전처리
2. 추가 ML modeling (*project 3 retrospective*)  
   2-1. **CatBoost** vs XGB, LGMB (and other boost models)  
3. DL modeling   
   3-1. **Sequential** (hl 수 : 2, epochs=30, batch_size=32)  
   3-2. **Sequential** (hl 수 : 3, epochs=30, batch_size=32)  
   3-3. Overfitting 해소  
4. 집값예측  
5. 추가 DL modeling  
   5-1. 단위기간 설정 (sequence_length = 10)  
   5-2. **LSTM**  


<img src='https://github.com/Choe-minsung/project-study/blob/3bfaedf59db71a6db35e82558886efe8af1f5273/P5/src/feature_map.png' width='700'/>


<img src='https://github.com/Choe-minsung/project-study/blob/12f5aec14b1ae39b00ea4f1270eab140566ccb07/P5/src/pred_airfare.png' width='700'/>
