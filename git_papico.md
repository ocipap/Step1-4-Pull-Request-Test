# git? github?

git : DVCS(분산 버전 관리 시스템)  
github : git repogitory 를 인터넷에에서 제공하는 단순한 호스팅 서비스

# git 의 대표적인 저장소 4가지

-   working tree (작업 디렉토리)
-   stage
-   local repository
-   remote repository

# git repository 만들기

1.  git init 명령어
2.  git clone \[remote repository address\]  
    하면 `.git` 폴더가 생김

# git add

working tree 에 있는 파일을 stage 에 올리는 작업

# git commit

stage에 변경사항을 local repository 에 옮기는 작업

# git patch

remote repository와 local repository 동기화

# git pull

working tree, stage, local repository 동기화

# git checkout

HEAD의 위치를 바꿈

# git merge

두 커밋을 합침

# git rebase

해당 브렌치의 commit 를 통째로 이어 붙임

# 오늘 중요한 내용

1.  커밋을 하면 무조건 남는다.
2.  브렌치는 단순 참조이다.
