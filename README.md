# 이력서
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![contributor](https://img.shields.io/github/contributors/ttpoh/RESUME.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/ttpoh/RESUME.svg)
![status](https://img.shields.io/badge/hired-brightgreen.svg)

## 소개
<img src="https://user-images.githubusercontent.com/99061209/168023385-56ca27eb-faee-4fd8-9958-b8719d618d73.jpg" width="200" height="200"/>

- 이름: 이병우<br/>
- 군필여부: 육군 중위 전역.<br/>
- 취미: 음악 감상, 카페 코딩, 독서, 러닝<br/>
- Email: solution12441@gmail.com<br/>
- GitHub: [github.com/ttpoh](https://github.com/ttpoh)
```
인간이 더 행복하게 살 수 있기를 바라는 신입 개발자입니다. 

```


## 회사경력
- [한국복지방송](http://www.kwbc.kr/) (2020.3 ~ 2021.7), 속기사(자막방송 실시간 속기)

## 학력
- 인제대학교 식품생명과학부 졸업(2008 입학)
- 김해고등학교 이과 졸업(2006 ~ 2008)

## 사용 기술
### Android
- JAVA
- Gson
- Volly(PHP통신, 닷홈)

### Backend
- Apache
- PHP
- MySQL

### Frontend
- html, css

그 외.
- 이슈관리 : Github

### TODO

- 문제 해결을 위해 더 나은 프로세스를 고민합니다. 
- 개발 하면서 겪게 되는 시행착오를 세세하게 기록합니다.(https://velog.io/@talisman)

## 프로젝트 이력
<img src="https://user-images.githubusercontent.com/99061209/168413254-391478f7-b7c0-4c26-a518-5d41c5d6bd10.jpg" width="150" height="150"/> <img src="https://user-images.githubusercontent.com/99061209/168413315-ea13001b-d146-43b2-9373-e6d27d72d356.jpg" width="150" height="150"/> <img src="https://user-images.githubusercontent.com/99061209/168413397-576e0889-2cc4-40ad-bb89-75e5b680c8dc.jpg" width="150" height="150"/> <img src="https://user-images.githubusercontent.com/99061209/168413399-98a3e437-ee2e-482d-88c4-f260654e6c10.jpg"width="150" height="150"/> <img src="https://user-images.githubusercontent.com/99061209/168413403-96e69aba-7685-464c-bbb1-2e9fc03709cd.jpg"width="150" height="150"/> <img src="https://user-images.githubusercontent.com/99061209/168413406-ef26ab40-bd91-4183-a060-8fb68fc90af9.jpg"width="150" height="150"/>



### 일기땀
- 소개: 운동, 식단, 신체 지수를 기록할 수 있는 안드로이드 앱.

- 안드로이드 스튜디오, 닷홈(Apache 2.4, PHP 7.4, MySQL 8.0) 사용해서 개발
 
1. 회원가입, 로그인, 로그아웃 
- 아이디 중복 체크를 통해 가입 유무를 확인하고 회원 정보 서버에 저장.
- 저장된 회원 정보와 로그인 시 입력 정보 체크 후 로그인. 
- 로그인 후 회원 아이디 sharedPreference에 저장(로그인 유지).
- 로그아웃(sharedPreference에 로그인된 아이디 삭제)

2. 운동, 식단, 신체 정보 기록 (비회원: SharedPreference / 회원: 서버 MySQL)
- 로그인을 하게 되면 기록된 데이터가 서버에 저장됩니다.
- 항목별 데이터는 CRUD 가능 <br/>

3. 운동 시간 측정(handler)
- 운동한 시간을 측정해 바로 기록될 수 있게 했습니다.  



### 라인업
- 소개: 함께 공연 볼 사람 구할 수 있는 웹사이트.
  (https://github.com/ttpoh/lineupwith)

1. 회원가입, 로그인, 로그아웃<br/>

2. 게시판, 댓글 CRUD
- 공연 멤버 모집 게시판, 댓글
- 공연 후기 게시판(게시물 작성: summernote)<br/>

3. 게시판 페이징
- 페이지를 get 방식으로 새로고침. <br/>

4. 세션, 쿠키
- 로그인 유지(세션)
- 공연 소식 팝업창(쿠키)<br/>

- 기간: 2022.03.08 ~ 2022.04.05

### 감상창고

- 소개: 문화 생활 후 기록할 수 있는 안드로이드 앱.
  (https://github.com/ttpoh/cstorage)<br/>

1. 감상 기록 저장 (SharedPreference / Recyclerview)
- 문화 생활(독서, 영화, 콘서트, 전시회, etc)에 대한 감상을 작성하게 되면 Recyclerview를 사용한 목록에 저장(SharedPreference)됩니다. <br/>

2. TO DO LIST (SharedPreference / ListView)
- 감상 관련 계획을 작성하게 되면 ListView를 사용한 목록에 저장(SharedPreference)됩니다. <br/>

3. 독서 검색 + 후기 추가 (네이버 책 검색 API)
- 독서 기록 저장 시 검색을 통한 항목 추가. 
- (검색 결과 중 원하는 도서 클릭하면 책 제목, 저자 2개의 데이터를 후기 추가하는 페이지에 입력) <br/>

4. 검색 (카카오맵 API, 키워드 검색)
- 문화 생활에 관련된 정보를 지역별 키워드 검색을 통해 얻을 수 있습니다. <br/>

5. 문화 생활 관련 사이트 배너, 배경음악(Thread)
- 메인 화면 하단부 배너에 문화 생활 관련 사이트 클릭시 이동 가능합니다. 
- 메인 화면에서 배경음악을 on/off 할 수 있습니다. <br/>

- 기간: 2022.02.01 ~ 2022.03.08




<br/>


----

읽어주셔서 감사합니다. <br/>
solution12441@gmail.com<br/>
