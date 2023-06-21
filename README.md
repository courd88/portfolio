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
- ⏰ [회고](#-회고)

</b>

## **📝 포트폴리오 개요**

<img width="100%" alt="메인 페이지" src="https://github.com/courd88/portfolio/assets/121409878/c704147b-7ee1-43cc-9ea7-c6d0c6b2f74a" />

> **프로젝트:** 외국인들의 한국관광 정보공유 사이트 [KADA]
>
> **기획 및 제작:** 김태균 외 5명
>
> **분류:** 개인 프로젝트
>
> **제작 기간:** 2023.04 ~ 2023.06
>
> **맡은 기능:** 게시글 사진 등록 , 좋아요 기능 , 페이징 , 반응형 웹 , 슬라이드 애니메이션
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

<img width="100%" alt="라이트/다크모드" src="https://github.com/courd88/portfolio/assets/121409878/3bc90b8b-7dc5-4a3d-9088-8bfc7017c6c9" />

- 기본 게시판 글쓰기에 사진을 넣을 수 있게 구현
- 사용자의 글수정에서도 사진을 변경 가능하도록 구현
- 목록에서 사진과 글을 보일수 있도록 구현

### **2. 좋아요 기능**

- 글 목록에서도 글 상세보기에서도 좋아요를 누를수 있도록 구현
- 게시판 인덱스와 좋아요 인덱스, 유저아이디를 외래키로 묶어서 구현 (추후 좀 더 나은 방법을 찾아보려 합니다)

### **3. 페이징 기능**

사진

- 좋아요와 최신 게시글 순서를 정할수 있으며 페이징기능을 구현

### **4. 반응형 웹**

<img width="100%" alt="반응형" src="https://github.com/courd88/portfolio/assets/121409878/2d53d90b-cfce-4d2f-8eee-ad0818737476" />

- 1240px , 800px 로 두가지 버젼으로 구현

- @media (max-width: 1240px){
    #main-page{
        width: 100%;
        margin-left:0%;
    }

    #main-koreaissue{
        display: flex;
        padding: 0 40px;
        
    }

    .main-koreaissue-li{
        width: 48%;
    }
}

@media (max-width: 800px){
    #main-koreaissue{
        display: flex;
        padding: 0 40px;
        
    }

    .main-koreaissue-li{
        width: 100%;
    }
}
  


### **5. 슬라이드 애니메이션**


- [Frontend-](https://github.com/courd88/lastproject-front/blob/master/src/main/useScrollFadeIn.js) 를 이용한 애니메이션을 구현
- [mainpage-](https://github.com/courd88/lastproject-front/blob/master/src/main/MainPage.js) 화면이 스크롤 될 때 목록들이 슬라이드 형식으로 나타나는 애니메이션 구현-





## ⏰ 회고

총 6명이서 두달동안 작업한 기간에 비해 볼륨이 부족하다는걸 알고 있습니다<br/>
처음 시작 하면서 서로 아이디어를 내고 기획을 하는 부분에서 여러 난관이 있었지만<br/>
나름 모두의 마음에 충족 시킬수 있던 프로젝트였습니다<br/>
진행과정 중 여러 트러블이 있었지만 서로 의견을 제시하고 대화를 통해 풀어나아가<br/>
서로 존중과 배려를 해주어 끝까지 무탈하게 완성시킬수 있었습니다.<br/>

<br/>
<br/>
<br/>
