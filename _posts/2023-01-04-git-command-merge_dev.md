---
title: git merge --squash 브랜치명
author: JeromeMi
date: 2023-01-04 20:22:00 -0500
categories: [Blogging, GitHub]
tags: [Git command, Study]
---

> 
{: .prompt-danger }


## Set up Githup

### HOW To GIT MERGE

git switch main
git merge --squash 브랜치명
git commit -m '메세지'

1. git switch main
2. git merge --squash 브랜치명
3. git commit -m '메세지'
4. squash and merge 하는 법은 그냥 --squash 옵션을 추가하면 끝입니다. 
    브랜치에서 만들어놨던 많은 commit 을 다 합쳐서   하나의 commit으로 main 브랜치에 생성해줍니다.

### 그냥 merge 했을 경우

merge --squash 했을 경우 
결과는 둘 다 똑같은데 한 놈은 선으로 이어져있고 한 놈은 텔레포트했을 뿐입니다. 

1. 브랜치 100개 만들어놨는데 일반 merge를 잔뜩 해놓으면 나중에 git log 그래프가 매우 복잡해질 수 있습니다.
그게 싫으면 squash 해보십시오. 또는 rebase 해도 마찬가지로 해결가능합니다. 


어떻게 merge 할 지 판단하기 힘들어요 :

! 2#@$@%@%@62

1. 브랜치 새로 하나 만들어서 commit 몇번 한 다음 main 브랜치에 squash and merge  

2. 브랜치 새로 하나 만들어서 commit 몇번 한 다음 main 브랜치로 rebase and merge 

3. 잘 합쳐져서 이제 쓸모없어진 브랜치는 제거 

```git merge 방법

[bemywingman-homepage]: https://bemywingman.github.io
