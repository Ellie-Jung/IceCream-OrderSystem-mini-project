# IceCream-OrderSystem-mini-project
> OOP Base Cmd Mini Project
------------------------------------------------------------


# < 나자바의 아이스크림 가게 >
* 첫번째 미니 프로젝트
* 데이터 베이스 연동 자바 프로젝트
---------------------------------------------------------------
### 1. 주제 
  회원제 아이스크림 주문 시스템
  

[나자바아이스크림가게_.pptx](https://github.com/Ellie-Jung/IceCream-OrderSystem-mini-project/files/6725017/_.pptx)


### 2. 설계
 ![UseCaseDiagram](https://user-images.githubusercontent.com/81676847/123565236-2b670d80-d7f7-11eb-9bdf-91fdae427666.png)
![설계ERD](https://user-images.githubusercontent.com/81676847/123611953-144b0e80-d83d-11eb-8fc2-3ce10e8c68de.png)



### 3. 기능

  * 전체메뉴 
  * 회원
       * 로그인
       * 회원 가입
       * 아이디, 비밀번호 찾기
       * 내 정보 보기
       * 내 정보 수정
       * 로그 아웃
  * 상품
      * 상품 목록 추가하기
      * 상품 목록 수정하기
      * 상품 재고 추가하기
  * 주문 
      * 주문하기
      * 결제하기
      * 영수증 출력
  * 관리자
      * 모든 회원 보기
      * 특정 회원 휴면회원처리
      * 총 매출 보기
      * 월별 매출 보기
      * 일별 매출 보기
  

### 4. 구현방법
   * DataBase : Oracle SQL
   * Language : JAVA
 ## 4-1 DB 테이블 구성
  
**Member Table ( 회원 테이블)**

 ![image](https://user-images.githubusercontent.com/81676847/123613404-5aed3880-d83e-11eb-9a96-ffd3e1e36698.png)
 
 
 **Product Table (상품 테이블)**
 
 ![상품](https://user-images.githubusercontent.com/81676847/123613694-9daf1080-d83e-11eb-8577-8b90915db173.png)
 
 **Order Table (주문 테이블)**
 
 ![주문](https://user-images.githubusercontent.com/81676847/123613784-b15a7700-d83e-11eb-821d-8cd871320ed5.png)



 ## 4-2 자바 패키지 구성
 **주문**
 **상품**
 **회원**
 **관리자**
 **구동패키지**
