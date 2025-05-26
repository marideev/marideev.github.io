---
title: github page 만들기(아주 basic)
nav_order: 1
parent: Documentation
layout: default
---

최초 작성: 25.05.26(월)
수정: xx.xx.xx 


# GitHub Pages 사이트 만들기
> <a href="https://docs.github.com/ko/pages/getting-started-with-github-pages/creating-a-github-pages-site" target="_blank"> Github pages 사이트 만들기 </a> 페이지로 넘어가 보자.

앞선 페이지에서 "리포지토리에 어떤 파일들만 있으면 깃허브 액션이 재키빌드로 나의 블로그 페이지를 만들어준다."라고 이해했다. 

그럼 어떤 파일들이 기본적으로 있어야 파일이 만들어질까?

그전에 리포지토리(저장소)를 만들기어야 한다. 이때 몇가지 규칙을 해당 페이지에서 설명해 준다.
> - 무료 플랜 사용자는 저장소를 public으로 만들어야 한다. 
> - 저장소 이름은 "\<user\>.github.io" 로 설정한다.

이제 저당소에 들어갈 파일을 살펴보자.

"Creating your site"의 3번에 이렇게 적혀있다. 
> Create the entry file for your site. GitHub Pages will look for an `index.html`, `index.md`, or `README.md` file as the entry file for your site.

위의 세 가지 파일 중 하나를 찾아서 깃허브 페이지의 첫 페이지로 사용할 것라고 보여진다. 

gpt한테 index.md 예시 하나만 만들어줘 하면 아래처럼 만들어 줬다. 

```markdown
# index.md
---
layout: default
title: 홈
---

# 안녕하세요!
Jekyll 블로그에 오신 것을 환영합니다.
```

`index.md` 만 저장소에 넣어놔도 나만의 페이지가 만들어진 것을 확인할 수 있다. 다만 아무것도 없는 대문이다. 다음 단계로 넘어가야 한다.