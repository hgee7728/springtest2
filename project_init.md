﻿

팀 프로젝트 정보

Tomorrow (장효기)

팀명(팀장)

제목

내일의 집

개요

집을 꾸밀 수 있는 상품(가구, 페브릭, 조명)을 구매할 수 있는 스토어와

스토어에서 구매를 실행한 구매자가 작성하는 오늘의 스토리 게시물을 볼 수

있는 게시판을 구현한다. 그리고 두 페이지 사이에서 활발한 교류로 정보를

공유하고 구매에 도움을 받을 수 있는 사이트를 구현한다.

\1. 로그인 시

구현기능

a. 마이페이지 활용 가능

b. 본인 게시물 작성 및 모아보기 가능

c. 장바구니 활용 가능

\2. 스토어 페이지에서 해당 상품에 대한 리뷰 바로 확인 가능

\3. 상품 상세페이지에서 옵션에 따른 주문 금액 계산

\4. 장바구니와 주문 페이지로 정보 전달

\5. 오늘의 스토리 페이지(리뷰)의 게시물 상품을 선택하여 작성

\6. 게시물의 로그인 여부에 따라 댓글 기능 사용 가능

\7. 본인 게시물의 수정, 삭제 가능

\8. 관리자 페이지에서 사용자들의 회원 정보 관리 가능(탈퇴, 주문)

\9. 관리자 페이지에서 게시물 등록, 수정, 삭제 가능

\10. 관리자 페이지에서 스토어 상품 등록, 수정, 삭제가능

팀원별

김연종

박준현

장효기

\> 관리자 페이지 담당

관리자 메인 페이지 구성

단위업무

상품 등록, 수정, 삭제 페이지 구성

주문 목록 페이지(전달 받은 데이터 list 페이지) 구성

회원 관리 목록 페이지 구성

\> 오늘의 스토리 게시판 담당

커뮤니티 메인 페이지 구성

오늘의 스토리 게시물 글쓰기 페이지 구성

오늘의 스토리 게시물 등록, 수정, 삭제 가능

오늘의 스토리 댓글 기능

\> 스토어 페이지 담당

스토어 메인 페이지 구성

카테고리별 상품 목록 페이지 구성

상품 상세 페이지 구성

리뷰 버튼 클릭 시 해당 상품 관련 오늘의 스토리 목록 구성

바로구매/장바구니 페이지 이동 구현





윤성훈

이동근

\> 마이페이지 (장바구니, 주문 상세, 결제 페이지 등) 담당

장바구니 페이지 구성

주문/결제 페이지 구성

내 정보 페이지 구성

\>로그인 관련 기능 담당

회원가입 페이지 구성

로그인 페이지 구성

회원정보수정 페이지 구성

설계 주안점

오늘의 스토리 페이지에서 사용자가 구매한 상품을 게시글 형태로 리뷰를

남길 수 있도록 하고, 이러한 게시물을 상품의 상세페이지에서 확인할 수

있고, 스토리 게시판 페이지로 바로 이동하여 확인할 수 있는 유연함을

구현한다.

관리자 로그인(admin/admin)을 했을 때, 일반 사용자와 동일한 기능을

수행하면서 추가적으로 활성화 되는 관리자 기능을 구현한다.

오늘의 스토리 게시판의 게시물 삭제, 상품 등록, 삭제, 수정, 스토어의 상품

등록, 수정, 삭제, 회원 정보 관리 등 관리자 페이지에서 관리할 수 있도록

한다.

사용기술 및

개발환경

[개발환경]

\- Apache Tomcat Web Server 9.0

\- Visual Studio Code 1.66

\- Eclipse IDE for Enterprise Java Developers, Version: 2020-09 (4.17.0)

\- Get Started With Oracle Database 11g Express Edition

/ Oracle SQL Developer, Version:Oracle IDE 17.2.0, Oracle IDE 21.2.1

\- listly(DB크롤링도구)

\- StarUML, Version: 5.0.1

[개발언어]

java(jdk-11.0.2), HTML5, CSS3, JS(jquery-3.6.0), ajax, jstl-1.2, gson-2.8.6,

cos, ojdbc6

[OS 환경]

\- Windows 10 Pro/Home x64

[참조사이트]

-oven app : https://ovenapp.io/

\- 오늘의 집 : https://ohou.se/





\- Bootstrap : https://getbootstrap.com/

-위지위그 - ckeditor5 : https://ckeditor.com/ckeditor-5/demo/

-erdcloud : https://www.erdcloud.com/

