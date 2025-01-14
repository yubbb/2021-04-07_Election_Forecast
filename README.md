# AI 빅데이터 교육 프로젝트_team4
2021년 4월 7일 보궐선거 결과 예측

###  기획의도
서울·부산 시장의 사망 및 사퇴 후 1년 내에 치뤄지는 보궐선거는 긴 기간을 두고 진행하는 공천 절차를 통해 대중의<br>
지지도를 쌓아올리는 과정과 달리, 여론의 방향성과 대중 인식이 선거 결과에 더 큰 영향을 줄 것이라 생각하였습니다.<br> 
또한, 이번 보궐선거가 내년 대선의 전초전이라고 평가받는만큼 대중의 인식을 분석하는 것이 중요할 것으로 판단하였습니다.


### 개발과정
1. 데이터 수집
2. 데이터 전처리
3. 모델 구축
4. 결과 분석

### 사용한 데이터
- 조선일보
- 중앙일보
- 유튜브
- 경향신문
- 동아일보
- 한겨레
- JTBC

### 모델 구성
- 모델 1 : 텍스트 감성분석
- 모델 2 : 후보자 예측

### 결과 분석
각 후보별 긍정률(positive/(positive+negative))을 계산하여 더 높은 긍정률을 가진 후보가 당선될 것으로 판단하였습니다.<br>
결과적으로 긍정률 : 박영선 후보 < 오세훈 후보, 김영춘 후보 < 박형준 후보로 나타남으로써 잘 예측한 것으로 결론내렸습니다.
