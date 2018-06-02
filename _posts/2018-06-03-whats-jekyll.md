---
layout: post
title: Ajax & JSON
---

<!-- [Jekyll](http://jekyllrb.com) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes. From [the project's readme](https://github.com/mojombo/jekyll/blob/master/README.markdown): -->

<!--   > Jekyll is a simple, blog aware, static site generator. It takes a template directory [...] and spits out a complete, static website suitable for serving with Apache or your favorite web server. This is also the engine behind GitHub Pages, which you can use to host your project’s page or blog right here from GitHub. -->

Ajax는 전체 페이지를 새로 고치지 않고도 페이지의 일부만을 위한 데이터를 로드하는 기법이다. 데이터는 주로 JSON(javascript Object Notation 자바스크립트 객체 식)이라고 부르는 형태로 전달된다.

페이지의 일부분에만 새로운 콘텐츠를 로드하는 기능은 사용자의 전체적인 사용 경험을 향상시킬 수 있다. 이는 페이지의 일부만 수정하게 되면 사용자가 전체 페이지가 로드될 때까지 기다릴 필요가 없기 때문이다. 이 기법은 소위 단일 페이지 웹 애플리케이션(SPA: Single Page Application, 브라우저에서 실행되기는 하지만 마치 소프트웨어 애플리케이션 같은 느낌을 주는 웹 기반 도구)이 등장하는 계기가 되었다.

데이터 타입: 서버는 주로 HTML, XML, JSON을 전달하므로 이에 관해 학습해야 한다.

jQuery는 Ajax 요청을 생성하고 서버로부터 전달받은 데이터를 처리하는 과정을 손쉽게 만들어준다.
<!-- Find out more by [visiting the project on GitHub](https://github.com/mojombo/jekyll). -->
