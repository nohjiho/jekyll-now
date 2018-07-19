---
layout: post
title: "git 명령어 모음"
comment: true
---

# 깃 명령어 모음

- git ssl 설정
git config --global http.sslVerify false

- 이름 지정
git config --global user.name "이름"
git config user.email "email 주소"

- 깃 상태확인
git status

- 깃 로컬 레파지토리 추가
git add *

- 깃 로컬레파지토리 커밋
git commit -m "코멘트"

- 깃허브 푸쉬
git push

- 변경분 update(fetch + merge)
git pull origin master