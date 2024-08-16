## 목차

1. [**프로젝트 소개**](#1)
2. [**기술 스택**](#2)
3. [**주요 기능**](#3)
4. [**아키텍처**](#4)
5. [**팀 소개**](#5)
6. [**폴더 구조**](#6)

<div id="1"></div>

## 📌프로젝트 소개
<img width="1280" alt="제목 없음" src="https://github.com/user-attachments/assets/3d7c34d9-7714-47f8-9262-7f3743d7073b">

<!-- <img width="1280" alt="기획배경" src="https://github.com/user-attachments/assets/19adf54e-e018-4eb3-a3a7-774809b534ad">
<img width="1280" alt="문제점" src="https://github.com/user-attachments/assets/35a98a0d-f61a-4726-8af1-d506e27a3aff">
<img width="1280" alt="그래서" src="https://github.com/user-attachments/assets/3c3f85aa-19c4-440f-a05d-d43e761b9710"> -->

- **소개**

  - 다양한 플랫폼의 신선한 웹툰을 한 눈에! **WebtoonSalad**<br/>

- **프로젝트 기간**

  - ```2024-07-02 ~ 2024-07-19``` <br/>


- **발표자료 및 영상**
  - [**PPT 바로가기 Click !**](https://drive.google.com/file/d/1MRQRrBvDkOaiY8XIKcfj3ZbXTnZDG8U0/view?usp=sharing) 👈

<br/>

<div id="2"></div>

## 📌기술 스택

### Stack

<div style="display: flex;">
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
</div>

### Collaboration

<div style="display: flex;">
  <img src="https://img.shields.io/badge/figma-%23F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" />
</div>

<br/>
<!--
- Spring Tool Suite 3.9.11 (STS 3)
- Java 8(1.8)
- Spring Framework 5.3.20.
- tomcat 9.0.37
- Maven 3.6.1 (EMBEDDED in STS 3)
- Oracle 21c Version 21.3.0.0.0
-->

<br/>

<div id="3"></div>

## 📌 주요 기능

<div id="6"></div>

## 📁 폴더 구조

<details>
<summary>폴더 구조 보기</summary>
  
```
C:.
│  .classpath
│  .gitignore
│  .project
│  pom.xml
│  
├─.settings
│      .jsdtscope
│      org.eclipse.jdt.core.prefs
│      org.eclipse.wst.common.component
│      org.eclipse.wst.common.project.facet.core.xml
│      org.eclipse.wst.jsdt.ui.superType.container
│      org.eclipse.wst.jsdt.ui.superType.name
│      org.eclipse.wst.validation.prefs
│      
├─src
│  ├─main
│  │  ├─java
│  │  │  └─com
│  │  │      └─webtoonsalad
│  │  │          ├─controller
│  │  │          │      CommentController.java
│  │  │          │      CommonController.java
│  │  │          │      JJimController.java
│  │  │          │      LikeCommentController.java
│  │  │          │      MyPageController.java
│  │  │          │      ReportController.java
│  │  │          │      SampleController.java
│  │  │          │      SignupController.java
│  │  │          │      UserController.java
│  │  │          │      WagleController.java
│  │  │          │      WebtoonController.java
│  │  │          │      
│  │  │          ├─dto
│  │  │          │      AuthDTO.java
│  │  │          │      CommentDTO.java
│  │  │          │      JJimDTO.java
│  │  │          │      LikeCommentDTO.java
│  │  │          │      LikeReplyDTO.java
│  │  │          │      LikeWagleDTO.java
│  │  │          │      PageDTO.java
│  │  │          │      ReplyCreateDTO.java
│  │  │          │      ReplyCriteria.java
│  │  │          │      ReplyDTO.java
│  │  │          │      SignupDTO.java
│  │  │          │      UserDTO.java
│  │  │          │      WagleCreateDTO.java
│  │  │          │      WagleCriteria.java
│  │  │          │      WagleDetailDTO.java
│  │  │          │      WagleListDTO.java
│  │  │          │      WagleUpdateDTO.java
│  │  │          │      WebtoonDTO.java
│  │  │          │      
│  │  │          ├─integration
│  │  │          │      WebtoonApi.java
│  │  │          │      
│  │  │          ├─mapper
│  │  │          │      CommentMapper.java
│  │  │          │      JJimMapper.java
│  │  │          │      LikeCommentMapper.java
│  │  │          │      LikeReplyMapper.java
│  │  │          │      LikeWagleMapper.java
│  │  │          │      ReplyMapper.java
│  │  │          │      ReportMapper.java
│  │  │          │      SignupMapper.java
│  │  │          │      UserMapper.java
│  │  │          │      WagleMapper.java
│  │  │          │      WebtoonMapper.java
│  │  │          │      
│  │  │          ├─security
│  │  │          │  │  CustomAccessDeniedHandler.java
│  │  │          │  │  CustomLoginSuccessHandler.java
│  │  │          │  │  CustomUserDetailsService.java
│  │  │          │  │  
│  │  │          │  └─domain
│  │  │          │          CustomUser.java
│  │  │          │          
│  │  │          └─service
│  │  │                  CommentService.java
│  │  │                  CommentServiceImpl.java
│  │  │                  JJimService.java
│  │  │                  JJimServiceImpl.java
│  │  │                  LikeCommentService.java
│  │  │                  LikeCommentServiceImpl.java
│  │  │                  LikeReplyService.java
│  │  │                  LikeReplyServiceImpl.java
│  │  │                  LikeWagleService.java
│  │  │                  LikeWagleServiceImpl.java
│  │  │                  ReplyService.java
│  │  │                  ReplyServiceImpl.java
│  │  │                  ReportService.java
│  │  │                  ReportServiceImpl.java
│  │  │                  SignupService.java
│  │  │                  SignupServiceImpl.java
│  │  │                  UserService.java
│  │  │                  UserServiceImpl.java
│  │  │                  WagleService.java
│  │  │                  WagleServiceImpl.java
│  │  │                  WebtoonApiService.java
│  │  │                  WebtoonService.java
│  │  │                  WebtoonServiceImpl.java
│  │  │                  
│  │  ├─resources
│  │  │  │  log4j.xml
│  │  │  │  log4jdbc.log4j2.properties
│  │  │  │  
│  │  │  └─com
│  │  │      └─webtoonsalad
│  │  │          └─mapper
│  │  │                  CommentMapper.xml
│  │  │                  JJimMapper.xml
│  │  │                  LikeCommentMapper.xml
│  │  │                  LikeReplyMapper.xml
│  │  │                  LikeWagleMapper.xml
│  │  │                  ReplyMapper.xml
│  │  │                  ReportMapper.xml
│  │  │                  SignupMapper.xml
│  │  │                  UserMapper.xml
│  │  │                  WagleMapper.xml
│  │  │                  WebtoonMapper.xml
│  │  │                  
│  │  └─webapp
│  │      ├─META-INF
│  │      │  │  MANIFEST.MF
│  │      │  │  
│  │      │  └─maven
│  │      │      └─com.webtoonsalad
│  │      │          └─controller
│  │      │                  pom.properties
│  │      │                  pom.xml
│  │      │                  
│  │      ├─resources
│  │      │  └─images
│  │      │          github.png
│  │      │          hire_me.jpg
│  │      │          icon_logo1.png
│  │      │          icon_logo2.png
│  │      │          logo.png
│  │      │          text_logo.png
│  │      │          top_button.png
│  │      │          
│  │      └─WEB-INF
│  │          │  web.xml
│  │          │  
│  │          ├─resources
│  │          │  ├─css
│  │          │  │  │  aside.css
│  │          │  │  │  customLogin.css
│  │          │  │  │  footer.css
│  │          │  │  │  header.css
│  │          │  │  │  jjim.css
│  │          │  │  │  rightaside.css
│  │          │  │  │  signup.css
│  │          │  │  │  
│  │          │  │  ├─mypage
│  │          │  │  │      chart.css
│  │          │  │  │      mypage.css
│  │          │  │  │      
│  │          │  │  ├─wagle
│  │          │  │  │      wagleDetail.css
│  │          │  │  │      wagleList.css
│  │          │  │  │      wagleModify.css
│  │          │  │  │      wagleRegister.css
│  │          │  │  │      
│  │          │  │  └─webtoon
│  │          │  │          detail.css
│  │          │  │          home.css
│  │          │  │          
│  │          │  └─img
│  │          │          like.png
│  │          │          
│  │          ├─spring
│  │          │  │  root-context.xml
│  │          │  │  security-context.xml
│  │          │  │  
│  │          │  └─appServlet
│  │          │          servlet-context.xml
│  │          │          
│  │          └─views
│  │              │  accessError.jsp
│  │              │  customLogin.jsp
│  │              │  customLogout.jsp
│  │              │  footer.jsp
│  │              │  header.jsp
│  │              │  leftaside.jsp
│  │              │  modal.jsp
│  │              │  rightaside.jsp
│  │              │  signup.jsp
│  │              │  
│  │              ├─jjim
│  │              │      jjim.jsp
│  │              │      list.jsp
│  │              │      
│  │              ├─mypage
│  │              │      mypage.jsp
│  │              │      myreport.jsp
│  │              │      userinfo.jsp
│  │              │      
│  │              ├─wagle
│  │              │      detail.jsp
│  │              │      list.jsp
│  │              │      modify.jsp
│  │              │      register.jsp
│  │              │      
│  │              └─webtoon
│  │                      detail.jsp
│  │                      home.jsp
│  │                      
│  └─test
│      ├─java
│      │  └─com
│      │      ├─webtoon
│      │      │  └─persistence
│      │      │          DataSourceTest.java
│      │      │          DataSourceTests2.java
│      │      │          JDBCTests.java
│      │      │          
│      │      └─webtoonsalad
│      │          ├─controller
│      │          │      UserControllerTests.java
│      │          │      
│      │          ├─mapper
│      │          │      CommentMapperTests.java
│      │          │      JJimMapperTest.java
│      │          │      LikeCommentMapperTests.java
│      │          │      LikeWagleTests.java
│      │          │      MemberMapperTest.java
│      │          │      ReplyCreateSelectKeyTests.java
│      │          │      ReplyDeleteTests.java
│      │          │      ReplyGetListWithPagingTests.java
│      │          │      ReplySelectTests.java
│      │          │      SignupMapperTests.java
│      │          │      WagleCreateSelectKeyTests.java
│      │          │      WagleCreateTests.java
│      │          │      WagleDeleteTests.java
│      │          │      WagleDetailTests.java
│      │          │      WagleSelectTests.java
│      │          │      WagleSelectWithPagingTests.java
│      │          │      WagleUpdateTests.java
│      │          │      WebtoonDayListTests.java
│      │          │      WebtoonDetailTests.java
│      │          │      WebtoonListTests.java
│      │          │      
│      │          ├─security
│      │          │      MemberTests.java
│      │          │      MemberTests2.java
│      │          │      
│      │          └─service
│      │                  JJimServiceTest.java
│      │                  ReplyGetListTests.java
│      │                  ReplyGetListWithPagingTests.java
│      │                  ReplyRegisterTests.java
│      │                  ReplyRemoveTests.java
│      │                  ReplyServiceTests.java
│      │                  WagleDeleteTests.java
│      │                  WagleGetDetailWagleTests.java
│      │                  WagleGetListTests.java
│      │                  WagleGetListWithPagingTests.java
│      │                  WagleRegisterTests.java
│      │                  WagleServiceTests.java
│      │                  WagleUpdateTests.java
│      │                  WebtoonApiServiceTests.java
│      │                  
│      └─resources
│              log4j.xml
│              
└─target
    ├─classes
    │  │  log4j.xml
    │  │  log4jdbc.log4j2.properties
    │  │  
    │  └─com
    │      └─webtoonsalad
    │          ├─controller
    │          │      CommentController.class
    │          │      CommonController.class
    │          │      JJimController.class
    │          │      LikeCommentController.class
    │          │      MyPageController.class
    │          │      ReportController.class
    │          │      SampleController.class
    │          │      SignupController.class
    │          │      UserController.class
    │          │      WagleController.class
    │          │      WebtoonController.class
    │          │      
    │          ├─dto
    │          │      AuthDTO.class
    │          │      CommentDTO.class
    │          │      JJimDTO.class
    │          │      LikeCommentDTO.class
    │          │      LikeReplyDTO.class
    │          │      LikeWagleDTO.class
    │          │      PageDTO.class
    │          │      ReplyCreateDTO.class
    │          │      ReplyCriteria.class
    │          │      ReplyDTO.class
    │          │      SignupDTO.class
    │          │      UserDTO.class
    │          │      WagleCreateDTO.class
    │          │      WagleCriteria.class
    │          │      WagleDetailDTO.class
    │          │      WagleListDTO.class
    │          │      WagleUpdateDTO.class
    │          │      WebtoonDTO.class
    │          │      
    │          ├─integration
    │          │      WebtoonApi.class
    │          │      
    │          ├─mapper
    │          │      CommentMapper.class
    │          │      CommentMapper.xml
    │          │      JJimMapper.class
    │          │      JJimMapper.xml
    │          │      LikeCommentMapper.class
    │          │      LikeCommentMapper.xml
    │          │      LikeReplyMapper.class
    │          │      LikeReplyMapper.xml
    │          │      LikeWagleMapper.class
    │          │      LikeWagleMapper.xml
    │          │      ReplyMapper.class
    │          │      ReplyMapper.xml
    │          │      ReportMapper.class
    │          │      ReportMapper.xml
    │          │      SignupMapper.class
    │          │      SignupMapper.xml
    │          │      UserMapper.class
    │          │      UserMapper.xml
    │          │      WagleMapper.class
    │          │      WagleMapper.xml
    │          │      WebtoonMapper.class
    │          │      WebtoonMapper.xml
    │          │      
    │          ├─security
    │          │  │  CustomAccessDeniedHandler.class
    │          │  │  CustomLoginSuccessHandler.class
    │          │  │  CustomUserDetailsService.class
    │          │  │  
    │          │  └─domain
    │          │          CustomUser.class
    │          │          
    │          └─service
    │                  CommentService.class
    │                  CommentServiceImpl.class
    │                  JJimService.class
    │                  JJimServiceImpl.class
    │                  LikeCommentService.class
    │                  LikeCommentServiceImpl.class
    │                  LikeReplyService.class
    │                  LikeReplyServiceImpl.class
    │                  LikeWagleService.class
    │                  LikeWagleServiceImpl.class
    │                  ReplyService.class
    │                  ReplyServiceImpl.class
    │                  ReportService.class
    │                  ReportServiceImpl.class
    │                  SignupService.class
    │                  SignupServiceImpl.class
    │                  UserService.class
    │                  UserServiceImpl.class
    │                  WagleService.class
    │                  WagleServiceImpl.class
    │                  WebtoonApiService.class
    │                  WebtoonService.class
    │                  WebtoonServiceImpl.class
    │                  
    ├─m2e-wtp
    │  └─web-resources
    │      └─META-INF
    │          │  MANIFEST.MF
    │          │  
    │          └─maven
    │              └─com.webtoonsalad
    │                  └─controller
    │                          pom.properties
    │                          pom.xml
    │                          
    └─test-classes
        │  log4j.xml
        │  
        └─com
            ├─webtoon
            │  └─persistence
            │          DataSourceTest.class
            │          DataSourceTests2.class
            │          JDBCTests.class
            │          
            └─webtoonsalad
                ├─controller
                │      UserControllerTests.class
                │      
                ├─mapper
                │      CommentMapperTests.class
                │      JJimMapperTest.class
                │      LikeCommentMapperTests.class
                │      LikeWagleTests.class
                │      MemberMapperTest.class
                │      ReplyCreateSelectKeyTests.class
                │      ReplyDeleteTests.class
                │      ReplyGetListWithPagingTests.class
                │      ReplySelectTests.class
                │      SignupMapperTests.class
                │      WagleCreateSelectKeyTests.class
                │      WagleCreateTests.class
                │      WagleDeleteTests.class
                │      WagleDetailTests.class
                │      WagleSelectTests.class
                │      WagleSelectWithPagingTests.class
                │      WagleUpdateTests.class
                │      WebtoonDayListTests.class
                │      WebtoonDetailTests.class
                │      WebtoonListTests.class
                │      
                ├─security
                │      MemberTests.class
                │      MemberTests2.class
                │      
                └─service
                        JJimServiceTest.class
                        ReplyGetListTests.class
                        ReplyGetListWithPagingTests.class
                        ReplyRegisterTests.class
                        ReplyRemoveTests.class
                        ReplyServiceTests.class
                        WagleDeleteTests.class
                        WagleGetDetailWagleTests.class
                        WagleGetListTests.class
                        WagleGetListWithPagingTests.class
                        WagleRegisterTests.class
                        WagleServiceTests.class
                        WagleUpdateTests.class
                        WebtoonApiServiceTests.class
                        
```

</details>

---

