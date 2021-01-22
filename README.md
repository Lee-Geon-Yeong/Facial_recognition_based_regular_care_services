# AI 안면인식 기반 단골관리 서비스 시스템

### 주요 기능
1. 안드로이드 앱으로 고객정보와 사진을 DB에 저장(IoT)
2. AI 안면인식을 통해 고객별 사진 객체 추출(AI)
3. 고객별 ID를 기반으로 과거 구매이력 조회 및 추천알고리즘을 통한 맞춤형 메뉴 추천(Big Data)
4. 추천메뉴 인터페이스로 전달 후 고객 맞춤형 메뉴판 제공(Cloud)

### 기획 의도 및 차별점
![image](https://user-images.githubusercontent.com/59759468/105444252-d572c480-5cb0-11eb-8e14-6d0649968100.png)
- 고객관리 측면에서 점점 양질의 서비스를 제공하는 것이 경쟁력이 있는 시대가 되었다.<br>
  언택트 + 개인화 + 맞춤 단골 서비스를 통해 고객의 니즈와 만족도를 극대화하는 전략으로 차별점을 두었다.

### Tools and Skills
![image](https://user-images.githubusercontent.com/59759468/105444011-64331180-5cb0-11eb-8329-e5e517c233d3.png)
- 빅데이터 - 웹 크롤링 및 행렬기반 메뉴 추천 서비스<br>
  IoT - Android(Kotlin)를 통한 앱 구현, django와 서버통신<br>
  AI - 데이터 수집 및 안면 이미지 전처리(OpenCV+Dlib)<br>
  클라우드 - AWS 연동 및 Web(React) 개발 

### IoT
![image](https://user-images.githubusercontent.com/59759468/105444877-07d0f180-5cb2-11eb-9109-4dd593751faa.png) 
![image](https://user-images.githubusercontent.com/59759468/105444912-1ae3c180-5cb2-11eb-9440-05bba26c8ad5.png)
- Android(Kotlin)를 통한 앱 개발, 회원가입과 사진촬영 기능 구현 후 Restful을 이용하여 데이터를 django 서버로 연동


### 느낀 점
- 각 분야의 기술을 융합하여 진행하는 프로젝트였으므로 전체의 흐름과 이 기술들을 어떻게 연동할 것인지에 대한 방법에 대해 많은 고민을 하였다. 각 분야에서 많이 쓰이는 개발 방식이라던지 서로에게 공유하고 알려주면서 내가 접해보지 않은 다른 분야에 대해 더 넓은 시야와 경험을 쌓을 수 있었던 좋은 경험이었다.
