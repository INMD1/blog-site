---
title:  "동아리 프로젝트 하면서"
categories: blog
---
# 개발 구성
군대 가기전 뒹글 뒹글 하면서 놀고 있는 선배가 `이런거 해볼래?`라는 이야기를 듣고 <br>
군대가기전 프로젝트를 해보자는 마음에 하게 되었다.<br>
처음에는 모바일 앱을 통해서 학교의 소식을 알리는 방향으로 만들기로 했고 앱을 설치 안 하고 웹으로 볼 수 있게
같이 개발하자는 선배의 의견을 듣고 둘 다 개발하기로 했다.

# 첫 프로그램 개발
<br>
<p align="center">
    <img src="https://ionicframework.com/img/meta/ionic-framework-og.png" style="width: auto; height : 200px;">
    <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--VtIgiqJe--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/d440mmj72v2vi7ad76ir.png" style="width: auto; height : 200px;">
</p>
웹앱을 하기 위해서 먼저 앱을 개발해야겠다고 생각했지만 시간이 오래 걸릴 거 같아서 ionic이라는 프레임워크를 이용하기로 했습니다.<br>
ionic는 하이브리드 앱을 만들 수 있는 프레임워크, 즉 웹을 만들면 그걸 앱 내부에 넣어서 웹앱을 만들 수 있습니다.<br>
이걸 이용하면 앱이랑 웹을 따로 안 만들어도 되고 웹 파일을 따로 들고 와서 웹을 호스팅 할 수 있으니 개발기한이 단축되기 때문에 이걸로 앱을 만들었습니다. 웹을 ionic에서 Vue 프레임워크를 지원하기 때문에 vue.js를 이용해서 만들었습니다.<br>
하지만 선배는 이렇게 하면 안드로이드 쓰는 사람들은 앱을 설치해서 쓸 수 있지만 IOS에게서는 앱을 설치를 못 하고 계속 사이트에 들어가야 해서 그냥 브라우저에 있는 앱 만들기 기능 같은 걸 이용해서 웹을 만들면 되지 않겠냐는 의견에 수용해서 개발한 웹 파일만 빼서 호스팅을 했습니다.<br>
<br>
## 간단한 리뷰
<p align="center">
    <img src="https://user-images.githubusercontent.com/87979171/165301138-99f07ffd-c5d1-4b5d-ba1c-fc1c1228c382.png" style="width: auto; height : 600px;">
</p>
그래서 사진을 다 만들었다. 사진을 보면 맨 처음에는 사람들이 많이 보는 학식이랑 학사공지를 뛰어 두고 다른 소식은 다른 페이지에서 볼수있게 
밑에 버튼을 만들어서 이동할수 있게 했다.<br>
<br>
프로젝트 한번 보려가기: https://github.com/asw-dod/DoD_app_vue_container
<br>
<br>
  
# 두번쨰 프로그램 
<br>
위에 모바일 웹을 만들고 선배는 이제 TV에다가 띄울 웹 페이지를 만들어달라고 부탁했다!<br>
그래서 똑같이 Vue.js 프레임워크를 이용해서 웹페이지를 만들고 있었다. 하지만 모바일은 간단하게 디자인하면 되었기에 쉬였는데<br>
크기가 큰 TV 같은 경우는 사람들이 자주 들락거리면서 많이 보기 때문에 디자인에 공을 들어야 했었다. 하지만 디자인하면서 더욱 
디자인이 이상하게 되는 생각에 스트레스가 받았는데 디자인을 전문적으로 하는 선배가 와서 디자인 의견을 주었고 그걸 토대로 개발을 계속했었다.<br>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/87979171/165301519-eb21ef29-90c9-4247-aeed-8da787a1edfa.png" style="">
  </p>
  
이떄 정말까지는 괜찮게 했다.

하지만 첫 번째 웹 개발보다 너무 많은 피드백이 몰리기 시작했다.
* 스크롤 되게 해줘
* 게임, 음악, 날씨 넣어줘
* 세벽에 화면 안뜨게 해줘 등..
진짜 머리에서 폭발 할 정도로 많이 들어와서 내가 할 수 있는 만큼 의견 반영해줬다.

## 간단한 리뷰
결국 어찌어찌 해서 만들었다. 
  <p align="center">
    <img src="https://user-images.githubusercontent.com/87979171/165301733-3b79d03c-b829-487c-882e-06f71240869c.png" style="">
  </p>

화면에서는 날씨 시간, 학식,학교 정보 다 때려 넣어서 표시하게 했다.<br>
<br>
프로젝트 한번 보려가기: https://github.com/asw-dod/DoD_DashBoard
<br>
<br>

# 프로젝트 끝 
    
이제 모든 개발이 끝났다.<br>
나는 프로그램을 개발 하면서 많은 피브백 하고 스트레스가 몰려왔지만<br>
스트레스는 낯구고 할수 있는 피브백과 개선사항을 수정하고 하니 완성이 되어 있었다.<br>
이제 남은 건은 성능개선과 코드 최적화 그리고 새로운 기능을 추가하는 것이다.<br>
하지만 군대 입대가 얼마 안 남았지만 할 수 있는 만큼 해보고 안 되면 가끔 휴가 나올 때 계속 개발할 예정이다.


