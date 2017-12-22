---
layout: post
title: Guide to Developing this Blog
author: gandhi
published: true
---
## 무엇으로 만들었나요??
- 지킬(jekyll)

## [지킬(jekyll)이란??](https://jekyllrb-ko.github.io/)
- 오픈소스 블로그

## jekyll vs wordpress
- wordpress 보다 가볍다.
- github 에서 호스팅된다.
- wordpress 보다 포스팅(글쓰기) 힘들다?

## 개발하기(Quick-start)
1.[지킬테마](http://jekyllthemes.org/)에서 선택 후 Fork한다. 
- 내가 고른 [테마](https://github.com/chesterhow/tale)
- 404나 css가 적용 안되는 테마들도 있다;; url경로 문제인듯

2.Fork 후 Fork된 나의 github -> Settings -> Repository name -> 닉네임.github.io 로 수정해준다.

3."_config.yml"파일을 
- baseurl:        "/tale"
- url:            "https://chesterhow.github.io"

아래와 같이 수정했다.(github에서 직접 수정)
- baseurl:        "/"
- url:            "https://gandhikim.github.io/gandhi"

4.[끝](https://gandhikim.github.io/) 


## 포스팅하기
1.[md(markdown)](https://gist.github.com/ihoneymon/652be052a0727ad59601)
- "_posts"폴더에 ".md" 파일을 만들어 포스팅한다
- "_posts/yyyy-MM-dd-my-title.md"(ex:_posts/2017-12-22-my-title.md")

2.방법
- github -> "_posts"폴더 -> "Create new file"버튼 -> md파일 생성
- http://prose.io for quick-and-simple GitHub editing
- git소스를 로컬pc로 다운받아 수정해서 올리는 방법
- [Tools for Writing and Previewing Markdown](http://mashable.com/2013/06/24/markdown-tools/#B.qNIBA7_Zqx)