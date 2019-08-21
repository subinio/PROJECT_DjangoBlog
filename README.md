
# Blog-Portfolio Project for Django 
해당 프로젝트는 블로그를 제작하는 프로젝트로, 장고 웹 프레임워크를 사용하였습니다.

<br>

## Table of contents
* Directory Structure Diagram
* Development Contents
* Development Environment 
* Implement screen
* Deployment
* License
* Contact


<br><br><br>

## 1. Directory Structure Diagram
```
├─blogapp
│  ├─migrations
│  │  └─__pycache__
│  ├─static
│  │  └─js
│  ├─templates
│  └─__pycache__
├─blogproject
│  └─__pycache__
├─media
│  └─images
├─portfolio
│  ├─migrations
│  │  └─__pycache__
│  ├─static
│  │  └─js
│  ├─templates
│  └─__pycache__
└─static
    └─admin
        ├─css
        │  └─vendor
        │      └─select2
        ├─fonts
        ├─img
        │  └─gis
        └─js
            ├─admin
            └─vendor
                ├─jquery
                ├─select2
                │  └─i18n
                └─xregexp
```

<br>

## 2. Development Contents
* **로그인**
로그인, 로그아웃에 따라 해당 블로그 글 작성, 포트폴리오 관리 및 블로그 설정을 관리하도록 함.
//해당 내용은 개발 진행 중입니다.

* **글 작성 기능**
사용자가 글을 작성하여 등록하면 게시판에 날짜 순으로 정렬됨.

* **글 미리보기 및 전체보기**
글 미리보기 기능을 통해 게시판에 정렬하고, 각각의 글을 누르면 글의 내용 전체보기가 가능하도록 함. 

* **포트폴리오**
static/media 를 이용한 포트폴리오 관리 (이미지저장에 관한 기능)

* **파일업로드**
파일 업로드 기능을 추가하여 홈메인 화면을 사용자가 원하는 사진으로 바꾸도록 함.
파일 업로드를 구현하기 위하여 *forms.py* 를 작성하여 폼에서 사진을 media로 받음. 

* **메인 색, 타이틀이름, 배경이미지 변경**
메인 색은 navbar의 색, 블로그의 전체적인 글의 색 등을 모두 지칭하므로 settings에서 블로그의 메인 색을 변경하여 블로그를 꾸밀 수 있음. 해당 내용은 form기능과 javascripts를 사용하여 구현하도록함.
메인 색, 타이틀 이름, 배경이미지 변경은 settings탭에서 변경 가능하도록 함.

* **settings**
블로그를 꾸밀 수 있는 설정에 대한 아이디어가 더 필요함. 해당 내용은 고민 후 바로바로 추가할 예정.

<br>

## 3. Development Environment  
* Window10
* visual code
* Python (Django web framwork)
* sqlLite3

<br>

## 4. Implement screen
### Main
![main](https://user-images.githubusercontent.com/49118667/63402611-fb8a9a00-c416-11e9-9680-42c0f991055d.JPG)

### portfolio
![portfolio](https://user-images.githubusercontent.com/49118667/63402650-18bf6880-c417-11e9-9800-9c9c9323c24f.JPG)

### Settings
![image](https://user-images.githubusercontent.com/49118667/63402570-da29ae00-c416-11e9-8f58-a91c2db914ae.png)


<br>

## 5. Deployment
* using **pythonanywhere** web hosting service
* [http://subinio.pythonanywhere.com/](http://subinio.pythonanywhere.com/)

<br>

## 6. License

<br>


## 7. Contact
* FAQ❔: [This repository Issue](https://github.com/subinio)
* mail✉️ : subinjin22@gmail.com

