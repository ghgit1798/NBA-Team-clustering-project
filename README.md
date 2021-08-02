# NBA 강/약팀 clustering project
- 목표: NBA 정규 시즌 데이터로부터 강/약팀 군집 분류 후 특징 파악
- 데이터: [nba 2017-2018 regular season data](https://www.kaggle.com/michaelmcfarlane/20172018-nba-regular-season-game-data)
- 사용 언어: R, Python(Pandas, Numpy, Plotly, Scklearn)
- 맡은 역할: data preprocessing, clustering, visualization

## 🔸 분석 배경
- 야구를 비롯한 스포츠분야에서 데이터와 AI를 바탕으로 승리를 결정짓는 요인을 파악하려는 시도가 증가하고 있다.
- 농구에서도 승리에 기여하는 특정한 요소를 발견할 수 있으리라는 기대감에 본 프로젝트를 진행하였다.

## 🔸 분석 소개
### 1. 분석 목적
- 수많은 공격과 방어 데이터 중 승패에 가장 크게 영향을 미치는 요인 파악
- 팀별 경기 데이터 비교를 통해 보안점 제시
### 2. 분석 방향
1. 주성분 분석(PCA)을 통한 데이터 차원 축소 및 주 요인 탐구
2. 승리 팀과 패배 팀 각각의 군집 분석을 통한 승패 요인 분석 및 우승 전략 제시

## 🔸 데이터 개요
![image](https://user-images.githubusercontent.com/44918665/127817228-4c9ec2b8-1f6e-485b-9373-6072b8662f90.png)
![image](https://user-images.githubusercontent.com/44918665/127817247-23d8efc8-55ca-45aa-80b9-7ba984b8404c.png)



## 🔸 분석 과정
![image](https://user-images.githubusercontent.com/44918665/127816153-cd9f8c85-5a7e-466f-b1a7-bf99ed7fd280.png)

### 1. 데이터 전처리
![image](https://user-images.githubusercontent.com/44918665/127816645-24268289-2ee8-4ed6-9ffa-5706de3d3653.png)

### 2. 주성분 분석 결과
![image](https://user-images.githubusercontent.com/44918665/127816495-b71ec246-86fb-4cbe-a02c-a6dd84bd4e24.png)
![image](https://user-images.githubusercontent.com/44918665/127817400-8a05e7d3-95df-4ae4-ab93-cd4f5902b172.png)


### 3. Scree plot을 근거로 주성분 개수 결정
![image](https://user-images.githubusercontent.com/44918665/127816592-89dca866-f5a0-4e70-bae8-2aa23ee77a59.png)

### 4. 클러스터링 분석 결과
![image](https://user-images.githubusercontent.com/44918665/127816841-51a40da6-3088-4598-b2da-cd236bf40220.png)
![image](https://user-images.githubusercontent.com/44918665/127817019-35c3abb8-6b56-42cc-be7b-8d6fe6fca81c.png)

## 🔸 분석 결과
### 1. 강팀1 - HOU 휴스턴 로키츠
![image](https://user-images.githubusercontent.com/44918665/127817556-7c8f239a-faaf-477e-a8cf-92fb33bde0fc.png)
### 2. 강팀2 - GSW 골든스테이트 워리어스
![image](https://user-images.githubusercontent.com/44918665/127817649-c51e95e2-1a0e-4c2a-9a77-6acb49ed0765.png)
### 3. 강팀3 - POR 포틀랜드 트레일블레이저스
![image](https://user-images.githubusercontent.com/44918665/127817697-6a109a98-ac96-4979-934f-bacf30628fc7.png)
### 4. 약팀1 - 2017-2018시즌 LAL 로스앤젤러스 레이커스
![image](https://user-images.githubusercontent.com/44918665/127819552-810b3a29-aaf2-43d7-b456-4846a2965cf3.png)

### 약팀 전략 - 2018-2019시즌 LAL 로스앤젤러스 레이커스
![image](https://user-images.githubusercontent.com/44918665/127817876-c9ab99bb-b3be-4e2d-9350-eee80c9e4914.png)

### 5. 약팀2 - 2017-2018시즌 DAL 댈러스 매버릭스
![image](https://user-images.githubusercontent.com/44918665/127818396-c0d45420-9374-4e29-a89f-8248beb81ce5.png)

### 약팀 전략 - 2018-2019시즌 DAL 댈러스 매버릭스
![image](https://user-images.githubusercontent.com/44918665/127818613-f884e130-893d-499a-9028-69ea1ff03804.png)

## 🔸 분석 결과 적용 및 한계점
### 1. 분석 결과 적용
![image](https://user-images.githubusercontent.com/44918665/127818921-6eb3106d-962e-42f6-99ef-59606d57dc42.png)

### 2. 한계점
![image](https://user-images.githubusercontent.com/44918665/127819130-aae2ee61-d907-4b71-9bdc-1a4f94d25689.png)

## 🔸 참고 사이트
![image](https://user-images.githubusercontent.com/44918665/127819241-afbfcd91-3705-4a19-8830-44eca59d50b7.png)

## 🔸 Appendix
![image](https://user-images.githubusercontent.com/44918665/127819303-1e1f1314-8d8e-44de-8b10-7c2477812a0b.png)


