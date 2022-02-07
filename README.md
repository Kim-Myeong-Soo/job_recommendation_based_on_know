# 대회 명 : KNOW기반 직업 추천 알고리즘 경진대회

기간 : 2021/12/06~2022/01/28
팀명 : thingsu
결과 : 

![](https://github.com/Kim-Myeong-Soo/job_recommendation_based_on_know/blob/6ccd02c4ed5a9b67c6b58eb3ac00668f4fc60d31/score.png)

## Solution
- 자연어 답변 문항에 대해서 bag of word 방식으로 feature 생성
- RandomForest와 Neural Network 모델 활용
- Hard Voting 방식으로 Ensemble

## Directory
'''
├── README.md 
├── asset
│   ├── List_csv2017.csv
│   ├── List_csv2018.csv
│   ├── List_csv2019.csv
│   ├── List_csv2020.csv
│   └── sample_submission.csv
├── code_thingsu.ipynb
├── test
│   ├── KNOW_2017_test.csv
│   ├── KNOW_2018_test.csv
│   ├── KNOW_2019_test.csv
│   └── KNOW_2020_test.csv
└── train
    ├── KNOW_2017.csv
    ├── KNOW_2018.csv
    ├── KNOW_2019.csv
    └── KNOW_2020.csv
'''
