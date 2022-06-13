### 이미지 정보 수집을 통한 Labelme formal출력 API Service (2022.05.09 - 2022.06.03) - 기업협업(누비랩)

- 이미지를 입력받아  Labelme formal으로 출력하기 위한 API Service 🔗[프로젝트 URL](https://github.com/xodn234/Image_input-labelme_format/tree/main)
    - 담당업무
        - 구글렌즈를 크롤링하여  foodname, labelbox 정보를 가져오는 코드 작성
        - image hash를 통하여 동일한 이미지를 판단하여 삭제하는 코드 작성
        - 크롤링한 labelbox를 가지고 이미지에 box가 포함된 이미지를 출력하는 코드 작성
- skill : Opencv, Crawling, API활용

### 식품 알레르기 대체 식품 추천 (2022.04.20 - 2022.05.02) - 개인

- 알레르기 반응이 없는 유사한 식품을 추천해주는 모델 구현 🔗[프로젝트 URL](https://github.com/xodn234/Food_allergy_PJ)
    - 추천을 위한 코사인유사도 방식 활용
    - Heroku를 통한 웹 배포
- skill : Flask, NLP

### ****GAN을 이용한 자동차 이미지 생성 (****2022.03.17 - 2022.03.22****) - 개인****

- 자동차 이미지 데이터를 활용하여 조작된 가짜 자동차 이미지 생성 🔗[프로젝트 URL](https://github.com/xodn234/GAN_car_image_creation_PJ)
    - 이미지 생성을 위한 DCGAN사용
    - 결과물 비교를 위해 애니메이션 데이터를 추가 활용
    - epoch 0~1000 학습 과정 확인
- skill : TensorFlow(keras), OpenCV

### ****송전선로 고장 예측 (****2022.02.11 - 2022.02.16****) - 개인****

- 선로 고장 예측 웹 구현 🔗[프로젝트 URL](https://github.com/xodn234/Electrical_Fault_detection_PJ)
    - 머신러닝 모델을 적용한 Flask를 이용한 웹구현
    - 카카오map을 이용하여 위치 표시
- skill : Flask, SQL

### ****기계 불량 예측  유지보수 분류 (****2022.01.07 - 2022.01.12****) - 개인****

- 불량 예측을 위한 머신러닝 모델링 및 해석 🔗[프로젝트 URL](https://github.com/xodn234/Machine_Predictive_Maintenance_PJ)
    - 실제 불량을 줄이고 점검을 위한 재현율(Recall) 평가지표 사용
    - 과적합의 문제를 해결하기 위해 bagging(RandomForest) 모델사용
    - pdpbox를 이용한 모델 해석
- skill : scikit-learn

### ****분석을 통한 다음 분기 제작 게임 도출 (****2021.12.08 - 2021.12.13****) - 개인****

- 데이터 분석 및 시각화를 통한 인사이트 도출 🔗[프로젝트 URL](https://github.com/xodn234/Video_Game_Sales_PJ)
    - 이상치를 출고량이 높다는 기준으로 판단
    - 최신 트랜드를 반영하기위해 최근 증감추세 반영
- skill : pandas, plotly
