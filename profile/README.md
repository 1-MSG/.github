# SSG 클론코딩 - 쇼핑몰 사이트와 관리자 사이트(README.md)

## 🗓️ 프로젝트 일정

- 일정: 2024년 2월 23일 - 2023년 4월 17일 (6주)

## 🚩기획 배경
온라인 쇼핑몰의 이용률이 급격히 증가하고 있습니다. 특히, SSG 쇼핑몰과 같은 대형 플랫폼은 다양한 상품과 편리한 이용 방식으로 소비자들에게 큰 인기를 얻고 있습니다.

그러나 이러한 대형 쇼핑몰의 시스템을 이해하고, 실제로 어떻게 운영되는지에 대한 정보는 쉽게 접근하기 어렵습니다. 이에, **실제 쇼핑몰의 운영 방식과 비즈니스 모델을 이해**하고자 SSG 쇼핑몰 사이트의 클론 코딩 프로젝트를 기획하게 되었습니다.

추가적으로, 단순히 사이트를 모방하는 것을 넘어, **실제 운영에 필수적인 데이터 모니터링 및 관리 기능**을 포함시켜, 실제 쇼핑몰 운영과 유사한 환경에서의 개발 역량을 강화하고자 하였습니다.

## 👩‍👧‍👦프로젝트 목표

### "SSG 클론 코딩과 실시간 데이터 관리 플랫폼"

SSG 쇼핑몰 사이트의 **주요 기능과 인터페이스를 재현**한 클론 코딩 작업과 함께, 상품 데이터, 총 매출액, 판매 수량 등 **중요 비즈니스 지표를 실시간으로 모니터링하고 관리**할 수 있는 관리자(ADMIN) 사이트 개발을 목표로 합니다.

특히, 저희 팀은 사용자 경험을 최적화하기 위해 프론트엔드와 백엔드 모두 개발 과정에서 성능 최적화에 많은 노력을 기울였습니다. 로딩 시간 단축, 서버 응답 속도 향상, 그리고 효율적인 데이터 처리 방식의 적용을 통해, 사용자는 **더욱 빠르고 부드러운 상호작용**을 경험할 수 있습니다.

## 🔎 서비스 개요

사용자는 클론 코딩된 쇼핑몰을 통해 실제 쇼핑몰과 유사한 쇼핑 경험을 할 수 있으며, 개발된 관리자 사이트를 통해 고객 관리, 매출 관리, 재고 관리 등의 다양한 관리 작업을 수행할 수 있습니다.

## 🎇서비스 화면 및 기능소개

- [쇼핑몰 사이트 바로가기](https://ssgcom-app.vercel.app/)
- [관리자 사이트 바로가기](https://admin.sssg.shop/)
- 아래 테스트용 계정을 사용해 쇼핑몰의 모든 기능을 사용해볼 수 있습니다.
  - ID : welcome / thankyou
  - PW : 1234

### 1. 회원관리 기능(회원가입/로그인)
![로그인gif](https://github.com/1-MSG/.github/assets/122415843/29cee163-130a-4f65-89f0-04e275b0f06f) | ![로그인gif](https://github.com/1-MSG/.github/assets/122415843/29cee163-130a-4f65-89f0-04e275b0f06f) |
--- | --- | 
간편/통합 회원가입| 통합 로그인 과정 |
### 2. 키워드로 상품 검색
![검색gif](https://github.com/1-MSG/.github/assets/122415843/60e0feba-1962-4953-961f-1fed34bf8547) | ![구매직전gif](https://github.com/1-MSG/.github/assets/122415843/34a0c755-3289-4448-8005-605d6e820256) |
--- | --- | 
상품 검색 및 조회 | 구매 직전 페이지 |
### 3. 상품 무한 스크롤 조회
![무한스크롤gif](https://github.com/1-MSG/.github/assets/122415843/901759e9-df96-4ef9-8141-286395b160a9) | ![카테고리별조회gif](https://github.com/1-MSG/.github/assets/122415843/96b9a7bd-31fa-43f7-96d9-f175680e854a) |
--- | --- | 
무한스크롤 통한 조회 | 카테고리별 조회 |
### 4. 상품 좋아요, 장바구니 담기
![좋아요gif](https://github.com/1-MSG/.github/assets/122415843/b0744ef1-8cf7-495d-b44f-633621beff74)| ![장바구니gif](https://github.com/1-MSG/.github/assets/122415843/92d616ff-bfb9-422c-9fa5-8e36c4b60215) |
--- | --- |
상품별 좋아요 | 옵션선택 후 장바구니 담기 |
### 5. 관리자 상품 판매량/사용자 관리
![어드민1](https://github.com/1-MSG/.github/assets/122415843/00e8e3f1-af43-4806-aa00-3401c6056405) | ![어드민2](https://github.com/1-MSG/.github/assets/122415843/5d45335f-407f-4c08-a4ad-71b7f8dbcbaf) |
--- | --- | 
전체 매출 관리/응답속도 탭| 상품 데이터 관리 탭|

## 🛠 기술 스택

## 📜산출물

### ✒아키텍처 구조도

<img src="https://github.com/1-MSG/backend/assets/81681883/19e22a99-72c6-4ff5-a66d-ca60926915b7" width="500">

### ✒ERD

![MSG-ERD](https://github.com/1-MSG/backend/assets/81681883/e65a5b2d-7a61-4bec-94d4-bc35265710d8)

### 폴더구조
Back
```
📦src
 ┣ 📂main
 ┃ ┣ 📂java
 ┃ ┃ ┗ 📂spharos
 ┃ ┃ ┃ ┗ 📂msg
 ┃ ┃ ┃ ┃ ┣ 📂domain
 ┃ ┃ ┃ ┃ ┃ ┣ 📂admin
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂controller
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂converter
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂entity
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂repository
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂service
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Impl
 ┃ ┃ ┃ ┃ ┃ ┣ 📂brand
 ┃ ┃ ┃ ┃ ┃ ┣ 📂bundle
 ┃ ┃ ┃ ┃ ┃ ┣ 📂cart
 ┃ ┃ ┃ ┃ ┃ ┣ 📂category
 ┃ ┃ ┃ ┃ ┃ ┣ 📂coupon
 ┃ ┃ ┃ ┃ ┃ ┣ 📂likes
 ┃ ┃ ┃ ┃ ┃ ┣ 📂options
 ┃ ┃ ┃ ┃ ┃ ┣ 📂orders
 ┃ ┃ ┃ ┃ ┃ ┣ 📂product
 ┃ ┃ ┃ ┃ ┃ ┣ 📂review
 ┃ ┃ ┃ ┃ ┃ ┣ 📂search
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂controller
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂entity
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂repository
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂impl
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂service
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂utils
 ┃ ┃ ┃ ┃ ┃ ┗ 📂users
 ┃ ┃ ┃ ┃ ┣ 📂global
 ┃ ┃ ┃ ┃ ┃ ┣ 📂api
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂code
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂status
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂example
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂exception
 ┃ ┃ ┃ ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┃ ┃ ┣ 📂converter
 ┃ ┃ ┃ ┃ ┃ ┣ 📂database
 ┃ ┃ ┃ ┃ ┃ ┣ 📂entity
 ┃ ┃ ┃ ┃ ┃ ┣ 📂redis
 ┃ ┃ ┃ ┃ ┃ ┗ 📂security
 ┃ ┃ ┃ ┃ ┗ 📜MsgApplication.java
 ┃ ┗ 📂resources
 ┗ 📂test

```
Front
```
📦components
 ┣ 📂banner
 ┣ 📂form
 ┣ 📂layout
 ┣ 📂MainCategory
 ┣ 📂pages
 ┃ ┣ 📂auth
 ┃ ┃ ┣ 📂signup
 ┃ ┃ ┗ 📂users
 ┃ ┣ 📂cart
 ┃ ┣ 📂category
 ┃ ┣ 📂catogory-list
 ┃ ┣ 📂join
 ┃ ┣ 📂like
 ┃ ┣ 📂login
 ┃ ┣ 📂main
 ┃ ┣ 📂nonuser
 ┃ ┣ 📂order
 ┃ ┃ ┣ 📂order-complete
 ┃ ┃ ┗ 📂product-order
 ┃ ┣ 📂product-detail
 ┃ ┣ 📂product-list
 ┃ ┃ ┣ 📂ranking
 ┃ ┃ ┣ 📂special-price
 ┃ ┣ 📂product-review
 ┃ ┣ 📂search
 ┃ ┗ 📂users
 ┃ ┃ ┗ 📂my-order
 ┗ 📂ui
```

### ✒깃허브 위키
[Github Wiki 바로가기](https://github.com/1-MSG/backend/wiki)

### ✒협업 관리

그라운드룰 | 노션 기반 진행상황 공유 |
--- | --- | 
![그라운드룰](https://github.com/1-MSG/backend/assets/122415843/b3010e34-dd6b-4c25-82ba-758b62a113f3)| ![노션_기반_진행상황_공유](https://github.com/1-MSG/backend/assets/122415843/8bc0838a-bc2e-41bc-95b0-fcc965302ac0) |

데일리 스크럼 및 회고 | Gitflow 전략 및 통일된 커밋 메시지 |
--- | --- | 
![데일리_스크럼_및_회고](https://github.com/1-MSG/backend/assets/122415843/5c3c2f6a-9ab8-4015-9768-e216cfffd9a4)| !![Gitflow_전략_및_통일된_커밋_메시지](https://github.com/1-MSG/backend/assets/122415843/6fc761ce-7ebd-47ba-8110-b6bd64dcd4cf) |

코드리뷰 | 트러블 슈팅 |
--- | --- |
![코드리뷰](https://github.com/1-MSG/.github/assets/122415843/dde2650b-ba16-40bc-ac82-95ffe0bf1e48) | ![트러블슈팅](https://github.com/1-MSG/.github/assets/122415843/cdee45e3-9f06-49ee-8c71-56791888bfbd) |


### 👥팀원 소개
|    <img src="https://avatars.githubusercontent.com/u/160799011?v=4" width="40" />    |   <img src="https://avatars.githubusercontent.com/u/122415843?v=4" width="40" />   |   <img src="https://avatars.githubusercontent.com/u/81681883?v=4" width="40" />    |
| :----: | :----: | :----: |
| 강성욱 | 서이현 | 조준호 |
| BackEnd| BackEnd| BackEnd|
|ksu9801@gmail.com  |tjwn1408@naver.com  |chojunho9803@gmail.com  |
| [@KangBaekGwa](https://github.com/KangBaekGwa)| [@I-HYEON](https://github.com/I-HYEON) | [@khanturtle](https://github.com/khanturtle)  |
소감 및 후기 | 소감 및 후기 | 소감 및 후기 |

|    <img src="https://avatars.githubusercontent.com/u/87313979?v=4" width="40" />    |   <img src="https://avatars.githubusercontent.com/u/67429918?v=4" width="40" />   |   <img src="https://avatars.githubusercontent.com/u/53307093?v=4" width="40" />    |
| :----: | :----: | :----: |
| 조윤찬 | 최형문 | 홍준표 |
| FontEnd| FrontEnd| BackEnd|
|whdbscks77@gmail.com  |munii1023@gmail.com |tjdvy17539@gmail.com  |
| [@YOON-CC](https://github.com/YOON-CC)| [@yunii23](https://github.com/yunii23) | [@howudong](https://github.com/howudong) |
소감 및 후기 | 소감 및 후기 | 소감 및 후기 |
