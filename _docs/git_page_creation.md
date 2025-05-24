---
title: github pages getting started
nav_order: 0
parent: Documentation
layout: default
---

최초 작성: 25.05.24(토)
수정: xx.xx.xx 

# 시작

개발자는 아니지만 업무적으로 코딩을 종종 한다. 그럼 구글링은 필수고 가끔 눈에 띄는 포맷의 블로그가 있다. 그러다가 알았다. Github pages라는 플랫폼이 있다는 것을.
관련해서 블로그 포스트도 있고, 유튜브도 있고 따라만 하면 쉽게 만들겠지 했다. 그런데 이해는 못하고 따라만 하고 결국에는 pages를 완성하지 못했다. 
실망감을 가지고 한 동안 쉬다가 따라하면서 보고 들었던 개념들을 느리지만 천천히 알아가보기로 했다. 조급한 마음 가지지 말고.

## Github pages documentation
> <a href="https://docs.github.com/ko/pages/getting-started-with-github-pages" target="_blank"> 깃허브 페이지의 공식 문서</a>에 들어가 보자. 개발자들은 공식 문서를 만들어 놓는 것 같다.

_언어 옵션에 한국어가 있다. 모두 번역해주는 줄 알았는데 몇 페이지 넘어가니 안해주더라, 물론 요즘 웹브라우저에 번역기능이 잘되있긴하지만 뭔가 속은 기분이 든다._

### What is github pages?
문서의 시작은 <a href="https://docs.github.com/ko/pages/getting-started-with-github-pages/what-is-github-pages" target="_blank"> What is GitHub Pages?</a> 이다. 내용이 길지는 않지만 다 이해는 못했다.

그럼에도 눈에 들어온 문장은 **"GitHub Pages은(는) 이제 GitHub Actions을(를) 사용하여 Jekyll 빌드를 실행합니다."** 깃허브 페이지로 블로그를 만드는 것은 알겠는데 Actions는 뭐고 Jeckll은 뭘까.

> **Github Actions** <br>
GitHub 저장소에 어떤 변화가 생겼을 때 자동으로 작업을 실행해주는 도구. 여기서 말하는 작업은 코드 빌드, 테스트, 배포 등 반복적인 동작을 의미한다고 한다.

레포지토리를 업데이트하고 내가 작성한 글에 맞춰 웹사이트를 빌드하는데 Github Actions를 들어가보면 빌드가 잘되었는지 진행중인지, 문제가 생겼다면 에러 로그도 확인이 가능하다.

> **Jeckll** <br>
Markdown 같은 정적 파일을 HTML 웹사이트로 바꿔주는 정적 사이트 생성기(static site generator)**입니다.

다시말하면 마크다운을 바로 웹사이트에 못띄우니까 HTML 형식으로 변환시켜준다.로 이해했다. 
