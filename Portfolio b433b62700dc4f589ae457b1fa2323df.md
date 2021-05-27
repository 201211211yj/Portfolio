# Portfolio

- 개인 포트폴리오를 작성하였습니다. 중요한 내용에는 Bold 처리를 하였습니다.

---

# **Skills.**

- 언어 : **Java**, Java Script, C++
- Framework : **Spring Boot, Spring Webflux**, Spring, Android, vue.js
- ETC : Linux, OpenCV,

---

# **Careers.**

**2012.03 ~ 2018.02 / 상명대학교 컴퓨터과학전공 졸업**

**2018.01 ~ / 미라콤아이앤씨 재직 (삼성화재 업무포탈 운영)**

[Career Project.](https://www.notion.so/f09f469a32124138b05e76084f9f6b40)

---

# **PR.**

**[업무 경험]**
저는 현재 보험사 업무포탈을 운영하고 있습니다. 일별로 접속자 수만 10만 명이 넘는 대용량 서비스인 포탈을 운영하며 Spring, DB2, Linux 등 많은 기술 스택을 쌓았습니다. 단순 운영에 그치지 않고 여러 프로젝트에 참여했습니다.
가장 컸던 프로젝트는 vue.js기반, nexacro기반의 포탈을 신규로 개발하는 것이었으며, 제 담당은 포탈의 사용자 권한연계, 메뉴 구성, 홈 화면 기능 등의 Back-end을 개발하는 것이었습니다. 단순 운영만 할 때는 몰랐으나 Framwork팀과 협력하며 진행하여 웹 서비스의 전체적인 구조를 파악할 수 있었습니다.
그 외에도 설계사 휴대폰 로그인 기능구현, 임직원 순간검색 솔루션 도입 등 지속적으로 사용자 편의 기능을 개발하여 고객 만족을 도모하였고, 설계사의 포탈 VOC를 분석하고 프로그램을 개선하여 연간 VOC를 30% 줄여 저희 파트의 주요 연간과제로 등극하기도 했습니다.

**[학습 능력]**
현 회사에 입사한 후 보험사의 웹 기반의 업무포탈을 운영하게 되었습니다. 비록 처음 개발해보는 분야였지만 기초적인 Java부터 기술을 새로 쌓으며 실력을 키웠습니다. 또한, 개인 토이프로젝트를 진행하며 Spring Boot, Spring JPA, Spring Cloud 등 신규 웹 기술 스택도 쌓아가고 있습니다.
회사에서 알고리즘 능력을 인정받아 SW Professional 등급을 취득하였고, 사내 알고리즘 강의를 진행하고 있습니다. 이러한 경험으로 학습 능력을 증명했을 뿐 아니라 강의를 통해 지식공유의 능력도 증명할 수 있습니다.

**[문제 해결 능력]**
모니터링 중 서버가 Hang이 걸릴 때가 있었습니다. SSO에서 임계치를 놓고 커넥션을 끊는 방법을 사용했으나, 근본적인 해결책이 되지는 않았습니다. 이 문제를 해결하기 위해 인프라팀에 협력요청을 하였고 L4의 로드밸런싱 방식이 Least Connection인 것을 알게되었습니다. 응답이 느릴 경우 커넥션이 적다고 판단하여 계속해서 느린 서버에만 커넥션을 보낸 것이었습니다. 이를 인지하고 Response Time방식으로 변경하여 응답이 느린 곳에는 커넥션을 보내지 않게 함으로써 문제를 해결했습니다.

---

# Major Projects**.**

## StackStock (2020.09~)

**Spring Boot Webflux** 기반의 대용량 비동기 데이터 처리를 통한 주식 예측 프로그램을 개발하고자 하였습니다. **Webflux와 기존의 동기적 MVC와의 성능 비교 및 장/단점 학습**이 주 목적인 프로젝트입니다.

**Git Repository.** 

- StackStock Crawler ([https://github.com/201211211yj/StackStockCrawler](https://github.com/201211211yj/StackStockCrawler))
    - WebClient를 통한 비동기 주식 크롤러입니다.
    - 축적된 데이터는 MongoDB에 쌓이게 되어있습니다.
- StackStock Rest API ([https://github.com/201211211yj/StackStockRouter](https://github.com/201211211yj/StackStockRouter))
    - WebFluxConfigurer를 통해 축적된 데이터를 처리할 수 있는 Rest API를 구현하였습니다.

**Tech Skills.**

- Back-End
    - **Java**
    - **Spring Boot Webflux**

## FaceBook Cloning (2021.04~2021.05)

**Spring Boot의 전반적인 기술**을 학습하기 위해서 개발을 진행한 프로젝트입니다.

![Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled.png](Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled.png)

**Tech Skills.**

- Front-End
    - React
- Back-End
    - **Java**
    - **Spring Boot + Jdbc : REST API 기반 Back-end 프로그램**
    - **Spring Security : JWT Authentication (Authentication 커스터마이징)**
    - **Kafka**
- API 문서 (Repository가 비공개 상태여서 부득이하게 해당 문서만 부분적으로 공개합니다.)

    ![Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%201.png](Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%201.png)

# Etc Projects**.**

## 자율주행 모듈 (2017.06 ~ 2017.09 完)

IOT Innovation Challange 본선에서 쓰인 프로그램으로 Artik710을 활용한 자율주행 모듈입니다. 

차선 인식을 위해 OpenCV를 활용하였으며 **Canny, Houghlines 등의 알고리즘을 조합**하여 사용하였습니다. 차선 인식률은 약 70%로 대부분의 트랙에 완주가 가능했습니다.

![Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%202.png](Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%202.png)

**Git Repository.** ([https://github.com/201211211yj/Artik710AutoCar](https://github.com/201211211yj/Artik710AutoCar))

**Tech Skills.**

- **자율 주행 기능 (담당 업무)**
    - **Linux**
    - **C++**
    - **OpenCV**
- 수동 주행 기능
    - Android
    - Java

## 어린이집 어플리케이션 (2016.07 ~ 2016.08 完)

학부시절 안드로이드 개발 학습용으로 개발한 어플리케이션입니다. 

서울시 공공데이터를 기반으로 어린이집 위치, 정보 조회, 식단 등록 등 간단한 기능을 개발하였습니다. 어플리케이션의 동작은 정상적으로 이루어지나, 소스코드의 구조화는 미흡하게 완성되었습니다.

![Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%203.png](Portfolio%20b433b62700dc4f589ae457b1fa2323df/Untitled%203.png)

**Git Repository.** ([https://github.com/201211211yj/2016SeoulApp](https://github.com/201211211yj/2016SeoulApp))

**Tech Skills.**

- **기본 기능**
    - **Java**
    - **Android**
    - **MySQL**

---