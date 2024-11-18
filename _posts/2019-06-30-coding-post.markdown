---
layout: post
title:  "Django로 게시판 만들기"
description: Django Web Framework를 사용해 게시판 만들기 프로젝트!
date:   2024-09-30 21:03:36 +0530
categories: Python Django
---
방학 기간 동안 웹 프레임워크를 경험해 보는 것이 중요하다고 생각해 개인 프로젝트를 진행해 보았다.

```python
from django.urls import path

from . import views

urlpatterns = [
    path('', views.index, name='index'),
    path('<int:question_id>/', views.detail, name='detail'),
]
```

다음과 같이 url pattern을 지정할 수 있다.

```scss
body {
	font-family: 'Nunito Sans', sans-serif;
	line-height: 1.5em;
	margin: 0;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}
```
commit 요청을 위한 수정 문구입니다. onsectetur adipisicing elit. Aliquam rerum, ratione impedit necessitatibus facere soluta odio repellat asperiores neque! Sunt iusto quia suscipit amet inventore eum, vel molestiae reiciendis alias.