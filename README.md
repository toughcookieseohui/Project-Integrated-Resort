# Project-Integrated-Resort

## 실무 SQL 사용 4개월 차... 그러나 ##

복합 리조트 회사에서 "멤버십"팀에 입사한 나..
데이터 담당으로 들어와서 본격적으로 실무 SQL을 사용하기 시작하는데...
그런데 포트폴리오는 대체 어떻게 작성해야 하는 걸까?
실무는 늘었는데 이를 어필하기가 쉽지 않다. 
보안때문에 내용은 최대한 숨기더라도 내가 한 건 어필을 해야하고..
다른 포트폴리오 참고하고 싶은데 실무에서 한 일을 세세히 적은 내용은 찾기 어렵다. 
그래서 일단 작성해보는 나의 포트폴리오

먼저, 복합리조트 회사란 무엇인가?
호텔, 카지노, 쇼핑몰, 컨벤션, 전시 시설, 공연장, 레스토랑, 박물관, 테마파크 등 여러 분야의 시설을 융합해 
비즈니스, 가족 관광, 레저, 엔터테인먼트 등 다양한 목적의 관광을 충족시킬 수 있는 리조트 시설을 말한다. (출처 : 파라다이스 블로그)

저 많은 유닛들에서 발생하는 데이터를 모두 다루는 것을 아니고..
나는 저 유닛들에서 멤버십 프로그램과 관련된 데이터만 다뤘다. 

## ERD
관계형 데이터베이스를 다루는데 ERD랑 DB명세서가 없어 이를 구축하는 일부터 시작했다.
회사 정보이기 때문에 블러 처리하였는데 멤버십 데이터베이스이기 때문에 회원 테이블을 중심으로
스타 스키마와 같은 형태를 띠고 있는 관계형 데이터베이스가 구축되어 있었다. 
ERD를 간단히 만들고 DB에 대한 이해도를 갖추고 나서 본격적인 분석 작업을 시작했다. 
![image](https://github.com/user-attachments/assets/dde050ca-d571-480b-be48-dfc042bd979c)


## 멤버십 Retention 측정 프로젝트 ##
- **분석 목적** : 멤버십 회원들의 호텔 재방문율을 계산하여 멤버십 프로그램의 매출 기여도를 확인하기 위한 목적
- **활용 데이터** : 기업 자체 데이터 (숙박 데이터, 회원 데이터)
- **분석 도구** : SQL (LEFT JOIN, INNER JOIN, GROUP BY, DIFF, MIN, MAX) 
- **분석 방법**
  1.
  2. 

## 유료 멤버십 콜 세일즈 프로젝트 ##
- **분석 목적** : 유료 멤버십 상품 판매를 위해 해당 상품을 구매할 만한 대상자를 선정하여 콜 세일즈를 하기 위한 목적
- **활용 데이터** : 기업 자체 데이터 (회원 데이터, 포인트 데이터)
- **분석 도구** : SQL (INNER JOIN, GROUP BY, ORDER BY)
- **분석 방법** : 

## 포인트 만료 회원에게 포인트 만료 알림 프로젝트 ##
- **분석 목적** : 포인트 만료까지 3개월이 남은 회원에게 포인트 만료 알림 문자를 보내기 위한 목적
- **활용 데이터** : 기업 자체 데이터 (회원 데이터, 포인트 데이터, 수신차단 데이터)
- **분석 도구** : SQL (LEFT JOIN)
- **분석 방법** : 

## 웰컴 바우처 리뉴얼 프로젝트 ##
- **분석 목적** : 회원가입 시 증정하는 웰컴 바우처의 사용 현황을 파악하고 새롭게 리뉴얼하기 위한 목적
- **활용 데이터** : 기업 자체 데이터 (회원 데이터, 바우처 데이터, 포인트 데이터)
- **분석 도구** : SQL (LEFT JOIN, INNER JOIN, GROUP BY)
- **분석 방법** : 
