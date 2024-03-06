# [🌱Beginner Friendly] Obesity Risk Prediction
----------------------------------
## Overview
This notebook is designed for beginners to practice Hyperparameter Tuning with Optuna and Machine Learning with LightGBM.
The dataset used here requires minimal preprocessing, which will aid in quickly grasping the machine learning process.

In particular, detailed explanations have been provided for each step to make it easy for beginners to understand.
Follow along with the tutorial and try to comprehend each step!📈🎯


## Content
  - **Outline** 
  - **Load Data** 
  - **Data Exploration** 
  - **Statistical Analysis** 
    - **Independent Samples t-test**
    - **Analysis of Variance (ANOVA)**
    - **Independence Test (Chi-square Test)**
  - **Preprocessing**
  - **Modeling**
    - **Hyperparameter Tuning**
    - **LGBMClassifier**
  - **Project Evaluation**
  - **Lesson Learned**


## 본 프로젝트에서 사용한 주요 개발환경 요약
  + Programming Languages : Python(ver. 3.12.1)


## 주요 라이브러리
  + See [requirements.txt](requirements.txt)


## Data Description
| Column | Full Form | Description| 
|---|---|---|
| 'id'| id | Unique for each person(row)|
|'Gender'| Gender| person's Gender|
| 'Age' | Age| Dtype is float. Age is between 14 years to 61 years |
|'Height'| Height | Height is in meter it's between 1.45m to 1.98m|
| 'Weight' | Weight| Weight is between 39 to 165. I think it's in KG.|
|'family_history_with_overweight'| family history <br> with overweight| yes or no question|
| 'FAVC'| Frequent consumption <br> of high calorie food| it's yes or no question. i think question they asked is <br>do you consume high calorie food|
|'FCVC'|  Frequency of <br>consumption of vegetables| Similar to FAVC. this is also `yes or no` question|
|'NCP'| Number of main meals| dtype is float, NCP is between 1 & 4. I think it should be 1,2,3,4 <br>but our data is synthetic so it's taking float values|
|'CAEC'| Consumption of <br>food between meals| takes 4 values `Sometimes`, `Frequently`, `no`, & `Always` <br>|
| 'SMOKE'| Smoke | yes or no question. i think the question is "Do you smoke?" |
|'CH2O'| Consumption of <br>water daily| CH2O takes values between 1 & 3. again it's given as <br>float may be because of synthetic data. it's values should be 1,2 or 3|
|'SCC'|  Calories consumption <br>monitoring| yes or no question|
|'FAF'| Physical activity <br>frequency| FAF is between 0 to 3, 0 means no physical activity<br> and 3 means high workout. and again, in our data it's given as float|
|'TUE'| Time using <br>technology devices| TUE is between 0 to 2. I think question will be "How long you have <br>been using technology devices to track your health." in our data it's given as float |
|'CALC'| Consumption of alcohol | Takes 4 values: `Sometimes`, `no`, `Frequently`, & `Always`|
| 'MTRANS' | Transportation used| MTRANS takes 5 values `Public_Transportation`, `Automobile`, <br>`Walking`, `Motorbike`, & `Bike`|
|'NObeyesdad'| TARGET | This is our target, takes 7 values, and in this comp. we have to give <br>the class name (Not the Probability, which is the case in most comp.)


## 테스트 준비 및 방법
- 원격 저장소의 주소를 복사한 다음 로컬 환경에 복제합니다.

```bash
git clone "https://github.com/yellayujin/RealEstateTrackerSeoul.git"  
```

- 폴더 최상위 경로에서 가상환경을 설치합니다.

```bash
pip install virtualenv #기존에 설치한 가상환경이 있다면 생략 가능
virtualenv venv
```

- 가상환경에 접속합니다.
```bash
source venv/Scripts/activate
```

- 라이브러리를 설치합니다.
```bash
pip install -r requirements.txt
```

- jupyter 환경에서 .ipynb파일을 실행합니다.
```bash
jupyter lab
```

## 코드 에러 문의 
- e-mail: skrtkd0416@naver.com

## 발표자료 PDF 
- 발표자료 PDF는 아래와 같습니다.
  + [00발표자료_2024](portfolio.pdf)
 
