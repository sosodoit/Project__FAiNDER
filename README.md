***FOR FAiNDER PROJECT WEBSERVICE DEVELOP***

## 2021.12.04 GOAL
■ (FAPP)배포 - REACT APP <br>
■ (FWEB)웹페이지 - FLASK WEB <br> 
□ 부가기능추가 - 자동신고 <br>
  EX) 가상의 경찰청 사이트를 만들고 신고 버튼을 누르면 신고 내역이 가상 사이트에 나온다는 시나리오 <br>
□ 부가기능추가 - 범칙행위 시점의 타임라인 크롭 <br>
□ 부가기능추가 - 날짜, 장소 등의 정보를 실제 블랙박스 메타 데이터 사용해보기 <br>
  EX) 블랙박스 API는 해당 회사만 사용가능, 오픈되어 있지 않으므로 실제 블박 메타 데이터를 확인 후 따라 사용해보고 <br>
  만일 블랙박스 API를 이용할 적에 구현 가능성이 있는지 확인해보기 위함 <br>
□ 모델기능추가 - 끼어들기(탐지) <br>
□ 모델기능추가 - 차량추적(트래킹) <br>
□ 모델기능개선 - 번호판 인식 오류 제거 <br>
  EX) 한 영상 안에 범칙 행위가 여러개일 경우에 중복 제거 <br>

## 11/19 UPDATE
■ Flask, Firebase 연결 <br>
■ 회원가입/로그인/로그아웃 <br>
■ 메인페이지/블랙박스특약통합조회페이지/신고기록조회페이지/신고기록상세페이지/신고하기페이지 <br>
■ 페이지 url mapping <br>
■ 신고기록조회페이지에 유저 신고 기록 카운트(db)가지고 목록 나타내기 <br>

#### 11/22 UPDATE
■ 신고기록상세페이지에 특정 신고 기록 눌렀을 때 해당 상세 내용(db) 나타내기 <br>
■ ID, PW 유효성 검사 <br>
■ 특정 ID로 로그인 시 해당 유저 상세 내용(db) 나타내기 <br>
□ db 신고0 예외처리하기 <br>
□ url 개선하기 [참고](https://wikidocs.net/81046#1) <br>

#### 11/23 UPDATE
■ 세부 UI 디자인 짜기 <br>
■ 템플릿으로 UI 구현 <br>
■ 로그인/회원가입/메인페이지 완료 <br>

#### 11/24 UPDATE
■ 신고 기록에 표시할 내용 <br>
□ (크롭된 영상도 넣을 것인지 확정) <br>
■ 마이 페이지에 들어갈 내용과 데이터베이스 짜기(메인 페이지의 상세페이지) <br>
■ 보험사 데이터베이스 생성 후 <br> 
□ 마이 페이지에 넘기기 <br>
▲ 회원가입/로그인 실패시 알림창 <br>

#### 11/25 UPDATE
□ 리액트 네이티브 앱 연동 <br>
□ 배포 확정 <br>
▲ 신고기록조회페이지/신고기록상세페이지/신고하기페이지 db <br>
■ 회원가입/로그인 실패시 알림창 <br>

#### 11/26 UPDATE
□ 파이큐티에 스크롤 넣기 <br>
□ ID 어떻게 할 것인지 확정 및 최종 수정 <br>
■ 신고기록조회페이지/신고기록상세페이지/신고하기페이지 db <br>
▲ flask web deploy... <br>

#### 11/27 UPDATE
▲ flask web deploy... <br>
□ 발표 피피티 수정 <br>
□ 영상 확정 <br><br> 

#### 12/08 UPDATE (예정)
□
□

***COMPLETE FAiNDER SERVICE CONNECT TO THE FLASK WEB***
