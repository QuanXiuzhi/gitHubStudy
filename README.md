# gitHubStudy

#GUI 환경에서 git 사용하기
## 1. git 설치
https://git-scm.com/

git 명령어
```sh
$ git init
```
빈 로컬 git 저장소가 생성된다
[.git] 폴더가 생성된다.
```sh
$ git config --global user.email 'quanxiuzhi3@gmail.com'
$ git config --global user.name "JEON"
```
버전 관리를 위해 내 정보를 등록한다.
```sh
$ git add README.txt
```
커밋에 추가할 파일을 선택(add)한다.
```sh
$ git commit -m 'add README.txt'
```
코멘트(-m = message)를 추가해 파일을 커밋한다.

```sh
$ git log
```
지금까지 한 커밋을 확인한다.
```sh
$ git checkout 28619b6266f27ed62d148ed2250ee218b5dbef58
```
특정 버전으로 돌아가기
```sh
$ git checkout -
```
최신 버전(HEAD)로 돌아가기

## 2. 소스트리 설치
https://www.sourcetreeapp.com/

## 3. Visual Studio 설치
Visual Studio에는 git 플러그인이 기본으로 제공된다.
