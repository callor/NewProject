# git project 업로드 하기

## README.md 파일 만들기
* sublime text 도구를 사용할수 있고
* git bash shell 에서 : `touch README.md` 라는 명령으로 생성
* git에 project 를 `push(Upload)` 했을때 안내메시지등을 보여주는 파일
* mark down 문법을 사용하여 간단한 문서를 작성하기

## local folder 를 local Repository 로 생성하기
* bash shell `git init` 명령으로 생성
* `.git` 폴더를 생성하는 명령이다

## `.git 폴더`
* project 폴더에 작성된 여러 파일들을 압축하여 원격 Repository 에 push 하기 위해서 준비된 폴더
* git에 push 할때 사용하는 여러정보들을 보관하는 폴더

## 원격 Repository 생성하기
* `https://github.com` 로그인 한 후 Repository 생성하기
* `git remote add ... ` 명령문 복사 : `git remote add origin https://github.com/callor/NewProject.git`
* bash shell 에서 `Shift + insert` 키를 입력하여 붙여넣기

## `.gitignore` 생성하기
* `.gitignore` 파일은 원격 github 에 업로드되지 않아야 할 파일 정보를 등록하는 곳
* bash shell `touch .gitignore`

## 로컬 프로젝트 원격 Repository에 push 하기

* `git add .` : 로컬폴더 파일을 압축하여 .git 폴더에 저장하기 

* `git commit -m 커멘트` : 원격 Repository 에 push 하는 정보 설정
* `git push -u origin master`: 데이터 push 
