# Portfolio

포기하지 않는 개발자 김건영입니다.

## Contact
- 이메일: kky8809@gmail.com
- 블로그: https://godsu-develop.tistory.com
- 깃헙: https://github.com/Geon0

## 기술 스택

프로젝트에서 사용한 기술 스택입니다. 
숙련된 기술은 **굵게** 강조했습니다.

- 언어
  - Java
  - Php
  - **JavaScript**
- 프레임워크 / 툴킷
  - React
  - **React Native**
  - Spring
  - Laravel
- 퍼블릭 클라우드
  - **AWS**
  - **RDS**
  
## 프로젝트 참여 경력

- [POPPOP (2022~2023)](https://play.google.com/store/apps/details?id=com.poppop&hl=ko)
- [METAVERSERO (2022~2022)](https://metaversero.io/)
- [MARKET (2021)](https://github.com/Geon0/MARKET)
- [ETC. (2019~)](https://github.com/Geon0)

## [POPPOP](https://play.google.com/store/apps/details?id=com.poppop&hl=ko) (2022~)

`#javascript` `#react-native` `#aws` `#php` `#Laravel` `#AR` `#Mysql`

### 프로젝트 내용
POPPOP은 사용자의 위치정보를 통해 AR컨텐츠를 사용하여 콘텐츠를 생성하여 다른 사용자들과 커뮤니케이션 하는 어플리케이션입니다.

### 자세히

POPPOP은 프론트엔드 React Native 와 백엔드 Laravel을 사용한 Api서버 RDS를 사용하여 DB를 구성했습니다.

1. 사용자의 스마트폰에서 위치정보를 가져와 Api server로 위치 정보를 전달합니다.
2. 서버는 전달받은 위치정보를 기반으로 DB에서 직경 3km이내의 위치를 반환해줍니다.
3. 해당 위치에 등록되어있는 AR컨텐츠들을 불러온 뒤 선택합니다.
4. wikitude라는 AR 라이브러리를 사용하여 해당 content를 사용하여 사진을 촬영하여 업로드합니다.
5. AWS Elastic Load Balancing 사용하여 HTTPS SSL 인증서 적용

### 역할
- 백엔드설계
- MainPageScreen 
- 위치기반 서비스

### 느낀점

위치기반 서비스는 DB Query를 사용하여 구현했습니다. 
위치 기반 AR을 사용하기 위해서 wikitude 라이브러리를 사용하였습니다.
해당 라이브러리를 React native에 적용시켰습니다.

### 사용해보기

apple app store 에서 pop pop ar 검색 후 다운로드
google play store 에서 poppop 검색 후 다운로드

## [METAVERSERO](https://metaversero.io) (2022~)

`#html` `#css` `#javascript` `#php` `#AR` `#Mysql`

### 프로젝트 내용
solidity를 사용하여 erc-1155 거래를 지원하는 NFT 거래소

### 자세히

METAVERSERO는 프론트엔드 html css javascript 와 백엔드 php 스마트 컨트랙트 solidity RDS를 사용하여 DB를 구성했습니다.

1. NFT를 생성하는 백오피스에 비중을 두었습니다.
2. 이더리움 메인넷에 pending

### 역할
- 백오피스 설계 제작

### 느낀점

solidity를 사용하여 이더리움 메인넷과 연결함

### 사용해보기

https://metaversero.io

## [MARKET](https://github.com/Geon0/MARKET) (2021)

`#html` `#css` `#javascript` `#jsp` `#java` `#oracle` `#Jquery`

### 프로젝트 내용
자체 솔루션을 사용하여 경매 시스템 구현

### 자세히

- 배치 스케쥴을 사용하여 정해진 시간 도달시 종료 되는 기능 구현
- 경매 시스템을 참고하여 입찰하기 기능 구현
- 입찰 기능 구현시 exception 처리 구현
- 버튼을 클릭하여 입찰 가격 조정 기능 구현
- 입찰자 발생시 전 입찰자에게 알림 기능 구현

### 역할
- 설계 및 

### 느낀점

Exception 처리에 많은 시간을 할애함
