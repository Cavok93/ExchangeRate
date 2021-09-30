# 이지 환율




<p align="center"><img src = "https://user-images.githubusercontent.com/83950413/135440596-bbd9b7bc-2416-4378-9b70-662c33108d5a.png" width = "47%" height = "47%">&nbsp; <img src = "https://user-images.githubusercontent.com/83950413/135440612-4c2468e4-e2a6-445d-a168-ff509d24474e.png" width = "47%" height = "47%"> </p>



#




## Introduction
>  #### '이지 환율' 은 무료 환율계산기 어플입니다.

+ #### 개발 기간
     - 2021.08.09 ~ 08.24
+ #### 참여 인원
     - iOS 1명
+ #### 개발 목표
     - 환율정보 API를 호출하고, 받은 데이터를 기반으로 국가별 환율을 계산
+ #### 사용 기술
     - Language : Swift
     - Architecture: MVC
    - Framework : UIKit
+ #### 배운 점
   - URLSession에 대한 이해
   - API 통신 경험

#




## Screen Shot

<img src = "https://user-images.githubusercontent.com/83950413/135442012-b5354a29-0d43-4b22-8014-7db133d2ba59.png" width = "20%" height = "20%" > <img src = "https://user-images.githubusercontent.com/83950413/135442015-df282785-b324-4a92-8460-608d0b8d6e3e.png" width = "20%" height = "20%" > <img src = "https://user-images.githubusercontent.com/83950413/135442017-769f1746-fa36-43cd-950a-03e8ae567486.png" width = "20%" height = "20%" > <img src = "https://user-images.githubusercontent.com/83950413/135442019-4fcc8be2-35b5-4a9c-b51d-fb1becaf06fa.png" width = "20%" height = "20%" >


#


## 앱스토어 링크 
 + https://apps.apple.com/kr/app/%EC%9D%B4%EC%A7%80-%ED%99%98%EC%9C%A8/id1582795081


## 느낀점
한국수출입은향에 의존한 데이터 이다보니 비영업일이나, 공휴일같은 변수들이 많았다. 해달일에는 데이터 요청에 대한 응답이 이루어지지 않는다. 그렇다고 "네트워크 요청에 대한 응딥이 이루어지지 않습니다" 라고 경고창을 띄우는 것은 너무 무책임한? 처리방식이라고 생각했다. 나름 생각한 해결책은 만약 요청한 

