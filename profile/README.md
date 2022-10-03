<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url] -->
<!-- [![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Pull Requests][pr-shield]][pr-url]
[![MIT License][license-shield]][license-url] -->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Instagram-Clone-Coding">
    <img src="https://avatars.githubusercontent.com/u/90607105?s=200&v=4" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Instagram-Clone-Project</h3>

  <p align="center">
    인스타그램 클론코딩 프로젝트 소개입니다.
    <br />
    <a href="http://ec2-3-36-185-121.ap-northeast-2.compute.amazonaws.com/"><h3>👉배포 사이트 바로가기👈</h3></a>
    <a href="https://github.com/Instagram-Clone-Coding"><strong>1. Explore the Organization</strong></a><br>
    <a href="https://github.com/Instagram-Clone-Coding/React_instagram_clone"><strong>2. Explore Front-end Repository</strong></a><br>
    <a href="https://github.com/Instagram-Clone-Coding/Spring_instagram-clone"><strong>3. Explore Back-end Repository</strong></a><br>
    <a href="http://ec2-3-36-185-121.ap-northeast-2.compute.amazonaws.com:8080/swagger-ui.html"><strong>4. Explore API Documents</strong></a><br>    
    <a href="https://www.erdcloud.com/d/ufv5P5mkEhpe2iStd"><strong>5. Explore ERD</strong></a><br>    
    <br />
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
### Table of Contents
  <ol>
    <li><a href="#프로젝트-소개">프로젝트 소개</a></li>
    <li><a href="#프로젝트-목표">프로젝트 목표</a></li>
    <li><a href="#시연-영상">시연 영상</a></li>
    <li><a href="#ia">IA</a></li>
    <li><a href="#aws-public-cloud-architecture">AWS Public Cloud Architecture</a></li>
    <li><a href="#tech-stacks">Tech Stacks</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### 프로젝트 소개

**인스타그램 클론 코딩**은 `Spring Boot`와 `React`를 기반으로 이미지 기반 소셜 미디어 **인스타그램** 서비스를 하나하나 구현해가는 프로젝트입니다.

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


### 프로젝트 목표

- 친숙한 서비스인 Instagram을 **분석**해서 **구조**를 직접 **설계**합니다.
- 역할을 분담하여 서비스를 코드로 **구현**하고 **배포**해봅니다.
    - 구현하는 과정에서 Front-end와 Back-end가 **협업**하는 과정을 이해합니다.
        - RESTful API를 직접 설계하고 API를 통한 HTTP 통신을 겪으며 협업 능력을 기릅니다.
        - 자신이 맡은 부분을 남에게 설명할 수 있는 의사소통 능력을 기릅니다.
    - 단순히 구현 후 끝나는 것이 아닌 **코드 리뷰**와 **피드백**을 통해 함께 성장합니다.
    - 기존의 코드를 지속적으로 개선하기 위해 **리팩토링**을 진행합니다.
- **Spring Boot**와 **React**를 기반으로 다양한 기술 스택을 **학습**하고 적용합니다.

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### 시연 영상
<details>
  <summary><strong>로그인</strong></summary>
  
![로그인로그인활동로그아웃](https://user-images.githubusercontent.com/68049320/190650075-3ebe7287-33d6-4b40-b395-4ca964ecfc74.gif)
- 로그인
- 로그인 활동
- 로그아웃
</details>
<details>
  <summary><strong>게시물</strong></summary>
  
![게시물조회스크롤좋아요저장](https://user-images.githubusercontent.com/68049320/190650398-bfce3180-b1f6-47cb-87fe-ee7f184fcc5c.gif)
- 게시물 무한 스크롤 조회
- 게시물 좋아요
- 게시물 저장  

![게시물업로드](https://user-images.githubusercontent.com/68049320/190650750-ed2d046c-ae66-40c7-b13a-165806ddccb9.gif)
- 게시물 업로드
</details>
<details>
  <summary><strong>팔로우</strong></summary>
  
![팔로우언팔로우](https://user-images.githubusercontent.com/68049320/190650566-8221388d-6cab-4dc0-b23b-264fed3a38df.gif)
- 팔로우
- 언팔로우
</details>
<details>
  <summary><strong>DM</strong></summary>
  
  ![메세지보내기좋아요취소이미지](https://user-images.githubusercontent.com/68049320/190651667-5bd0b4d3-b348-47d8-ad91-68d1d87d5bf6.gif)
- 메시지 보내기/취소
- 메시지 좋아요/취소
- 이미지 보내기
- 채팅방 목록 조회
- 채팅방 조회
</details>

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### IA
![인스타IA](https://user-images.githubusercontent.com/68049320/190657661-eac81a9f-1716-46bb-849e-9c763cc31496.png)

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### AWS Public Cloud Architecture
![image](https://user-images.githubusercontent.com/68049320/193588720-04e11485-4d4c-4548-b747-2cfec3d264d1.png)

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Tech Stacks
<table>
	<tr><th rowspan="7">⚛Front-end</th><td>Language</td><td>TypeScript</td></tr>
	<tr><td>Library</td><td>React</td></tr>
	<tr><td>State Container</td><td>Redux</td></tr>
	<tr><td>Component</td><td>Styled-Components</td></tr>
	<tr><td>Asynchronous</td><td>Axios</td></tr>
	<tr><td>Messaging</td><td>SockJS, StompJS</td></tr>
	<tr><td>Open API</td><td>Naver Map API</td></tr>
	<tr><th rowspan="10">🌱Back-end</th><td>Language</td><td>Java 11</td></tr>
	<tr><td>Framework</td><td>Spring Boot 2.5.4</td></tr>
	<tr><td>ORM</td><td>Spring Data JPA, Querydsl</td></tr>
	<tr><td>SMTP</td><td>Gmail SMTP</td></tr>
	<tr><td>Authorization</td><td>Spring Security, JWT</td></tr>
	<tr><td>Messaging</td><td>WebSocket, STOMP</td></tr>
	<tr><td>API Documentation</td><td>Swagger</td></tr>
	<tr><td>Database</td><td>MariaDB, H2, Redis, GeoIP</td></tr>
	<tr><td>Test</td><td>JUnit5, Mockito</td></tr>
	<tr><td>Open API</td><td>Kakao Map API</td></tr>
	<tr><th rowspan="3">👨‍👩‍👦‍👦Collaboration</th><td>Api Test</td><td>Postman</td></tr>
	<tr><td>Communication</td><td>Notion, Google Meet</td></tr>
	<tr><td>Version Control</td><td>Github</td></tr>
	<tr><th>🛠AWS Public Cloud Service</th><td colspan="2">EC2, RDS, S3, ElastiCache, VPC, Internet gateway, NAT gateway, ELB, ALB, Route 53, Certificate Manager </td></tr>
</table>

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/seonpilKim">
        <img src="https://avatars.githubusercontent.com/u/68049320?v=4" width="110px;" alt=""/><br />
        <sub><b>김선필</b></sub></a><br />
        <sub><b>🍪Back-end</b></sub></a><br />
        <sub><b>✈Team Leader</b></sub></a><br />
        <a href="https://github.com/seonpilKim" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/bluetifulc">
        <img src="https://avatars.githubusercontent.com/u/58378676?v=4" width="110px;" alt=""/><br />
        <sub><b>최다훈</b></sub></a><br />
        <sub><b>🧀Back-end</b></sub></a><br />
	<sub><b></b></sub></a><br />
        <a href="https://github.com/bluetifulc" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/live-small">
        <img src="https://avatars.githubusercontent.com/u/70274947?v=4" width="110px;" alt=""/><br />
        <sub><b>한수화</b></sub></a><br />
        <sub><b>☕Front-end</b></sub></a><br />  
	<sub><b></b></sub></a><br />
        <a href="https://github.com/live-small" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/kimyoungyin">
        <img src="https://avatars.githubusercontent.com/u/78777345?v=4" width="110px;" alt=""/><br />
        <sub><b>김영인</b></sub></a><br />
        <sub><b>🍖Front-end</b></sub></a><br />    
	<sub><b></b></sub></a><br />
        <a href="https://github.com/kimyoungyin" title="Code">💻</a>
    </td>
  </tr>
</table>  

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/Instagram-Clone-Coding/Introduction.svg?style=for-the-badge
[contributors-url]: https://github.com/Instagram-Clone-Coding/Introduction/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Instagram-Clone-Coding/Spring_instagram-clone.svg?style=for-the-badge
[forks-url]: https://github.com/Instagram-Clone-Coding/Spring_instagram-clone/network/members
[stars-shield]: https://img.shields.io/github/stars/Instagram-Clone-Coding/Spring_instagram-clone.svg?style=for-the-badge
[stars-url]: https://github.com/Instagram-Clone-Coding/Spring_instagram-clone/stargazers
[issues-shield]: https://img.shields.io/github/issues/Instagram-Clone-Coding/Spring_instagram-clone.svg?style=for-the-badge
[issues-url]: https://github.com/Instagram-Clone-Coding/Spring_instagram-clone/issues
[license-shield]: https://img.shields.io/github/license/Instagram-Clone-Coding/Spring_instagram-clone?style=for-the-badge
[license-url]: https://github.com/Instagram-Clone-Coding/Spring_instagram-clone/blob/develop/LICENSE.txt
[pr-shield]: https://img.shields.io/github/issues-pr/Instagram-Clone-Coding/Spring_instagram-clone?style=for-the-badge
[pr-url]: https://github.com/Instagram-Clone-Coding/Spring_instagram-clone/pulls
[product-screenshot]: images/screenshot.png
