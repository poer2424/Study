# HOW TO GIT

[참고](https://urbanbase.github.io/dev/2021/01/15/GitCommand.html)

***

## pull

**remote repository에 저장된 최신 파일이 local repository에 병합됨**

> git pull {원격 저장소} {원격 브랜치}

* git pull origin master
  * 현재 작업중인 원격저장소의 master 브랜치를 가져옴

## add

**local repository에서 변경이 일어난 파일들을 스테이징함**

> git add {파일/폴더명}

* git add .
  * 변경이 일어난 파일 전부 스테이징

## commit

**변경내용저장**

>git commit {명령인자}

* git commit -m "message"
  * 스테이징 된 파일들 전부 "message" 메세지로 commit
* git commit -a
  * 신규파일을 제외한 변경사항을 스테이징 후 커밋
* git commit --amend
  * 이전 커밋 변경

## push

**commit한 파일들 remote repository에 업로드**

>git push {원격 저장소} {원격 브랜치}

* git push origin master
  * 현재 작업중인 원격저장소의 master 브랜치에 local repository 업로드
