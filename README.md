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

### IoT
![image](https://user-images.githubusercontent.com/59759468/105444877-07d0f180-5cb2-11eb-9109-4dd593751faa.png) 
![image](https://user-images.githubusercontent.com/59759468/105444912-1ae3c180-5cb2-11eb-9440-05bba26c8ad5.png)
- Android(Kotlin)를 통한 앱 개발, 회원가입과 사진촬영 기능 구현 후 Restful을 이용하여 데이터를 django 서버와 연동

### AI
![image](https://user-images.githubusercontent.com/59759468/105445304-fdfbbe00-5cb2-11eb-990c-d8ac0946d76b.png)
![image](https://user-images.githubusercontent.com/59759468/105445393-2c799900-5cb3-11eb-9099-0c4bc696210d.png)
![image](https://user-images.githubusercontent.com/59759468/105445402-31d6e380-5cb3-11eb-874c-5fc5eeb0a3bd.png)
![image](https://user-images.githubusercontent.com/59759468/105445426-41562c80-5cb3-11eb-8b35-8b9cb8e48cc3.png)
-   AI - 데이터 수집 및 안면 이미지 전처리(OpenCV+Dlib)

### Big Data
![image](https://user-images.githubusercontent.com/59759468/105445237-c8ef6b80-5cb2-11eb-9562-82dbb24b139b.png)
![image](https://user-images.githubusercontent.com/59759468/105445255-da387800-5cb2-11eb-8fde-d4cc490cd948.png)
- 웹 크롤링 및 행렬기반 메뉴 추천 서비스

### Cloud
![image](https://user-images.githubusercontent.com/59759468/105445463-5a5edd80-5cb3-11eb-9175-3e78d4f7c427.png)
![image](https://user-images.githubusercontent.com/59759468/105445475-6480dc00-5cb3-11eb-9b99-6f5d06359c21.png)
![image](https://user-images.githubusercontent.com/59759468/105445490-6fd40780-5cb3-11eb-9cb8-c78032760044.png)
- 클라우드 - AWS 연동 및 Web(React) 개발

### 느낀 점
- 각 분야의 기술을 융합하여 진행하는 프로젝트였으므로 전체의 흐름과 이 기술들을 어떻게 연동할 것인지에 대한 방법에 대해 많은 고민을 하였다. 각 분야에서 많이 쓰이는 개발 방식이라던지 서로에게 공유하고 알려주면서 내가 접해보지 않은 다른 분야에 대해 더 넓은 시야와 경험을 쌓을 수 있었던 좋은 경험이었다.
