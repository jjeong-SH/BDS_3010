# BigData Computing course project (BDS3010-01)
### 주제: COVID 대유행 기간 동안 미디어의 백신 언급도에 따른 관련 주가 변화 분석

조원: 김연요, 정상희, 정재원, 안유균

*for explanation, please check out our project ppt file!*
![Big_data_computing_team1_2](https://user-images.githubusercontent.com/80621384/141470050-9aee2ed5-634c-48b3-b520-b68b78a63c86.jpg)


## Package requirements
adjustText
bs4
requests
konlpy
wordcloud
IPython
Sklearn
(버전은 상관없음)



## Executor's Environment
Mac OS jupyter notebook



## Executing Guide
Q1 -> News_crawler -> Q2_1  -> relation -> Q2_2 -> Q3 -> Q4



## Data Location and Specification
1)  './data': 공공기관 및 금융기관에서 다운받은 데이터

- 'owid-covid-data.csv' : 코로나 발생 현황 데이터
- 그 외 csv 파일: 백신 관련 주가 데이터

2) './crawler/files': 네이버 뉴스 크롤링 데이터

- '1st.csv': 코로나 1차 대유행 시기 네이버 기사 데이터
- '2nd.csv':  코로나 2차 대유행 시기 네이버 기사 데이터
- '3rd.csv':  코로나 3차 대유행 시기 네이버 기사 데이터
- 'url_link.txt': 네이버 기사 링크
- 'temp.csv': 크롤링 테스트용 temp 데이터

3) './keyword': 키워드 추출 결과 데이터

- './keyword/1st_period_rep.csv' : 1차 대유행 시기에 추출된 키워드
- './keyword/2nd_period_rep.csv' : 2차 대유행 시기에 추출된 키워드
- './keyword/3rd_period_rep.csv' : 3차 대유행 시기에 추출된 키워드
- 'vaccine_data.csv' : 백신 언급량 데이터



