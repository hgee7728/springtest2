




# 파이널 프로젝트 - PISIC (PIck your muSIC) 음원스트리밍 사이트 <img width="50" alt="image" src="">


## Contents <img width="30" src="">
1. 팀 소개
2. 프로젝트 개요
3. 설계의 주안점
4. 개발환경
5. 주요기능
6. Document

<br>

## 1️⃣ 팀 소개
<img width="1911" alt="image" src="">

<br>

## 2️⃣ 프로젝트 개요
<img width="1913" alt="image" src="">

<img width="30" alt="image" src=""> ***내용내용***
  - 내용
  - 내용
  - 내용

<br>

## 3️⃣ 설계의 주안점
- **접근성**
  - 메뉴를 직관적으로 표기하여 누구나 쉽게 사용할 수 있도록 접근성을 높임
- **편의성**
  - 100% 웹 기반으로 모든 구성원이 시간과 장소에 제약없이 실시간으로 반영된 정확한 자료를 확인할 수 있음
- **오류의 최소화**
  - 많은 테스트를 통해 여러가지 오류들을 수정해 사용자의 불편함을 최소화함

<br>

## 4️⃣ 개발환경
<img width="1711" alt="image" src="">

<br>

## 5️⃣ 주요기능

<div align="center">
<img width="200" alt="image" src="">
</div>

<details>
<summary><h3>✅ 박준현 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src=""> 내용내용내용 <img width="250" alt="image" src="">
</div>

<br>

<div align="center">
  
![1_로그인)내용,내용](GIF 경로)
  
</div>

- 내용
- 내용
- 내용
---
<div align="center">
<img width="100" alt="image" src="">
</div>

<img width="1887" alt="image" src="">

- 내용
- 내용
- 내용

</details>

---

<details>
<summary><h3>✅ 장효기 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src=""> 내용 내용 <img width="250" alt="image" src="">
</div>

<br>

<div align="center">

![2_메인)내용 내용](gif 경로)

</div>

- 내용
- 내용
- 내용
---
<div align="center">
<img width="100" alt="image" src="">
</div>

<img width="1887" alt="image" src="">

- 내용
- 내용
- 내용

</details>

---

<details>
<summary><h3>✅ 근태관리 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 출근 등록
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![12_근태관리)출근등록](https://user-images.githubusercontent.com/83773369/181917973-ff194941-591a-4afc-98e6-ec8b2429ed0d.gif)

</div>

- 출근 버튼 클릭 시 출근 시간이 DB에 저장되며 내 근태 현황에 리스트로 확인 가능
- 출근시간이 DB에 저장되어 있다면 출근 버튼은 비활성화, 퇴근 버튼은 활성화
- 출근시간이 저장 되어있지 않다면 퇴근 버튼은 비활성화 상태

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 퇴근 등록
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![13_근태관리)퇴근등록](https://user-images.githubusercontent.com/83773369/181917986-deb3019f-69a9-4796-9214-11dc1ca4f9cd.gif)

</div>

- 퇴근 버튼 클릭 시 퇴근 시간이 DB에 저장되며 누적 근무 시간이 늘어남
- 퇴근시간이 저장되어 있다면 퇴근 버튼은 비활성화 상태

---
<div align="center">
<img width="100" alt="image" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1577544307/noticon/a7cmr2ibsfyuwcydpvny.png">
</div>

<img width="1908" alt="image" src="https://user-images.githubusercontent.com/83773369/181918128-4e12b874-481a-44fd-92d7-5d28cc147178.png">

- 시간 단위로 계산되기 때문에 1시간 이상 근무해야 퇴근 처리 가능
- 퇴근시간 저장되면 오늘 날짜의 퇴근시간 - 출근시간으로 계산하여 소정 근무 시간 구함

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 내 근태 현황 
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![14_근태관리)내근태현황](https://user-images.githubusercontent.com/83773369/181917989-5e53b81f-a743-4253-9059-b1b0c09d825d.gif)

</div>

- highcharts API를 사용하여 하프도넛 그래프로 누적 근무 시간, 남은 근무 시간 수치를 시각화 함
- 누적 근무 시간, 남은 근무 시간 확인
- 해당 월에 언제 얼마나 근무했는지 테이블로 확인

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 내 연차 내역
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![15_근태관리)내연차내역](https://user-images.githubusercontent.com/83773369/181917991-4b24c654-71c5-427b-bdc8-7051440113ee.gif)

</div>

- 총 연차, 사용 연차, 잔여 연차 확인
- 연차 사용 내역, 연차 생성 내역 확인
- 사용 내역 2개씩 뜨도록 페이징처리

---
<div align="center">
<img width="100" alt="image" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1577544307/noticon/a7cmr2ibsfyuwcydpvny.png">
</div>

<img width="1913" alt="image" src="https://user-images.githubusercontent.com/83773369/181918298-534776f7-d952-47dd-96f4-49d3b805d9bc.png">

- highcharts API를 사용하여 내가 원하는 대로 컬러 변경, 퍼센트로 표기하는 title의 위치와 style을 지정하는 등 
프로젝트에 맞게 커스텀 진행

</div>
</details>

---

<details>
<summary><h3>✅ 채팅 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 채팅 홈 
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![16_채팅)채팅홈](https://user-images.githubusercontent.com/83773369/181918369-8020788a-d452-4eac-a0e7-d8595aef79e2.gif)

</div>

- websocket API 사용
- 사원목록에서 친구 리스트를 조회
- 채팅 리스트에서 내가 참여한 채팅방들, 가장 마지막 대화 조회
- 채팅방 클릭 시 채팅 내역 확인

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 채팅방 만들기 및 멤버 초대
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![17_채팅)방만들기,멤버초대](https://user-images.githubusercontent.com/83773369/181918371-1b6286ab-5725-470b-b1b4-eb6324b8375e.gif)

</div>

- 채팅방 생성 시 대화상대를 선택하지 않았을 때, 방 제목을 입력하지 않았을 때 alert
- 새로 만들어진 방 상세조회 시 채팅 참여 인원 수와 채팅 참여자 확인

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 채팅 발신 및 수신
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![18_채팅)채팅발신,수신](https://user-images.githubusercontent.com/83773369/181918373-38edc9e7-cfc9-4743-9d31-34a3f3285ace.gif)

</div>

- 채팅 발신 시 오른쪽 말풍선으로 표시
- 채팅 수신 시 왼쪽 말풍선으로 표시
- 같은 사람이 여러 개 채팅을 보낼 경우 말풍선만 띄워 줌

---
<div align="center">
<img width="100" alt="image" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1577544307/noticon/a7cmr2ibsfyuwcydpvny.png">
</div>

<img width="1909" alt="image" src="https://user-images.githubusercontent.com/83773369/181918569-bbd800fa-3be7-48e5-b09f-807ef65cd2fe.png">

- 라이브러리를 pom.xml에 설정
- EchoHandler 클래스 생성
- servlet-context.xml에서 웹소켓 핸들러를 등록 후 웹소켓 서버로 사용할 클래스를 bean으로 생성

<img width="1904" alt="image" src="https://user-images.githubusercontent.com/83773369/181918620-edab2420-4327-4431-ae63-da83c46876e4.png">

- jsp에서 웹 소켓 접속, 메시지 발신, 수신 코드 작성
- 메시지 발송 시 이름, 채팅 내용, 방 번호 controller에 전달
- controller에서 받은 메시지를 웹 소켓 세션의 sendMessage()를 통해 모든 유저에게 메시지를 전달하여 수신기능 구현
- jsp에서 전달받은 메시지를 TextMessage의 getPayload()를 통해 controller에서 확인 가능
- 메시지 발송 시 채팅 테이블에 insert하여 DB에 저장
- jsp에서 메시지 수신 시 보낸사람과 받는사람을 로그인 한 사람과 비교하여 말풍선 색깔로 구분해줌
- 같은 사람이 여러 개 채팅을 보낼 경우 말풍선만 띄워줌
- 채팅이 여러 개일 경우 스크롤바가 생성되어 가장 하단으로 가도록 설정

---

<div align="center">
<img width="100" alt="image" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1577544307/noticon/a7cmr2ibsfyuwcydpvny.png">
</div>

<img width="1916" alt="image" src="https://user-images.githubusercontent.com/83773369/181918630-9fc883a3-764c-4ad2-b744-e547c4125034.png">

- 채팅 내용 조회 시 중복된 행은 하나만 조회되도록 차집합 역할을 해주는 MINUS를 이용하여 2개의 SELECT문을 하나의 쿼리로 조회
- LEFT OUTER JOIN을 이용하여 채팅 내용이 없는 방도 조회
- 채팅번호 DESC로 정렬 후 채팅 내용이 없는 방은 마지막으로 정렬

</div>
</details>

---

<br>

<div align="center">
<img width="202" alt="image" src="https://user-images.githubusercontent.com/83773369/182773336-b2226c1b-02ee-445b-aa31-5ebf09254acb.png">
</div>

<details>
<summary><h3>✅ 주소록 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 주소록 조회, 검색
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![주소록X2](https://user-images.githubusercontent.com/83773369/182774004-e7dc93e9-a2e9-4735-bbb7-2e7753b69c1c.gif)

</div>

</div>
</details>

---

<details>
<summary><h3>✅ 공지사항 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 공지사항 글쓰기
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![공지사항글쓰기X2](https://user-images.githubusercontent.com/83773369/182774185-c56ebce7-6203-4446-a27c-ca2b0e9fa47d.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 공지사항 삭제
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![공지사항삭제X2](https://user-images.githubusercontent.com/83773369/182774290-cf610f67-1023-46dc-8397-75ccac48fc83.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 공지사항 조회, 검색
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![공지사항조회X2](https://user-images.githubusercontent.com/83773369/182774372-17637cd4-ae18-4ab8-9b33-1db062e7fe4b.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 공지사항 상세 조회
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![공지사항상세보기X2](https://user-images.githubusercontent.com/83773369/182774357-25955578-fa24-4f12-892f-b84f14eb0cbd.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 공지사항 수정
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![공지사항수정X2](https://user-images.githubusercontent.com/83773369/182774367-96fae620-c5c7-41d4-9b94-93e81dbbdc2d.gif)

</div>

</div>
</details>

---

<details>
<summary><h3>✅ 메일 </h3></summary>
<div markdown="1"> 


<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 메일 쓰기
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![메일쓰기x2](https://user-images.githubusercontent.com/83773369/183241003-49488764-ae7e-4ba5-bdf5-54ec849c7ab4.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 메일 조회
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![메일조회X2](https://user-images.githubusercontent.com/83773369/182774905-0b3e24d9-75f6-4edc-81d1-342c0df88547.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 메일 읽기
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![메일읽기X2](https://user-images.githubusercontent.com/83773369/182774913-b28a843a-0f87-4995-96b5-d397112bc23e.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 메일 삭제
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<br>

<div align="center">

![메일삭제x2](https://user-images.githubusercontent.com/83773369/183241009-396ad828-9e50-4f5c-badb-551cfd553ae1.gif)

</div>


</div>
</details>

---

<br>

<div align="center">

<img width="202" alt="image" src="https://user-images.githubusercontent.com/83773369/183080289-febe828b-1b19-4f65-9dad-8bea6533b119.png">

</div>

<details>
<summary><h3>✅ 로그인 / 로그아웃 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 로그인 / 로그아웃
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![로그인,로그아웃](https://user-images.githubusercontent.com/83773369/183080597-66acda39-57df-4ee5-b7e4-339a432cf700.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 아이디 찾기
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![아이디 찾기](https://user-images.githubusercontent.com/83773369/183080784-867d5021-29aa-4662-a6c2-ba53de7dcd2b.gif)

</div>


---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 비밀번호 찾기
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![비밀번호 찾기](https://user-images.githubusercontent.com/83773369/183080924-531ad121-d170-4a89-ac90-784ebb50b249.gif)

</div>

</div>
</details>

---

<details>
<summary><h3>✅ 내 정보 수정 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 내 정보 수정
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![내정보수정](https://user-images.githubusercontent.com/83773369/183081230-034b0021-6334-4492-9eff-1f37fca867bc.gif)

</div>

</div>
</details>

---

<details>
<summary><h3>✅ 캘린더 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 캘린더 등록 / 조회
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![캘린더_등록,조회](https://user-images.githubusercontent.com/83773369/183081365-872dc245-4f1c-4813-b863-af12728968de.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 캘린더 삭제
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![캘린더_삭제](https://user-images.githubusercontent.com/83773369/183081424-26963f60-b666-4bfe-b855-998077ed918f.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 캘린더 수정
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![캘린더_수정](https://user-images.githubusercontent.com/83773369/183081490-bcf59907-7f32-4039-b461-9e4956d01791.gif)

</div>

</div>
</details>

---

<details>
<summary><h3>✅ 투표 </h3></summary>
<div markdown="1"> 

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 투표 등록 / 투표
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![투표_등록,투표](https://user-images.githubusercontent.com/83773369/183081570-1632a0ba-382a-425b-bba5-543aede817c1.gif)

</div>

---

<div align="center">
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png"> 투표 조회 / 검색
<img width="250" alt="image" src="https://media.discordapp.net/attachments/692994434526085184/1002954522253074472/a0c55ca0bfe82413.png">
</div>

<div align="center">

![투표_조회,검색](https://user-images.githubusercontent.com/83773369/183081631-16d264bb-8e5a-4e1f-98ee-fcd802f9d8ee.gif)

</div>

</div>
</details>

---

<br>


## 6️⃣ Document

<br>

##  1. 개발 일정

<img width="1906" alt="image" src="">

<br>

## 2. 유스케이스

<img width="1707" alt="image" src="">

<br>

## 3. ERD

![내용 내용](png 경로)


<br>

## 4. Sequence Diagram

![내용 내용](png 경로)

<br>

## 5. Class Diagram



<br>

