## 프로젝트 소개
Taxi v-3 환경에서 TD Difference Learning의 학습방법인 SARSA와 Q-Learning의 학습 성능 차이를 비교 분석해보았습니다


## 사용 라이브러리
+ numpy
+ gym
+ matplotlib.pyplot
+ tqdm


## 사용방법
파일의 윗부분은 SASRSA에 대한 코드를, 아랫부분에는 Q-Learning에 대한 코드를 작성했습니다.
따로 붙여서 구현해야 합니다.


## 결과
SARSA : 3600번째 에피소드부터 보상값 양수 전환. Average Return은 7.9169

Q-Learning : 2800번째 에피소드부터 보상값 양수 전환. Average Return은 7.9632
