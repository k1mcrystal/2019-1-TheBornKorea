# 2019-1-TheBornKorea
> YBIGTA mini-conference project :: 더본코리아 브랜드별 유통전략 분석

> Web Crawling + Map Visualization + Clustering Analysis

#### Members: 김수정, 전유진, 정현우


### 0. Project Information
- 데이터 설명 : 더본코리아 홈페이지의 매장 주소 정보를 데이터로 활용    
- 목표 : 더본코리아 각 브랜드의 매장 분포의 특징을 분석하고 시각화하기

### 1. Web Crawling with Selenium

- Selenium 이용
- 더본코리아 홈페이지(http://www.theborn.co.kr/)에 제공된 매장 주소 정보를 데이터로 활용
- 브랜드, 지역, 매장명, 주소를 크롤링
    
### 2. Google Maps Geocoding API
- Google Maps Geocoding API 이용
- 주소 데이터를 위·경도 데이터로 변환

### 3. Map Visualization with Folium
- Folium 이용  
- 위·경도 데이터를 이용하여 지도에 점 찍기
- 브랜드별 매장 분포의 특성을 파악

### 4. Clustering Analysis
- 매장 분포의 특징을 결정하는 여러 요인들에 대해 가설을 세우고 검증
- 대학교 수, 영화관 수, 지하철 역과의 거리, 매장 좌석 수 등의 요인 고려
- a/b test를 통해, 가장 유의한 요인 3개(매장 좌석 수, 지하철 역과의 거리, 주거지역 여부)를 도출하고 해당 요인을 기준으로 군집화
- 총 4개의 군집에 대하여 각각의 유통전략 파악

### 5. Final Result
- 더본코리아 브랜드 간 매장 분포의 차이를 결정짓는 요인은 '매장 좌석 수', '지하철 역과의 거리', '주거지역 여부'이다.
- 군집1(새마을식당, 원조쌈밥집, 홍콩반점), 군집2(빽다방, 미정국수, 역전우동), 군집3(빽스비어, 한신포차, 돌배기집), 군집4(본가)
