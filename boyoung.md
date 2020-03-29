Search for issue
================    
### 버스 분석 및 신규 노선 제안    
* 배경
  - 출퇴근 시간에는 일부 구간에만 승객 몰림
  - 현재 혼잡 구간에 짧은 시간만 운행하는 버스 있음 (다람쥐 버스)    
  
* 목적
  - 다람쥐 버스의 효과가 크게 나타나고 있으므로 출퇴근 시간 이동량을 분석하여 신규 노선 제안    
  
* 데이터
  - [사업체 및 종사자 밀도 통계](https://data.seoul.go.kr/dataList/96/S/2/datasetView.do)
  ![img3](https://user-images.githubusercontent.com/33210702/77854642-6100fd80-7226-11ea-8e45-78e74a18d535.PNG)
    + 사업체 수, 종사자 수, 종사자밀도비 등    
    
  - [대중교통 이용통계](https://bigdata.seoul.go.kr/data/selectSampleData.do?r_id=P213&sample_data_seq=14&sch_type=&sch_text=%EA%B5%90%ED%86%B5&currentPage=1)    
  
  ![img4](https://user-images.githubusercontent.com/33210702/77854664-8857ca80-7226-11ea-9684-82499fbaaee7.PNG)
  + 날짜, 노선, 역, 출퇴근 시간 최다 승하차 인원 등     
  
  ![img5](https://user-images.githubusercontent.com/33210702/77854678-96a5e680-7226-11ea-9739-a917d05f8333.PNG)
  + 날짜, 정류장, 출퇴근 시간 최다 승하차 인원 등     
  
* 분석 방향
  - 종사자 수, 종사자 밀도, 사업체 수 등을 파악
  - 많은 인원 몰리는 곳을 신규 노선 필요한 지역으로 도출
  - 다람쥐 버스의 패턴과 비슷한 노선 새롭게 도출
