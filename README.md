# NLP Project


리뷰에서의 긍정적인 표현과 부정적인 표현을 기준으로 가게를 평가하는 코드

사전에 제작한 감성 사전을 기반으로 리뷰에서 표현을 추출하여 점수를 생성

- 원하는 카테고리별 감성사전을 제작 : 맛/서비스/가격/분위기
- 사전을 기반으로 크롤링한 데이터의 분석을 진행
- 카테고리별 만족도 산출

Flow
![image](https://user-images.githubusercontent.com/33486207/122022843-f5db2100-ce01-11eb-84f7-db42c4b98fe0.png)




크롤러를 통해 카카맵을 통해 장소리뷰를 크롤링(노원 맛집)으로 검색하여 리뷰 취합

참조 사이트 및 Git
1. https://hoho325.tistory.com/268 - 크롤러 (https://github.com/wlgh325/python_crawling)
2. https://github.com/haesoly/estimate_review_of_restaurant - 감정분석
3. http://dilab.kunsan.ac.kr/knu/knu.html - 감성사전
4. 이재광
