Hyejin's Idea for this project
===============================

#### GOAL : 서울시 대중교통 인구밀도 및 통행 패턴
- 시간별(특히 출퇴근 시간) 대중교통 인구밀도 분석
- 대중교통 통행 패턴 및 토지이용

    출퇴근별로 승하차 인구수를 파악한 뒤 그 자치구에는 어떠한 형식으로 토지가 이용되고 있는 지 예측 가능
    
#### SOURCE OF DATA
- [지하철 승하차 API](https://data.seoul.go.kr/dataList/OA-12252/S/1/datasetView.do)

    ![지하철 승하차 API](https://user-images.githubusercontent.com/31836035/77851143-5a688b00-7212-11ea-93aa-ba3004021ee1.PNG)
    
        대중교통 종류코드 , 정류장명 , 시간별 승 · 하차인수 , 연월 , 위치 좌표와 같은 필요한 변수 가지고 오기

- [버스 승하차 API](https://data.seoul.go.kr/dataList/OA-12913/S/1/datasetView.do)

    ![버스 승하차 API](https://user-images.githubusercontent.com/31836035/77851098-f6de5d80-7211-11ea-8646-a6608fa26739.PNG)
    
        대중교통 종류코드 , 정류장명 , 시간별 승 · 하차인수 , 연월 , 위치 좌표와 같은 필요한 변수 가지고 오기

#### Example of Visualization
![Example of Visualization](https://user-images.githubusercontent.com/31836035/77850900-87b43980-7210-11ea-9f8d-ad90b66f7358.jpg)

#### The Ohters
- [토지 관련 자료 필요할 시 참고](http://data.seoul.go.kr/dataService/boardList.do?tr_code=short#submenu125)
