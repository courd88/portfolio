# **PORTFOLIO**

## **📗 목차**

<b>

- 📝 [개요](#-포트폴리오-개요)
- 🛠 [기술 및 도구](#-기술-및-도구)
- ✨ [업데이트](#-업데이트)
- 👨🏻‍💻 [기능 구현](#-기능-구현)
  - [게시글 사진 등록](#1-게시글-사진-등록)
  - [좋아요 기능](#2-좋아요-기능)
  - [페이징](#3-페이징-기능)
  - [반응형 웹](#4-반응형-웹)
  - [슬라이드 애니메이션](#5-슬라이드-애니메이션)
- ⏰ [반성](#-반성)

</b>

## **📝 포트폴리오 개요**

<img width="100%" alt="메인 페이지" src="https://github.com/courd88/portfolio/assets/121409878/c704147b-7ee1-43cc-9ea7-c6d0c6b2f74a" />
(https://github.com/courd88/portfolio/assets/121409878/c704147b-7ee1-43cc-9ea7-c6d0c6b2f74a)

> **프로젝트:** 외국인들의 한국관광 정보공유 사이트 [KADA]
>
> **기획 및 제작:** 김태균 외 5명
>
> **분류:** 개인 프로젝트
>
> **제작 기간:** 2023.04 ~ 2023.06
>
> **주요 기능:** 게시글 사진 등록 , 좋아요 기능 , 페이징 , 반응형 웹 , 슬라이드 애니메이션
>
> **사용 기술:** JAVA , spring , spring boot , JavaScript , React , MySQL
>
> **Frontent:** https://github.com/courd88/lastproject-front.git
>
> **Backend:** https://github.com/courd88/LastProject-Back.git
>
> **문의:** teagyun@nate.com

<br />

## **🛠 기술 및 도구**

![JAVA](https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white)
![JavaScript](https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=Javascript&logoColor=black)
![spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white)
![React](https://img.shields.io/badge/React-53C1DE?style=flat-square&logo=react&logoColor=white)
![MySQL](https://img.shields.io/badge/Mysql-4479A1?style=flat-square&logo=Mysql&logoColor=white)
![GitHub](https://img.shields.io/badge/Github-%23121011.svg?style=flat-square&logo=github&logoColor=white)




<br />

## **👨🏻‍💻 기능 구현**

### **1. 게시글 사진 등록**

<img width="100%" alt="라이트/다크모드" src="https://user-images.githubusercontent.com/51189962/136142455-dd9bbdf1-4676-408c-bdc2-009f133e92db.gif" />

- 기본 게시판 글쓰기에 사진을 넣을 수 있게 구현
- 사용자의 글수정에서도 사진을 변경 가능하도록 구현
- 목록에서 사진과 글을 보일수 있도록 구현

### **2. 좋아요 기능**

<img width="100%" alt="hashlink" src="https://user-images.githubusercontent.com/51189962/136143186-aeb70c36-8e21-40e7-b937-deea0e66ad18.gif" />

- 글 목록에서도 글 상세보기에서도 좋아요를 누를수 있도록 구현
- 게시판 인덱스와 좋아요 인덱스, 유저아이디를 외래키로 묶어서 구현 (추후 좀 더 나은 방법을 찾아보려 합니다)

### **3. 페이징 기능**

사진

- 좋아요와 최신 게시글 순서를 정할수 있으며 페이징기능을 구현

### **4. 반응형 웹**

<img width="100%" alt="반응형" src="https://user-images.githubusercontent.com/51189962/136144110-0a5cb56e-1dcf-4bc8-b7d8-b93bbb100744.gif" />

- 1240px , 800px 로 두가지 버젼으로 구현

- @media (max-width: 800px) {
  .containerWrap .realTitle{
      font-size: 24px;
      margin-right:0;
      margin-top: 50px;
      margin-bottom:21px;
  }

  .wrapper {
    width:90%;
    /* border: 1px solid tomato; */
  }

  .box1 {
      grid-template-columns:1fr;
  }

  .tdBox {
      width: 100%;
      height: 300px;
  }

  .image {
      width: 50%;
      height: 250px;
  }

  


### **5. 슬라이드 애니메이션**

<img width="100%" alt="이메일 발신" src="https://user-images.githubusercontent.com/51189962/136146784-b8b42395-8a05-402a-b393-d0aa95580c7f.gif" />

- [Frontend-](https://github.com/courd88/lastproject-front/blob/master/src/main/useScrollFadeIn.js) 를 이용한 애니메이션을 구현
- [mainpage-](https://github.com/courd88/lastproject-front/blob/master/src/main/MainPage.js) 화면이 스크롤 될 때 목록들이 슬라이드 형식으로 나타나는 애니메이션 구현-





## ⏰ 반성

총 6명이서 두달동안 작업한 기간에 비해 볼륨이 부족하다는걸 알고 있습니다

<br/>
<br/>
<br/>
