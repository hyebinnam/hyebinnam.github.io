---
layout: post
title: 일상과 공부(<마우스 우클릭 방지// siteSecurity.js)
---

요즘 너무 바쁜 생활..
하고싶은 것도 너무 많고, 해야 할 것도 너무 많아서 손이 떨린다.

청춘의 독서 <br>
이 책을 주면서 사랑하는 딸에게 말하고싶다. 세상은 죽을 때까지도 전체를 다 볼 수 없을 만큼 크고 넓으며, 삶은 말할 수 없이 아름다운 축복이라는 것을. 인간은 이 세상을 위해 태어난 것이 아니라 이 세상에 살러 온 존재이며, 인생에는 가치의 우열을 가릴 수 없는 여러 길이 있다는 것을. 그리고 어느 길에서라도 스스로 인간다움을 잘 가꾸기만 하면 기쁨과 보람과 행복을 발견할 수 있다는 것을..

책은 나를 참 설레게 만든다.. 듣고싶은 얘기는 책 속에 담겨있다.

html파일

    <script src="/js/siteSecurity.js"></script><!-- 보안 마우스 우클릭 방지 -혜빈 -->

    <script type="script">
      $(function(){
          $('body').siteSecurity({
              f12:'y',         //f12키 막기
              rightclick: 'y', //우클릭 막기
              select:'y',      //선택 막기
              drag:'y',        //드래그 막기
              execptionip:'27.35.21.239' //예외 아이피
          });
      });
    </script>   

js파일

/*************
name : siteSecurity.js
************/

<text>
<iframe height='265' scrolling='no' title='siteSecurity.js' src='//codepen.io/hyebin/embed/YvmyKK/?height=265&theme-id=0&default-tab=js,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/hyebin/pen/YvmyKK/'>siteSecurity.js</a> by 남혜빈 (<a href='https://codepen.io/hyebin'>@hyebin</a>) on <a href='https://codepen.io'>CodePen</a>.



/////안될경우
<text>
<body id="main" oncontextmenu="return false" ondragstart="return false" onselectstart="return false"></body>
</text>
