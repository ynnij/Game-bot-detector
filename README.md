# Game-bot-detector


> 게임 속 유저의 데이터를 활용한 사람/봇 탐지 시스템


## 프로젝트 소개


게임 'Aion' 유저의 정보를 기록한 데이터 셋을 학습하여 실제 유저와 봇을 탐지하는 프로젝트입니다. 

프로젝트에 사용된 데이터셋은 [해당 사이트]( https://ocslab.hksecurity.net/Datasets/game-bot-detection)에서 얻으실 수 있습니다. 본 프로젝트에서는 Player actions features와 Player information features 데이터를 사용하였습니다.


* Player actions features : 게임 봇의 고유 특성을 파악하기 위해 행동의 빈도와 비율을 조사한 데이터


* Player information features : 사람과 게임 봇의 행동 특성 차이를 중점으로 분류한 데이터



## 사용한 기계학습 모델 


### Tensorflow 


* Naive Bayes

* Decision Tree, Random forest
