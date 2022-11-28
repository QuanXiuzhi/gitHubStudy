# CLI
## 로컬에서 git 사용
### 1. git 설치
https://git-scm.com/

```sh
$ git init
```
=> 빈 로컬 git 저장소가 생성된다. [.git] 폴더가 생성된다.
```sh
$ git config --global user.email 'quanxiuzhi3@gmail.com'
$ git config --global user.name "JEON"
```
=> 버전 관리를 위해 내 정보를 등록한다.
### 2. git commit
```sh
$ git add README.txt
```
=> 커밋에 추가할 파일을 선택(add)한다.

```sh
$ git commit -m 'add README.txt'
```
=> 코멘트(-m = message)를 추가해 파일을 커밋한다.

```sh
$ git commit --amend
```
=> 빠진 파일/커밋 메시지 수정 등 사소한 수정이 있을 때 --amend 옵션을 사용하면 이전 커밋을 덮어씌운다.

```sh
$ git log
```
=> 지금까지 한 커밋을 확인한다.

### 2. git checkout
```sh
$ git checkout 28619b6266f27ed62d148ed2250ee218b5dbef58
```
=> 특정 버전으로 돌아가기(checkout)

```sh
$ git checkout -
```
=> 최신 버전(HEAD)로 돌아가기(checkout)

```sh
git checkout -- <file name>
```
=> 워킹 디렉토리에 있는 파일의 수정 사항을 이전 커밋으로 되돌린다. 수정한 내용이 전부 사라지기 때문에 조심해서 사용하자.

## 원격(remote) 저장소
### 1. 원격 저장소 사용하기
```sh
$ git clone <remote>
```
```sh
$ git remote <remote 단축명> <remote>
$ git remote githubStudy https://github.com/QuanXiuzhi/githubStudy.git
```

### 2. git push
```sh
$ git push <remote> <branch>
```

### 3. git fetch / git pull
```sh
$ git fetch <remote>
$ git fetch https://github.com/QuanXiuzhi/githubStudy.git
$ git fetch githubStudy 
```
```sh
$ git pull <remote>
```
=> remote 에 url 전체를 써도 되고, remote 단축명을 사용할 수도 있다.


# GUI 환경에서 git 사용하기
### 1. 소스트리 설치
https://www.sourcetreeapp.com/

### 2. Visual Studio 설치
Visual Studio에는 git 플러그인이 기본으로 제공된다.


<br><br>
[참고]
> https://git-scm.com/book/ko/v2