# 쇼핑몰 프로젝트
### SpringBoot와 JPA를 이용한 쇼핑몰입니다.
### 로그인/로그아웃, 상품등록, 상품관리, 장바구니, 주문하기/주문취소, 구매이력 등 쇼핑몰에 필요한 핵심 기능 구현

## 사용기술
+ SpringBoot 2.5.9, Thymeleaf, JPA, MySQL5.8.9, SpringSecurity
+ Language : Java11
+ Build Tool : Maven
+ IDE : IntelliJ

## 메인화면
![메인화면](https://user-images.githubusercontent.com/73814691/153765632-58558e83-2145-46c0-a5fb-c499652470b2.png)
+ 판매중이 상품들을 한 눈에 볼 수 있습니다.

## 상품등록
![상품등록](https://user-images.githubusercontent.com/73814691/153765571-e974cee5-9d21-44e9-851d-cdd1edcc1cf3.gif)
+ 관리자가 상품을 등록할 수 있습니다. 
+ 상품명, 판매중/품절 상태, 가격, 재고, 상세내용을 입력할 수 있습니다.
+ 상품 이미지를 업로드하고 저장합니다.

## 상품관리
![상품관리](https://user-images.githubusercontent.com/73814691/153765600-689378b1-5be8-436a-b329-b7819bef99bb.gif)
+ 등록한 상품정보를 조회 및 수정할 수 있습니다. 

# 장바구니
![장바구니](https://user-images.githubusercontent.com/73814691/153765610-d00aa130-e67d-4267-a1ed-6b345e5c0181.gif)
+ 쇼핑몰 회원은 원하는 상품을 선택해 장바구니에 넣을 수 있습니다.  

# 주문취소
![주문취소](https://user-images.githubusercontent.com/73814691/153765622-b29ff0e6-b0d8-4aac-8543-c771f3f40996.gif)
+ 상품주문을 취소할 수 있습니다. 

## ERD
![entityManagerFactory(EntityManagerFactoryBuilder)](https://user-images.githubusercontent.com/73814691/153052127-b1968ead-7ea1-4e6e-9462-5d31c3a0f434.png)

