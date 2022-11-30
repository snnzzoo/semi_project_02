# Brokurly🥦

> 이커머스 사이트 [ Brokurly🥦] project
>
> Domain : http://brokurly.shop/
>
> ![logo.png](assets/9d4aadd340d3ad41028ddcbf41a645a7a24fb09a.png)

## 🔖 Table of contents

-   [Brokurly🥦](#brokurly)
    -   [🔖 Table of contents](#-table-of-contents)
    -   [📜 General info](#-general-info)
    -   [🧭Requirements](#requirements)
    -   [🗃️Modeling](#️modeling)
        -   [ERD모델](#erd-모델)
        -   [와이어프레임](#와이어-프레임)
    -   [💻Technologies](#technologies)
        -   [Technology stack](#technology-stack)
    -   [🔍Features](#features)
        -   [담당 역할](#담당-역할)
        -   [기능 소개](#기능-소개)
        -   [Main Page](#main-page)
        -   [Accounts APP](#accounts-app)
        -   [Products APP](#products-app)
        -   [Reviews APP](#reviews-app)
        -   [Qnas APP](#qnas-app)
        -   [Orders APP](#orders-app)
    -   [💬Reviews](#reviews)
    -   [Scrum Records](#scrum-records)

## 📜 General info

-   메인화면 사진

    ![Untitled](https://user-images.githubusercontent.com/104806801/204688386-4c0a9bcc-26c2-48ca-876f-47227ccb3005.png)

    

-   개발기간 : 2022. 11. 09 - 2022. 11. 22

-   팀원

    -   Front-end([김예린](https://github.com/ererink/), [임선주](https://github.com/snnzzoo/))
    -   Back-end([이동근](https://github.com/qlghwp123/), [이태극](https://github.com/uRo3YA/), [최준우](https://github.com/wnsn8546/))

## 🧭Requirements

-   1️⃣ 서비스에는 최소 20개의 콘텐츠 정보(여행지, 맛집, 영화, 상품)가 생성된 상태여야 합니다.
-   2️⃣ 콘텐츠 정보 & 후기 공유 커뮤니티 서비스에 필요한 최소한의 CRUD를 구현해야 합니다.
-   3️⃣ 회원 인증 기능을 구현하고, 권한에 따라 서비스 사용을 제한해야 합니다.
-   4️⃣ 사용자는 콘텐츠 또는 후기에 좋아요를 남길 수 있어야합니다.
-   5️⃣ 사용자간 팔로우를 할 수 있어야합니다.
-   6️⃣ HTML / CSS / JavaScript를 활용해서 웹 사이트를 디자인합니다.
-   **7️⃣ 완성한 서비스는 배포해야하며 발표회에서는 배포된 서비스를 시연해야 합니다.**

## 🗃️Modeling

### ERD 모델

> ![brokuly_20221120_221825.png](assets/44acdf0f19105dcc740be7e9619498ca38c07c7f.png)

### 와이어 프레임

 - [Figma Link](https://www.figma.com/file/jiVLhSHUiwT51ndzyLm0av/%EB%B8%8C%EB%A1%9C%EC%BB%AC%EB%A6%AC?node-id=0%3A1&t=dhefFUTcmJxXy7Zv-1)

> ![Screenshot 2022-11-20 at 22.24.30.JPG](assets/57f934bf2a6c240800146820c4a25af9436a08cb.JPG)



## 💻Technologies

### Technology stack

-   Version Control and Messenger

    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white">

-   Backend and Testing

    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white">

-   Frontend

    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">

*   Infra

    <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white"> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"> <img src="https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white"> <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white">

## 🔍Features

### 담당 역할

#### 공통

-   프로젝트 기획
-   Figma로 화면 설계


#### 임선주

-   Front-end
-   Navbar -  dropdown menu, 일부 css
-   Footer
-   Top button
-   마이페이지, 장바구니, 주문하기/주문완료 페이지 화면 구현
-   각 페이지별 세부 디자인 통일

<details>
<summary>김예린</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

-   Front-end
-   메인 페이지, 상품 메인 페이지, 상품 상세 페이지 화면 구현
-   navbar 구현
-   회원가입 및 로그인, 회원탈퇴 페이지 화면 구현

</details>

<details>
<summary>이동근</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

-   Team Leade
-   Back-end(Accounts App)
-   Deploy to Amazon EC2
-   Bug Fix

</details>

<details>
<summary>이태극</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

-   Back-end (Products, Review App, Accounts 일부)
-   Crawling
-   Search
-   Bug Fix

</details>

<details>
<summary>최준우</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

-   Back-end(Order,Qnas)
-   Social Login(Naver, KaKao)
-   Social Share(Facebook, Twitter, Naver, KaKao)
-   KAKAO Address Search API, KAKAO Map API, KAKAO Pay API
-   ID , Email Duplication Check, Email Verification(Number check)
-   Bug Fix

</details>


### 기능 소개

### Main Page

-   Navbar

    > 스크롤에 따라 레이아웃이 변형됨
    >
    > ![image](https://user-images.githubusercontent.com/104806801/204690289-2f2017c9-b0e3-4bd0-9689-1a6ab78b4bb9.png)

    > 스크롤을 내릴 경우
    >
    > ![Untitled (2)](https://user-images.githubusercontent.com/104806801/204689003-816cd790-84f7-4b6a-a510-ad6514cc5d71.png)


-   Section

    > 각각의 섹션에서 조회기준을 통해 여러 객체 출력

-   챗봇

    > 화면 우측 하단에 top button과 함께 위치
    > <br>
    > ![Untitled (3)](https://user-images.githubusercontent.com/104806801/204689273-f06398ab-5351-4e44-8b53-441dbfdbbad6.png)
    > ![Untitled (4)](https://user-images.githubusercontent.com/104806801/204689295-7fce3669-3497-464d-a8a6-82e9eab4b637.png)



### Accounts APP

-   CRUD

    > 판매자 / 구매자를 선택하여 유저 생성 가능
    >
    > ![Untitled (5)](https://user-images.githubusercontent.com/104806801/204689595-5504a0ba-799e-4a3e-b3e1-f3bc1ae107fd.png)
    > ![Untitled (6)](https://user-images.githubusercontent.com/104806801/204689631-8e4749d7-5970-4c57-9f5a-1bc2d3bbd917.png)



-   로그인, 로그아웃

    > 로그인, 로그아웃 기능 구현
    > 
    > ![Untitled (7)](https://user-images.githubusercontent.com/104806801/204689697-4e4652fb-0a46-4b61-a240-f81a1af3a5d7.png)


*   마이페이지

    > 판매자 / 구매자에 따라 화면 구성을 다르게 보여줌
    >
    > ![Untitled (12)](https://user-images.githubusercontent.com/104806801/204689943-d8b32ff9-a46f-4719-b27f-8bba78fe8471.png)


*   장바구니

    > 상품 상세에서는 장바구니로 redirect
    >
    > 검색 및 위시리스트에서 모두 비동기 통신으로 장바구니 추가/삭제 구현
    >
    >![Untitled (8)](https://user-images.githubusercontent.com/104806801/204689723-4dd7904f-b07f-4ef0-8e8c-cd915060b8c7.png)


*   위시리스트

    > 상품 상세에서 비동기로 추가 기능 구현
    >
    > ![Untitled (11)](https://user-images.githubusercontent.com/104806801/204689877-c169f0f0-6af8-4f6b-9234-22ffa732bc51.png)


*   유저가 작성한 리뷰 목록

    > 유저가 작성한 리뷰 목록을 마이페이지에서 조회 가능

*   아이디 및 이메일 중복체크

    > DB 에서 ID 중복 체크, 이메일

*   네이버 로그인

    > 네이버 로그인 구현

*   상품 관리

    > 현재 판매자가 판매하고 있는 상품을 조회

*   상품 문의

    > 현재 구매자가 생성한 문의 목록을 조회

*   이메일 인증

    > 랜덤 코드 발송을 비동기로 구현

*   주문 목록

    > 현재 구매자가 주문 생성한 목록을 조회

### Products APP

-   index 페이지

    > 호버로 제품별 이미지 효과

-   상세 페이지

    > 상품 리뷰 작성은 모달 팝업으로 제작
    > 상품 문의는 아코디언으로 확장
    >
    > ![Untitled](https://user-images.githubusercontent.com/104806801/204764938-d642bf61-6874-447d-a908-997d622d994e.png)


-   데코레이터

    > 데코레이터 구성으로 유저 권한(판매자/구매자)에 따른 기능 접근 제한

-   CRUD

    > 상품 생성시 멀티셀렉트 필드를 이용한 다양한 옵션 선택 가능

-   크롤링

    > 크롤링을 통한 기존 상품들 대량 등록

-   페이지네이션

    > 페이징처리하여 상품별 출력 갯수 적절히 조절

-   검색 기능

    > Q 모듈을 이용한 검색기능
    > Listview를 이용한 페이지네이션

-   판매자 팔로우 기능

    > 비동기 통신으로구현 Accounts 앱으로 연결
    > 마이페이지의 팔로잉 목록에서 판매자의 최근 판매 상품 볼 수 있음

-   위시리스트 기능

    > 비동기 통신으로구현 Accounts 앱으로 연결

-   상품문의 기능

    > 상품별 상세 페이지에서 문의사항과 답변을 출력하며
    > 기능은 Qnas앱으로 연결

-   장바구니 기능

    > Orders 앱으로 연결

### Reviews APP

-   CRUD

    > 리뷰 모델과 분리한 이미지 모델을 이용해 하나의 리뷰에 여러 이미지 삽입

-   평점

    > 상품에 해당하는 리뷰 평점을 계산하여 상품 평점 반환

-   추천

    > 비동기 통신으로 구현

-   댓글

    > 비동기 통신으로 구현

### Qnas APP

-   질문 CRUD

    > 상품에 대한 구매자의 문의 작성, 조회, 수정, 삭제
    >
    > ![Untitled (1)](https://user-images.githubusercontent.com/104806801/204765034-d84e0b04-1c52-4b20-b3d7-7fa6b96ceb8b.png)


-   답변 CRUD

    > 문의에 대한 판매자의 답변 작성, 조회, 수정, 삭제

-   상태

    > 답변대기, 답변완료상태 표시

### Orders APP

-   주문 기능

    > 카트 -> 주문서 -> 주문완료의 흐름으로 구현
    >
    > ![Untitled (2)](https://user-images.githubusercontent.com/104806801/204765089-f6333424-73db-464f-9397-ab8f79037aac.png)


-   결제 기능

    > 카카오페이 API 를 활용한 결제 확인 테스트 구현

## 💬Reviews

-   임선주

    -   실력 있는 팀원 분들과 기획 단계부터 개발까지 이전보다 더 꼼꼼하게 진행하면서 다양한 개발 지식을 배울 수 있었습니다. 
    -   첫 번째 프로젝트보다 기간이 길어 여유가 좀 있지 않을까 라고 생각했으나, 하나를 완성했다고 생각하면 다른 부분에서 오류가 발생하는 과정이 반복되었습니다. 그렇지만 지금까지 해왔던 프로젝트 중 가장 완성도가 높다고 생각합니다. 
    -   이번 프로젝트를 통해 css 지식을 많이 배울 수 있었습니다. block/inline 요소, 그리고 flex의 개념과 활용을 더 잘 알게 되었습니다. 
    -   자바스크립트를 활용하고 싶은 부분이 많았으나 너무 어려웠습니다.. 그래서 자바스크립트를 자유자재로 활용할 수 있기 위한 공부를 시작했습니다. 
    -   팀원들과 소통하고 협업하는 방법을 배울 수 있어서 좋았습니다. 또 문제가 생겼을 때 어떻게 풀어나갈 수 있을 지에 대해서도 배웠습니다.
    -   프로젝트 마지막 날 몸이 좋지 않아 마무리를 제대로 하지 못한 것이 마음에 걸리고 체력 관리의 중요성을 알게 되었습니다. 실제 프로젝트는 이보다 더 장기간동안 더 많은 에너지를 쏟아 부을텐데, 체력관리는 선택이 아닌 필수!라는 것을 깨닫게 되었습니다.
    -   그동안 부족한 저와 함께 한 팀원 분들 정말 고생 많으셨고 감사했습니다. 앞으로 모두 잘 되기를!!


<details>
<summary>김예린</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->
 -   프론트엔드를 경험해본 적이 없어 더 나은 기능으로 더 나은 화면을 구현하지 못한 것에 대한 아쉬움이 컸습니다. Javascript를 더 공부해보고 싶은 생각이 들었습니다.
 -   팀원분들의 작업 방식을 더 이해하며 협업해야 하는 중요성과 깨달음을 얻을 수 있었던 경험이었습니다.
 -   프론트엔드의 역할과 고충을 체득할 수 있었던 소중한 경험이었습니다. 앞으로 다른 역할로서 프로젝트에 참여할 때 프론트엔드의 작업방식을 이해하며 더욱 협력적인 자세로 임할 수 있을 것 같습니다.

</details>

<details>
<summary>이동근</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

 -   이번 프로젝트에서 팀의 팀장으로서 미숙했던 점이 아주 많았다는 것을 알게 되었습니다.
 -   제가 생각한 문제점과 알게된 것은 다음과 같습니다.
 -   기획에 비해 저의 개발 속도가 매우 느렸습니다.
     -   개인 개발 역량을 키워야 함을 깨달았습니다.
 -   업무 분담이나 소통 및 팀원 역량 파악 등 많이 부족합니다.
     -   더 많이 소통하고 팀원 이전에 사람으로서 다가가는 것이 필요하다는 것을 알게 되었습니다.
 -   결정 해야할 때를 놓치고 우유부단하여 초기 생각했던 것보다 많은 시간이 소요되었습니다.
     -   팀에 필요한 일이라면 직언이 필요함을 깊이 깨달았습니다.
 -   노션과 디스코드를 사용하다 보니 문서의 통일을 못한거 같습니다.
     -   분명하게 정하고 문서화하는 습관과 정리하는 습관이 필요하다는 것을 알게 되었습니다.
 -   역량이 부족해서 항상 팀원분들께 많이 미안하고 죄송하고 감사했습니다.
 -   힘들었지만 정말 값진 시간을 얻은거 같습니다.

</details>

<details>
<summary>이태극</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

 -   코드짜는 것보다 더 중요한건 협업 과정에서 소통이라고 생각합니다.
 -   **코드짜는 것보다 더 중요한건 협업 과정에서 소통이라고 생각합니다.**(중요하니 두번)
 -   왜 사람들이 Django에서 함수형 뷰를 안쓰고, 제네릭 뷰로 상속 받아서 쓰는지 알게되었습니다.
     -   특히 마이페이지 구현이나, 검색의 경우 이전 페이지에서 값들 불러온 상태에서 렌더링이 되야 하는데 일반 함수형 뷰를 쓸 경우 context에 많은양을 집어넣어야 해서 다른 코드를 재활용하기 힘들었습니다.
 -   쿼리 조회의 경우 분명 더 간결한 조회 조건이 있을것인데 상당히 복잡하게 짜서 출력관련해서 제가 다시 봐도 이해하기 어려웠습니다.

</details>

<details>
<summary>최준우</summary>

<!--summary 아래 빈칸 공백 두고 내용을 적는공간-->

 -   이전 프로젝트에서 하고 싶었던 다양한 API들을 사용해볼 수 있었던 기회였습니다.
 -   주문, 이메일 인증 등의 기능 흐름을 살펴보고 해당 기능을 구현할 수 있는 다양한 방법들을 찾아 볼 수 있었습니다.
 -   다음 프로젝트에서는 이번 프로젝트의 경험을 바탕으로 DRF 등을 활용하여 직접 API서버도 구축 해봐야겠다는 생각이 들었습니다. 감사합니다.

</details>


## Scrum Records

-   [스크럼 일지 바로가기!](https://github.com/qlghwp123/SPJT-02/tree/main/scrum)

