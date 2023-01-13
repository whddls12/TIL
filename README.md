# Markdown
    텍스트 기반 마크업 언어
>### 1. 헤더
    # "text"
    ## "text"
    ...
    ###### "text"

>### 2. 리스트
#### 순서있는 목록
    숫자와 점 사용
#### 순서없는 목록
    *,+,- 사용
>### 3. 코드블럭
    ```
    여기에 코드 넣기
    ```
>### 4. 링크
    [Title](url)
[Title](link)

>### 5. 이미지
    ![이미지](img_url)
![이미지](img_url)
>### 6. 텍스트 강조
    *one*
    _two_
    **three**
    __four__
    ~~five~~

*one*
_two_
**three**
__four__
~~five~~
>### 7. 수평선
    * * *
    ***
    *****
    - - -
    -------

* * *
***
*****
- - -
----------


# Git/Github
    “분산” 버전 관리 프로그램.

* 히스토리 열람 가능

* 개인 작업 수정 후 서버 등록

## Repository

    디렉토리를 버전 관리하는 저장소

* .git 에 버전 관리에 필요한 모든 것이 들어있음.

* **커밋**(Commit)한다 : **특정 버전으로 남긴다.**

> ### Working Directory

작업 영역
> ### Staging Area

커밋으로 남기고 싶은 내용을 모아두는 곳
> ### Repository 

저장소
![git concept](https://miro.medium.com/max/640/1*zpvd5fjZAFGsVAEsvMGKxA.webp)

## 명령어

`git init` : 로컬 저장소 생성

`git add` : working directory → Staging Area

`git commit` : Staging Area → Repository

`git status` : 현재 상태 확인

`git push ` : 로컬 저장소에서 원격 저장소로 옮겨줘

`git log` : 커밋한 기록 열람

`git clone` : 깃허브에서 pc로 파일 복사

    zip으로 다운로드받으면 .git 없음 (최신파일만 복사)
git 명령어에 --help 옵션 추가하면 설명서 볼 수 있음

### git add 한 내용을 취소하는 방법
1. 한번도 커밋하지 않았을 때
    </br> git rm --cached <file>
2. 첫 커밋 이후
    </br> git restore --staged <file>


    ### [git rm --cached, git restore --staged, git reset의 차이점](https://stackoverflow.com/questions/65434544/whats-the-difference-between-git-rm-cached-git-restore-staged-and-gi)

### commit message 수정
- git commit -amend
- commit message 수정 후 esc 클릭, :wq 입력

### .gitignore
* repository나 staging area에 추가되지 말아야 하는 폴더나 파일을 정의하는 파일

## Vim 간단사용법
    a,o,i : 입력모드
    esc 누르면 명령모드
    :w 저장
    :q 닫기
    :wq 저장하고 닫기
    :q! 저장하지 않고 닫기

