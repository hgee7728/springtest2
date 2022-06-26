

**K H s e m i p r o j e c t**

**TOMORROW**

**T E A M 2 : 내 일 의 집**

**김 연 종 박 준 현 윤 성 훈 이 동 근 장 효 기**





**CONTENTS**

01

06

07

08

09

**구성원 소개**

**클래스 다이어그램**

**URL 매핑 구조**

**히스토리 관리**

**테스트 케이스**

02

03

04

**개발 배경 및 구현 목표**

**개발환경**

**프로젝트 산출물**

10

**참조 사이트**

05

**스토리 보드**





01

**구성원 소개**





**TOMORROW**

구성원 소개

01

**조장: 장효기**

**박준현**

**윤성훈**

**김연종**

**이동근**





**TOMORROW**

구성원 소개

01

발표& PPT제작

스토어 메인페이지

스토어 카테고리 페이지

상품 상세 페이지

**김연종**

공통 header, footer

관리자 페이지

(상품 관리, 회원관리,

게시물 관리)

**팀장: 장효기**





**TOMORROW**

구성원 소개

01

발표

회원가입 페이지

로그인 페이지

회원정보 수정 페이지

발표& PPT제작

**박준현**

커뮤니티메인페이지

**이동근**

오늘의 스토리 페이지

(리뷰, 댓글 등록)





**TOMORROW**

구성원 소개

01

PPT 제작

내 정보 페이지

장바구니 페이지

결제 페이지

**윤성훈**





02

**개발 배경 및 구현 목표**





**TOMORROW**

개발 배경 및 구현 목표

02

“

오늘의 집

”

**STORE**

**COMUNITY**

**PRODUCT**

**+**

**팔 로 잉 , 사 진 ,**

**집 들 이**

**REVIEW**





**TOMORROW**

개발 배경 및 구현 목표

02

**TOMORROW**

“ ”

**오늘의**

**STORY**

**+**

**REVIEW STORE**

**댓글**





**TOMORROW**

개발 배경 및 구현 목표

02

**TOMORROW**

“ ”

**개발**

**목적**

**적극적인 리뷰 활동을 통한 사용자들의**

**소통 공간 마련과 스토어와의 유연한 연결**

**구현**

**게시판에서 사용자들 사이의 정보 공유가**

**자연스럽게 구매로 이어지는 페이지를 구현 목표**





03

**개발 환경**





**TOMORROW**

개 발

환 경

04

[개발환경]

\- Apache Tomcat Web Server 9.0

\- Visual Studio Code 1.66

\- Eclipse IDE for Enterprise Java Developers, Version: 2020-09 (4.17.0)

\- Get Started With Oracle Database 11 g Express Edition

/ Oracle SQL Developer, Version:Oracle IDE 17.2.0, Oracle IDE 21.2.1

\- listly(DB크롤링도구)

\- StarUML, Version: 5.0.1

[개발언어]

java(jdk-11.0.2), HTML5, CSS3, JS(jquery-3.6.0), ajax, jstl-1.2, gson-2.8.6, cos, ojdbc6

[OS 환경]

\- Windows 10 Pro/Home x64





04

**프로젝트 산출물**





04

**프로젝트 산출물**

**1. 프로젝트 일정**

**2. 요구사항 정의서**

**3. 단위업무 정의서**

**4. 유스케이스 다이어그램**

**5. ERD**





\1.

**프로젝트 일정**





**TOMORROW**

프 로 젝 트

일 정

03





\2.

**요구사항 정의서**





**TOMORROW**

요 구 사 항

정 의 서

03





**TOMORROW**

요 구 사 항 정 의 서

03





**TOMORROW**

요 구 사 항 정 의 서

03





**TOMORROW**

요 구 사 항 정 의 서

03





\3.

**단위업무 정의서**





**TOMORROW**

단 위 업 무

정 의 서

03





**TOMORROW**

단 위 업 무

정 의 서

03





**TOMORROW**

단 위 업 무

정 의 서

03





**TOMORROW**

단 위 업 무

정 의 서

03





**TOMORROW**

단 위 업 무

정 의 서

03





\4.

**유스케이스 다이어그램**





**TOMORROW**

유 스 케 이 스

다 이 어 그 램

03





\5.

**ERD**





**TOMORROW**

E R D

( 논 리 / 물 리 )





05

**스토리 보드**





**TOMORROW**

스토리 보드

05





**TOMORROW**

스토리 보드

05





**TOMORROW**

스토리 보드

05





**TOMORROW**

스 토 리

보 드

05

storyboardMain.jsp

\-

\-

CSS에서 @media를 이용하여 브라우저의 가로 너비가

변경될 때 1024px를 기준으로 게시글의 행과 열 배치가

달라지도록 구현.

썸네일 사진 div에 padding-bottom: 100%를 적용하여

브라우저 크기를 조절하면 반응형으로 사진 크기가 1:1

비율 자동 조절되도록 구현.





**TOMORROW**

스 토 리

보 드

05

storyboardRead.jsp





**TOMORROW**

스 토 리

보 드

05

storyboardRead.jsp

\-

\-

해당 게시글의 작성자 ID와 로그

인 Session의 ID를 비교하여 ID

가 일치하면 게시글 수정, 삭제

버튼이 보임.

댓글 작성 또한 로그인 Session

의 존재 여부에 따라서 작성할

수 있음.





**TOMORROW**

스 토 리

보 드

05

ProductDao.java

WriteStoryBoardServlet

.java

storyboardWrite.jsp

\-

상품 선택 부분은 DB에 저장되어있는 상품목록을 select 태그의

option 값으로 불러온 후 한가지 상품을 선택할 수 있도록 구현.





**TOMORROW**

스 토 리

보 드

05

\-

\-

페이지 상단 스토리 작성 가이드는 jQuery를 이용하여 접고 펼칠 수

있는 아코디언 방식을 구현.

사진 첨부 기능은 cos 라이브러리를 활용하여 워크스페이스에 사진

을 저장시킬 수 있고 글 내용 부분은 CKEditor4를 이용하여 글 작성

과 사진 첨부를 함께 할 수 있도록 하였음.

\-

모든 요소에 값을 입력한 후 게시물 등록을 누르면 로그인 Session

의 ID를 작성자로 하여 해당 게시물이 등록.





**TOMORROW**

스 토 리

보 드

05

\-

\-

상품 목록 페이지 : nav 태그로 카테고리 목록을 구성하

고 Ajax를 사용하여 각 카테고리를 클릭하면 카테고리에

해당하는 같은 category\_id 값을 가진 상품들로 목록을

구성할 수 있도록 한다.

목록마다 한 페이지의 6개 상품이 나오도록 하고 페이지

처리를 한다..

productList.jsp





**TOMORROW**

스 토 리

보 드

05

\-

\-

옵션 정보를 화면에 출력하기 위해 select 태그를 사용하고 상품마다 가지고 있는 옵션 종류에

따라 옵션 선택 메뉴가 화면에 나타나도록 한다. 옵션이 없을 수도 있고 여러 개일 수도 있다.

Bootstrap을 활용하여 메뉴바를 디자인한다.





**TOMORROW**

스 토 리

보 드

05

productDetail.jsp

– 상품을 구성하는 ProductVo와 상품이 갖고 있는 옵션 정보를 구성하는

ProductDetailVo를 분리하여 ProductVo에서 ArrayList 형태로 옵션값을 저장

할 수 있도록 한다.

– ArrayList 형태로 가져온 옵션 정보는 c태그의 forEach와 choose – when 태그

를 활용하고 index 값을 통해 옵션 종류를 구분하고 해당 옵션의 번호와 값을

가져와 select 태그 에 optPrice(옵션가격)와 calPrice(기존가격+옵션가격)함수

를 호출하여 계산하고 주문금액 부분에 출력한다.





**TOMORROW**

스 토 리

보 드

05

productList.jsp

ProductDao.java





**TOMORROW**

스 토 리

보 드

05

PorductVo.java

PorductDetailVo.java

\-

상품을 구성하는 ProductVo와 상품이 갖고 있는 옵션 정보를 구성

하는 ProductDetailVo를 분리하여 ProductVo에서 ArrayList 형태

로 옵션값을 저장할 수 있도록 한다.





**TOMORROW**

스 토 리

보 드

05

productDetail.jsp





**TOMORROW**

스 토 리

보 드

05

– button 의 클릭이벤트를 location.replace 와 id로 화면단 이동하여 화면 변화가 쌓이지

않게 하면서, 클릭마다 이동만 하도록 구현한다.





**TOMORROW**

스 토 리

보 드

05

CartInertServlet





**TOMORROW**

스 토 리

보 드

05

– 장바구니에 넣은 상품과 동일한 pNo (상품번호)가 없다

면 새로운 insert 문을 해주는 insertmyCart 로 연결해주

고 이미 같은 상품이 장바구니에 존재한다면 Cnt를 +1

하여 updatemyCart 로 연결함

– 선택한 상품을 새롭게 장바구니에 insert 하는 sql문





**TOMORRO**

**W**

스 토 리 보 드

05

– 기존에 있던 상품에 상품 갯수를 update하는 sql문

– ArrayList에 pNo (상품번호)와 id값을 이용해 전체

주문목록 테이블과 회원테이블을 조인하여 내 장바

구니 목록을 불러 올 수 있도록 하는 select 문





**TOMORROW**

스 토 리

보 드

05

cartList.jsp





**TOMORROW**

스 토 리

보 드

05

cartList.jsp

– 체크박스에 체크한 상품은 cartdel controller에 cNo (상품번호)를

보내 delete 문을 수행할 수 있도록 하였음

–

주문번호, 상품번호, 주문갯수, 주문옵션, 상품이름, 브랜드명, 상품

이미지를 장바구니.jsp 에 <c: forEach /> 반복문을 사용하여 모두

표현하였음.

–

장바구니에 물건이 없다면 선택된 상품이 없다고 표시





**TOMORROW**

스 토 리

보 드

05

**productEdit.jsp**





**TOMORROW**

스 토 리

보 드

05





**TOMORROW**

스 토 리

보 드

05





**TOMORROW**

스토리 보드

05

**productEdit.jsp**

\-

\-

상품번호와 상품 상세 번호를 입력 후 조회버튼을 클릭 시

productEdit.jsp의 script구문에서 함수 searchHandler()를 호출한다.

이 때 url에 상품번호와 상품 상세번호 값을 전달하고 sql문의 결과

값을 각각 입력란에 불러오기 위해 ajax의 json방식이 간단하고 편리

하여 사용했다.

만약 해당 상품번호와 상품 상세번호가 상품의 데이터가 담겨있는

테이블에 존재하지 않는다면 success 함수의 매개변수 result는 null

값을 반환하게 되고 조회하지 못했다는 알림창이 뜨면서 상품 수정

페이지로 다시 돌아가게 된다.





**TOMORROW**

스토리 보드

05

**AdProductSearchServlet.java**

\-

AdProductSearchServlet클래스는 AdminService클래스에 사용

자가 입력한 상품번호와 상품 상세번호를 전달하여

searchProduct()를 실행한다.

\-

\-

\-

jsp에서 전달받은 상품번호와 상품 상세번호는 정수가 아닌 문

자열 값으로 받기때문에 정수변환을 수행한다.

결과값을 productEdit.jsp에 전달하기 위해 문자 출력 스트림인

PrintWriter클래스의 변수을 사용한다.

JSON방식으로 produtEdit.jsp에 결과값을 전달한 후 버퍼를 비

우고 스트림을 닫는다.





**TOMORROW**

스토리 보드

05

**AdminDao.java**

\-

AdminDao클래스의 함수 searchProduct는 사용자가 입력한 상품번호

와 상품 상세번호를 매개변수로 가져와 3개의 select문을 통해 해당

상품 기본 정보, 상품 상세 정보, 상품 이미지 정보를 조회한다.

\-

\-

매개변수로

가져온

값을

where조건절에

사용하기

위해

PreparedStatement 클래스를 사용했다.

sql문의 결과값을 Product 객체 담아 service-servlet순으로 전달하게

되는데 만약 sql문의 오류가 발생하게 되면 객체에 값을 전달하지 못

하고 null값을 반환하는데 오류 내용과 오류 위치를 출력한다.





06

**클래스 다이어그램**





클 래 스 다 이 어 그 램

**P r o d u c t**

kh.semi.tomorrow.common

kh.semi.tomorrow.product.controller

**JdbcTemp**

**StoryMainServlet**

+getConnection(): Connection

+close(Connection): void

+close(PreparedStatement): void

+close(ResultSet): void

kh.semi.tomorrow.product.model.dao

**ProducDao**

\+ selectAllProduct(pNo) : ArrayList<ProductVo>

+setAutocommit(Connection, onoff): void

+commit(Connection): void

+rollback(Connection): void

-pstmt : PreparedStatement

-rs : ResultSet

+selectAllProduct(Connection conn): ArrayList<ProductVo>

+selectAllProduct(Connection conn, int pNo): ArrayList<ProductVo>

+selectAllProduct(Connection conn, int startRnum, int endRnum,

int pageCateId, int pNo): ArrayList<ProductVo>

+listStoryBoard(Connection conn, int pNo): ArrayList<StoryBoardVo>

+selectProduct(Connection conn, int pNo): ProductVo

+countProduct(Connection conn, int pageCateId): int

**ProductListServlet**

\+ selectAllProduct(startRnum, endRnum,

pageCateId, pNo) : ArrayList<ProductVo>

kh.semi.tomorrow.product.model.vo

**ProductVo**

-countProduct(int pageCateId):int

\- pNo : int

\- pName : String

\- pBrand : String

\- pContent : String

\- pPrice : int

**CategoryServlet**

\- cateId : int

kh.semi.tomorrow.product.model.service

**ProducService**

\+ selectAllProduct(startRnum, endRnum,

pageCateId, pNo) : ArrayList<ProductVo>

\- cateName : String

\- optNo : int

\- optVal : String

-dao: ProductDao

\- countProduct(int pageCateId):int

\- optPrice : int

+selectAllProduct(): ArrayList<ProductVo>

+selectAllProduct(int pNo): ArrayList<ProductVo>

+selectAllProduct(int startRnum, int endRnum,

int pageCateId, int pNo): ArrayList<ProductVo>

+listStoryBoard(int pNo): ArrayList<StoryBoardVo>

+selectProduct(int pNo): ProductVo

\- pSeq : int

\- productImgNo : int

\- productImgName : String

\- productImgSize : int

\- Pdt : ProductDetailVo

\- Pdvo : ArrayList<ProductDetailVo>

\- Ovo : ArrayList<OrderVo>

**ProductSelectServlet**

\+ selectProduct(pNo): ProductVo

\+ listStoryBoard(pNo):ArrayList<StoryBoardVo>

+countProduct(int pageCateId): int

+ProductVo()

+toString() : String

+getter and setter()





클 래 스 다 이 어 그 램

**P r o d u c t**

kh.semi.tomorrow.product.model.vo

**ProductVo**

\- pNo : int

\- pName : String

**ProductDetailVo**

\- pBrand : String

\- pContent : String

\- pPrice : int

\- cateId : int

\- optNo : int

\- optName : String

\- optVal : String

\- optPrice : String

\- pSeq : int

\- cateName : String

\- optNo : int

\- optVal : String

\- pNo : int

\- optPrice : int

+ProductVo()

+toString() : String

+getter and setter()

\- pSeq : int

\- productImgNo : int

\- productImgName : String

\- productImgSize : int

\- Pdt : ProductDetailVo

\- Pdvo : ArrayList<ProductDetailVo>

\- Ovo : ArrayList<OrderVo>

+ProductVo()

+toString() : String

+getter and setter()





클 래 스 다 이 어 그 램

**S t o r y**

**b o a r d**

kh.semi.tomorrow.common

kh.semi.tomorrow.storyboard.controller

**JdbcTemp**

kh.semi.tomorrow.storyboard.model.dao

**StoryBoardDao**

**DeleteStoryBoardServlet**

+getConnection(): Connection

+close(Connection): void

+close(PreparedStatement): void

+close(ResultSet): void

+setAutocommit(Connection, onoff): void

+commit(Connection): void

+rollback(Connection): void

-pstmt : PreparedStatement

-rs : ResultSet

+deleteStoryBoard(int bNo) : int

+writeStoryBoard(Connection conn, StoryBoardVo vo) : int

+updateStoryBoard(Connection conn, StoryBoardVo vo) : int

+deleteStoryBoard(Connection conn, int bNo) : int

+writeStoryReComment(Connection conn, StoryRecommentVo vo) : int

+listStoryBoard(Connection conn) : ArrayList<StoryBoardVo>

+listStoryBoard(Connection conn, int startRnum, int endRnum) :

ArrayList<StoryBoardVo>

+readStoryBoard(Connection conn, int bNo) : StoryBoardVo

+countStoryBoard(Connection conn) : int

+hitStoryBoard(Connection conn, int bNo) : int

**ListStoryBoarServlet**

+listStoryBoard(int startRnum, int

endRnum) : ArrayList<StoryBoardVo>

+countStoryBoard() : int

kh.semi.tomorrow.storyboard.model.vo

**StoryBoardVo**

**ReadStoryBoardServlet**

\- bNo : int

\- bTitle : String

\- bContent : String

\- bWriter : String

\- mId : String

+readStoryBoard(int bNo) : StoryBoardVo

+hitStoryBoard(int bNo) : int

kh.semi.tomorrow.storyboard.model.service

**StoryBoardService**

\- bCnt : int

\- bDate : Timestamp

\- pNo : int

\- bNy : int

\- mIntro : String

\- bRecommentList :

ArrayList<StoryRecommentVo>

**UpdateStoryBoardServlet**

-dao : StoryBoardDao

+readStoryBoard(int bNo) : StoryBoardVo

+writeStoryBoard(StoryBoardVo vo) : int

+updateStoryBoard(StoryBoardVo vo) : int

+deleteStoryBoard(int bNo) : int

+writeStoryReComment(StoryRecommentVo vo) : int

+listStoryBoard() : ArrayList<StoryBoardVo>

+listStoryBoard(int startRnum, int endRnum) :

ArrayList<StoryBoardVo>

+readStoryBoard(int bNo) : StoryBoardVo

+countStoryBoard() : int

+hitStoryBoard(int bNo) : int

**WriteDoStoryBoardServlet**

+writeStoryBoard(StoryBoardVo vo) : int

+updateStoryBoard(StoryBoardVo vo) : int

\+ StoryBoardVo()

\+ toString() : String

\+ getter and setter()





07

**URL 매핑 구조**





**TOMORROW**

U R L 매 핑 구 조

07





08

**히스토리 관리**





**TOMORROW**

히 스 토 리

관 리

08





09

**테스트 케이스**





**TOMORROW**

테 스 트

케 이 스

09





**TOMORROW**

테 스 트

케 이 스

09





**TOMORROW**

테 스 트

케 이 스

09





10

**참조 사이트**





**TOMORROW**

참 조

사 이 트

10

[참조사이트]

\- 오늘의 집 : https://ohou.se/

\- oven app : https://ovenapp.io/

\- Bootstrap : https://getbootstrap.com/

\- WYSIWYG - ckeditor5 : https://ckeditor.com/ckeditor-5/demo/

\- ERDcloud : https://www.erdcloud.com/

\- W3Schools : https://www.w3schools.com/

\- **Dynamic Dummy Image Generator :** https://dummyimage.com/





SEMI PROJECT : TEAM2 : TOMORROW

**THANK**

**YOU**

