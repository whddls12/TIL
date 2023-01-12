# Markdown

*텍스트 기반 마크업 언어*

    1. 헤딩 (#)
    2. 리스트  
    3. 코드블럭
    4. 링크 
    5. 이미지
    6. 텍스트 강조
    7. 수평선

# Git/Github
“분산” 버전 관리 프로그램.

히스토리 열람 가능, 개인 작업 수정 후 서버 등록

## Repository

디렉토리를 버전 관리하는 저장소

.git 에 버전 관리에 필요한 모든 것이 들어있음.

**커밋**(Commit)한다 : **특정 버전으로 남긴다.**

>Working Directory

작업 영역
>Staging Area

커밋으로 남기고 싶은 내용을 모아두는 곳
>Repository 

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
