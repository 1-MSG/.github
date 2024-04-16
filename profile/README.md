# SSG 클론코딩 - 쇼핑몰 사이트와 관리자 사이트(README.md)

## 🗓️ 프로젝트 일정

- 일정: 2024년 2월 23일 - 2023년 4월 17일 (6주)

## 🚩기획 배경
현대 사회에서 온라인 쇼핑몰의 이용률은 급격히 증가하고 있습니다. 특히, SSG 쇼핑몰과 같은 대형 플랫폼은 다양한 상품과 편리한 이용 방식으로 소비자들에게 큰 인기를 얻고 있습니다. 그러나 이러한 대형 쇼핑몰의 시스템을 이해하고, 실제로 어떻게 운영되는지에 대한 정보는 쉽게 접근하기 어렵습니다. 이에, 저희 팀은 **실제 쇼핑몰의 운영 방식과 비즈니스 모델을 이해**하고자 SSG 쇼핑몰 사이트의 클론 코딩 프로젝트를 기획하게 되었습니다. 추가적으로, 단순히 사이트를 모방하는 것을 넘어, **실제 운영에 필수적인 데이터 모니터링 및 관리 기능**을 포함시켜, 실무적 경험을 더욱 풍부하게 하고자 하였습니다.

## 👩‍👧‍👦프로젝트 소개 및 목표

### "SSG 클론 코딩과 실시간 데이터 관리 플랫폼"

SSG 쇼핑몰 사이트의 **주요 기능과 인터페이스를 재현**한 클론 코딩 작업과 함께, 상품 데이터, 총 매출액, 판매 수량 등 **중요 비즈니스 지표를 실시간으로 모니터링하고 관리**할 수 있는 관리자(ADMIN) 사이트 개발을 목표로 합니다. 사용자는 클론 코딩된 쇼핑몰을 통해 실제 쇼핑몰과 유사한 쇼핑 경험을 할 수 있으며, 개발된 관리자 사이트를 통해 고객 관리, 매출 관리, 재고 관리 등의 다양한 관리 작업을 수행할 수 있습니다.

특히, 저희 팀은 사용자 경험을 최적화하기 위해 프론트엔드와 백엔드 모두 개발 과정에서 성능 최적화에 많은 노력을 기울였습니다. 로딩 시간 단축, 서버 응답 속도 향상, 그리고 효율적인 데이터 처리 방식의 적용을 통해, 사용자는 더욱 빠르고 부드러운 상호작용을 경험할 수 있습니다. 단순히 쇼핑몰 사이트의 구축 뿐만 아니라, **실시간 데이터 관리와 성능 최적화**라는 두 가지 핵심 요소를 성공적으로 통합하여 실제 쇼핑몰 운영과 유사한 환경에서의 개발 역량을 강화하고자 하였습니다.

## 🎇서비스 화면 및 기능소개

- [쇼핑몰 사이트 바로가기](https://ssgcom-app.vercel.app/)
- [관리자 사이트 바로가기](https://admin.sssg.shop/)
- 아래 테스트용 계정을 사용해 쇼핑몰의 모든 기능을 사용해볼 수 있습니다.
  - ID : welcome / thankyou
  - PW : 1234

- 소셜 로그인, 이메일 인증
- 상품 검색
- 상품 로딩 무한 스크롤
- 상품 찜, 장바구니 담기
- Admin : 상품 판매량/유저 집계

### 시연 영상

### 🏗️아키텍쳐

![인프라 아키텍쳐](https://github.com/1-MSG/backend/assets/81681883/19e22a99-72c6-4ff5-a66d-ca60926915b7)

<br>

### 🧭ERD

![MSG-ERD](https://github.com/1-MSG/backend/assets/81681883/e65a5b2d-7a61-4bec-94d4-bc35265710d8)
<br>
### 🍀 기술 스택

- **Backend**

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/Spring Data JPA-F05032?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/QueryDSL-81717?style=for-the-badge&logo=QueryDSL&logoColor=white"> 

- **Frontend**

<img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">  <img src="https://img.shields.io/badge/ReactQuery-61DAFB?style=for-the-badge&logo=ReactQuery&logoColor=white">  <img src="https://img.shields.io/badge/NextAuth-339933?style=for-the-badge&logo=NextAuth&logoColor=white"> <img src="https://img.shields.io/badge/vercel-06B6D4?style=for-the-badge&logo=vercel&logoColor=white"> <img src="https://img.shields.io/badge/swr-007ACC?style=for-the-badge&logo=swr&logoColor=white"> <img src="https://img.shields.io/badge/chart JS-007ACC?style=for-the-badge&logo=chart JS&logoColor=white">

- **DB**
  
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/MongoDB-3178C6?style=for-the-badge&logo=MongoDB&logoColor=white">

- **Infra**

<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">   <img src="https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-6DB33F?style=for-the-badge&logo=Nginx&logoColor=white">

- **Docs**

<img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white">

<br>

## **협업 관리**
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
|tjwn1408@naver.com  |tjwn1408@naver.com  |tjwn1408@naver.com  |
| [@KangBaekGwa](https://github.com/KangBaekGwa)| [@I-HYEON](https://github.com/I-HYEON) | [@khanturtle](https://github.com/khanturtle)  |



### 📚프로젝트 후기
### 강성욱
### 서이현
### 조준호
### 조윤찬
### 최형문
### 홍준표

## 📖Github Wiki
- [Github Wiki](https://github.com/1-MSG/backend/wiki)
