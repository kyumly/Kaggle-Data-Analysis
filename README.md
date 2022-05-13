# Kaggle-Data-Analysis

##타이타닉 예제
###1. 데이터 읽기
    데이터를 읽는거는 가장 기본중에 기본
1. 명령어 pd.read_csv()
2. 데이터는 train. test로 구분할 수 있음
3. 결과화면
![image](image/titanic/read_data.png)
###2. 데이터 개요 파악
    탐색적 데이터 해석이라고 한다. 구체적으로 몇개에 데이터가 있고, 어떤 데이터를 사용해 시각화 할것인지 정하게 된다.
1. shape : 파일에 구조를 알려준다(열과 행의 갯수)
![image](image/titanic/shape.png)

2. dtypes : 데이터의 속성값을 알려준다.
![image](image/titanic/dtypes.png)

3. 양적 변수 vs 질적 변수
   1. 질적 변수 : 수치로 수치 사이틔 간격에 의미가 없는 경우(단지 분류를 짓기 위해 (ex.성별))
      1. 명목 척도 : 분류를 위한 것
      2. 순서 척도 : 순서에 의미가 있는것
   2. 양적 변수 : 간격에 의미가 있는 수치
      1. 간격 척도 : 간격을 측정하는 것
      2. 비례 척도 : 비율에 의미가 있는 것


4. describe : 데이터의 통계량 확인 
![image](image/titanic/describe.png)

5. values_counts() : 카터고리 변수 확인 
<br>데이터프레임["열명"] 형태로 내가 원하는 데이터를 뽑아서 사용할 수 있다.
<br> 이때 데이터의 type은 Series이다
![image](image/titanic/counts.png)

6. isnull(axis=0 or 1)결측값 확인하기
<br>axis 행(0), 열(1) 기준을 잡는 단위<br>
![image](image/titanic/isnull.png)


###3. 데이터 시각화
###4. 데이터 전처리와 특징값 생성
###5. 머신러닝 모델링