# 딥러닝 프로젝트
-------------------------------------------------------------
## 🙌<u>목적</u>
- 외국인들을 위한 한식음식 분류 및 감정에 따른 한식 추천기

## ❓데이터 수집
- Aihub의 한국이미지(음식) 데이터
- Roboflow에서 제공하는 한식, 얼굴 감정 데이터
- Aihub의 단발성 대화 데이터

## 😀참여인원
- [TEAM: K-FOOD]
- 지승엽 : CNN으로 음식 이미지 분류, YOLOv8을 이용해 Live로 음식 분류, Gardio로 웹페이지상에 설계한 기능들 demo버전 구현
- 김태혁 : YOLOv8을 이용해 Live로 감정 분석, Bert를 이용해 
- 이용희 : 주제선정, 자료조사, YOLOv8을 이용해 Live로 음식 분류, ppt제작

## 🤷<u>기능</u>
- 분류기능 : densnet201 모델을 활용한 음식분류, Yolov8을 이용한 실시간 음식 분류
- 감정분석 기능: 텍스트 자연어처리모델 Bert사용, Yolov8을 이용한 얼굴감정 분석. 
- 위 두가지 기능을 활용한 음식추천.

## 🤴<u>결과화면</u>
|기능1(실시간 음식 분류)|기능1 결과|
|:-:|:-:|
|<img src="https://user-images.githubusercontent.com/67897827/227238363-a43c1f31-9785-4205-b2b6-5c3decdc72b8.PNG" width="500" height="300"/>|<img src="https://user-images.githubusercontent.com/67897827/227238356-7d491a7c-bd21-454f-a470-b869dc8a8797.PNG" width="1100" height="300"/>| 

|기능2(이미지 업로드->한식이름 분류)|기능3(실시간 얼굴감정 분석)|
|:-:|:-:|
|<img src="https://user-images.githubusercontent.com/67897827/227238384-41a556fa-2964-437d-9026-c1891f1ab928.PNG" width="700" height="300"/>|<img src="https://user-images.githubusercontent.com/67897827/227238316-cd9793d4-9bd9-42f5-896c-7fdb9e59df91.PNG" width="700" height="300"/>| 

|기능3 결과|기능4(텍스트입력 -> 감정분석 후 한식추천)|
|:-:|:-:|
|<img src="https://user-images.githubusercontent.com/67897827/227238412-00c97a34-f846-4763-be66-1923bbfcc059.PNG" width="700" height="300"/>|<img src="https://user-images.githubusercontent.com/67897827/227238349-091dbf7c-9665-4ea2-91f6-4309f7baf2b2.PNG" width="700" height="300"/>|
