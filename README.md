# 중고 거래 웹사이트 
JSP + Servlet 중고 거래 사이트 - 가지나라

## 🖥 프로젝트 소개
당근마켓과 중고나라를 모티브로 한 중고 거래 웹사이트 제작 프로젝트입니다. 중고 물품을 판매 및 구매할 수 있고, 회원들간 자유롭게 작성할 수 있는 커뮤니티 게시판을 구현하는 것을 목표로 했습니다.
<br>

## 📅 개발 기간
2022.10.17~ 2022.11.01 (약 2주)
<br>

## 🔧 개발 환경
- OS : Microsoft Windows 10
- WAS : Apache Tomcat 9.0
- IDE : Eclipse
- DB : Oracle DB
- 개발 언어 : HTML, CSS, Bootstrap / JavaScript, jQuery / Java 11
- 개발 프레임워크 : Mybatis
- 라이브러리 : jQuery, jackson-json
<br>

## 📌 MY 구현 기능
- 담당 업무 : 주제선정/ 회원 관리(회원 삭제, 검색, 정보 수정)DB설계/ 상품 관리(상품 삭제, 검색, 정보 수정)/ 문의글 관리(문의글 쓰기, 검색, 수정, 삭제)/ 챗봇 기능/ CSS
#### [회원 관리]
- 관리자는 사용자의 정보를 아이디, 이름, 계정상태, 등급으로 조회할 수 있습니다.
- 관리자는 사용자의 정보를 수정할 수 있습니다.
- 가입된 사용자가 회원 탈퇴시 회원가입 상태가 변경됩니다.
- 사용자의 등급을 변경할 수 있습니다.

#### [상품 관리]
- 관리자는 상품의 정보를 작성자의 아이디, 이름, 카테고리, 제목으로 조회할 수 있습니다.
- 관리자는 상품의 정보를 수정할 수 있습니다.
- 관리자는 상품을 삭제할 수 있습니다.


#### [문의글 관리]
- 회원은 문의 게시판에 문의글을 작성하고 여러장의 이미지를 올릴 수 있습니다.
- 작성자와 관리자만 문의글을 열람, 수정, 삭제할 수 있습니다.
- 관리자는 문의글에 답글을 작성하고 답글은 해당 문의글 바로 아래에 위치해야 합니다
- 관리자만이 답글을 수정, 삭제할 수 있습니다.

#### [챗봇]
- 회원은 웹사이트 하단의 버튼 클릭으로 챗봇을 실행할 수 있습니다.
- 챗봇(관리자)은 회원에게 서비스 번호를 메시지로 보여줍니다.
- 회원은 번호를 입력해 원하는 서비스로 이동합니다.

<br>

## 💁🏻‍♀️ 멤버 구성
-인원 : 4명<br>
-김도유, 김동환, 이재영, 임재헌

## 📌 ERD
<img width="754" alt="2차ERD" src="https://user-images.githubusercontent.com/112562015/207402568-36add992-0616-4f48-8d55-a2040d045aaa.png"><br><br><br>

##  화면 구현 및 기능 설명
### ✏️ 메인 화면
<img width="600" alt="메인"  src="https://user-images.githubusercontent.com/112562015/207404059-5fc19255-9a7a-4827-be6b-193a9d204988.png"><br><br><br>

## ✏️ QNA 메인 화면
<img width="600" alt="qna"  src="https://user-images.githubusercontent.com/112562015/207405367-27cb6f00-c468-4d15-8034-c988c45ecd50.png">
- 작성자와 관리자만 문의글을 열람, 수정, 삭제할 수 있습니다.<br>
- 관리자는 문의글에 답글을 작성하고 답글은 해당 문의글 바로 아래에 위치합니다.<br><br><br>


## ✏️ QNA 
<img width="438" alt="qna상세"  src="https://user-images.githubusercontent.com/112562015/207407212-7d1ac68a-1f4a-4a4d-8b15-ece7a71732c3.png">
- 작성자와 관리자만 문의글을 열람, 수정, 삭제할 수 있습니다.<br>
- 회원은 문의 게시판에 문의글을 작성하고 여러장의 이미지를 올릴 수 있습니다.<br><br><br>

## ✏️ QNA 관리자 - 문의글에 대한 답글 작성 화면
<img width="600" alt="qna2" src="https://user-images.githubusercontent.com/112562015/207405430-9993f057-fd44-41f8-9431-a7332bf6b347.png">
-관리자만이 답글을 수정, 삭제할 수 있습니다.<br><br>

## ✏️ 회원 관리 메인 화면
<img width="600" alt="회원관리메인" src="https://user-images.githubusercontent.com/112562015/207405491-3bb6ad20-f2f6-4066-b4dc-e2cc407118c6.png">
- 관리자는 사용자의 정보를 아이디, 이름, 계정상태, 등급으로 조회할 수 있습니다.<br>
- 관리자는 사용자의 정보를 수정할 수 있습니다.<br>
- 가입된 사용자가 회원 탈퇴시 회원가입 상태가 변경됩니다.<br>
- 사용자의 등급을 변경할 수 있습니다.<br><br><br>

## ✏️ 상품 관리 메인 화면
<img width="600" alt="상품관리" src="https://user-images.githubusercontent.com/112562015/207406458-e4afa95e-2a37-458c-965a-a9034a75f6a0.png">

## ✏️ 상품 수정 및 삭제
<img width="500" alt="상품수정" src="https://user-images.githubusercontent.com/112562015/207406544-66a5b124-e70a-4632-bd44-70dc9503c448.png">
- 관리자는 상품의 정보를 작성자의 아이디, 이름, 카테고리, 제목으로 조회할 수 있습니다.<br>
- 관리자는 상품의 정보를 수정할 수 있습니다.<br>
- 관리자는 상품을 삭제할 수 있습니다.<br><br><br>

## ✏️ 챗봇
<img width="218" alt="챗봇1" src="https://user-images.githubusercontent.com/112562015/207406658-e0cc0447-020b-4f36-a485-43b59c347560.png">
- 회원은 웹사이트 하단의 버튼 클릭으로 챗봇을 실행할 수 있습니다.<br>
- 챗봇(관리자)은 회원에게 서비스 번호를 메시지로 보여줍니다.<br><br><br>
<img width="201" alt="챗봇2" src="https://user-images.githubusercontent.com/112562015/207406665-f57a8bcb-cc04-4c38-ae42-fdb702a5cb9e.png">
- 회원은 번호를 입력해 원하는 서비스로 이동합니다.<br><br><br>

