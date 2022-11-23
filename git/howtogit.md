# HOW TO GIT

[참고](https://urbanbase.github.io/dev/2021/01/15/GitCommand.html)

***

## init

**git 초기화, git 경로지정**

>git init

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

## status

**현재 git 프로젝트에서의 파일 상태**

>git status

## rm

**파일지우기, 스테이징해제**

>git rm {파일명}
<br>
git rm --cached {파일명}



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

## log

**commit 목록 (옵션이 굉장히 많음) <br> git log --help로 자신에게 맞는 명령어 활용하기**

>git log

* git log --graph
  * log를 그래프형식으로 보여줌
* git log --all
  * 모든 branch 보기
* git log --oneline
  * commit 메세지 제목만 간단하게 보기


## git fetch -p 

* 로컬저장소를 최신정보로 갱신, 유효하지 않은 참조 제거

## git checkout -b <branch>, git push origin <branch>

* 새로운 브랜치 만들고 그 새로운 브랜치를 remote에 업데이트.

