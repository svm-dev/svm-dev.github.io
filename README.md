# svm-dev.github.io
스타십벤딩머신 기술 블로그

## 블로그에 게시글 작성 방법
> 아래 사항대로 수정한 뒤 커밋하신 뒤 `master`로 푸시하시면 반영이 됩니다.

0. 먼저 멤버를 등록하지 않았다면 멤버를 추가 해야 한다. [members.yml](https://github.com/svm-dev/svm-dev.github.io/blob/master/_data/members.yml)에 작성자를 추가한다
- 실제 보여지는 페이지는 [People](http://svm-dev.github.io/people/) 이곳에서 확인할 수 있다.

1. `_posts` 디렉토리 안에 게시글을 추가한다. 게시글의 이름은 날짜-제목 순으로 하고 `-`를 이용해서 단어를 이어서 서술한다.

2. [기술 블로그 오픈](https://raw.githubusercontent.com/svm-dev/svm-dev.github.io/master/_posts/2016-05-16-welcome-to-svm.md)을 참고해서 게시글을 작성한다
- 상단에 헤더 부분에 대한 `layout`, `title`, `date`, `categories`, `author` 를 작성한다.
`date`에 대해서는 현재 날짜와 시간을 기준으로 서술한다. `date`의 값이 만약 미래시점의 날짜, 시간이라면 게시글이 나타나지 않을 수도 있으므로 주의한다

```ruby
layout: post                        # layout을 post로 지정해야 함
title:  "기술 블로그 오픈"              # 게시글 제목
date:   2016-05-16 09:00:00 +0900   # 날짜 시간
categories: normal                  # 카테고리는 아직 분류하지 않으나 주제별로 작성 요구(ex android, web, ruby, python, rails 등)
author: "suhanlee"                  # member 로 추가시 상위 이름
```