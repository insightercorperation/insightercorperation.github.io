---
layout: post
title: '개발 블로그 포스팅 방법'
description: '개발 블로그 작성 방법을 포스팅 합니다.'
author: ari
date: 2019-03-25 00:00
tags: [guide]
image: /files/covers/introduce.jpg
---

[![insighter_image_test](/assets/images/pc/logo.png){:width="50%"}](/assets/images/pc/logo.png)
> 안녕하세요. 인사이터 기술 블로그 입니다.
> 본 포스트는 포스팅 테스트와 더불어 작성자 등록 및 포스트 방법에 대해 안내해 드리겠습니다. :)

* 작성자
    - v1.0.0: [ari](/authors/ari/) (2019-03-25)
    - v1.1.0: [alex](/authors/ari/) (2019-04-04)

## 1. 작성자 등록 방법
작성자 등록은 `/_authors/` 폴더에서 `name.md` 파일을 만든 후

```
---
name: 작성자 영어 이름
title: 작성자 한글 이름
image: /files/authors/작성자_영어_이름.jpg
---
```

다음과 같은 형식에 맞도록 작성해 주시면 됩니다.
프로필에 나타날 이미지 사진은 `/files/authors/` 폴더에 넣어주시면 됩니다.


## 2. 포스팅 방법
포스팅은 `/_posts/` 폴더에 `YYYY-MM-DD-title.md` 파일을 만든 후

```
---
layout: post
title: '제목'
description: '포스트의 내용을 간략하게 설명합니다.'
author: author Name
date: YYYY-MM-DD 00:00
tags: [tag_name]
image: /files/covers/cover_image_name.png
---
```

다음과 같은 형식에 맞도록 작성해 주시면 됩니다.
태그명은 `3. 태그 등록 방법`을 참고하여 태그를 등록 한 후 사용해야 합니다.
포스팅의 커버 이미지는 `/files/covers/` 폴더에 넣어 주세요.

포스팅 내에서 사용하는 이미지는 `/files/`에 넣으신 후 `![이미지 설명](/files/img_name.png)` 와 같은 형태로 사용하실 수 있습니다.
포스팅은 마크다운 형식으로 작성하실 수 있으며, 마크다운 문법에 대한 사용 방법은 [링크](https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/)를 참고해 주세요.

> 참고: 이미지 사이즈를 변경할 경우 `[![이미지_설명](이미지 경로){:height="??%" width="??%"}](이미지 경로)` 와 같이 사용하실 수 있습니다.

## 3. 태그 등록 방법
태그는 `/_tags/` 폴더에 `태그명.md` 파일을 만든 후

```
---
name: 태그명
title: 태그에 대한 간략한 설명
image: 태그 이미지가 있다면 추가. 없을 경우 넣지 않아도 됨.
---
```

다음과 같은 형식에 맞도록 작성해 주시면 됩니다.
