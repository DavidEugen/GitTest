# GitTest


## GitRepoasitory 생성 방법

### 1. Git Remote Repository 생성 
* Github에서 진행

### 2. Local 기존 프로젝트 (생성 혹은 생성)   

### 3. git Repository 연결
* 기존 Local 프로젝트에 git 연결

```
cd [프로젝트 경로]
git init
git remote add origin [원격주소]
git pull origin [브랜치명]
```

* git 연결후 IDE에 따라 Refresh 필요프로젝트를 닫았다 열어야 플러그인 적용되기도 함.


## Fork 방법
* egov의 저장소에 직접 코드를 수정할 권한이 없기에 구현 코드를 추가 할 수 없다.
* 이에 fork는 자신의 저장소로 복사하여 이를 반여할 수 있게 요구할 수 있는데, 이것이 PR(Pull Request)이다.

### 1. Fork 하기
* egov의 원하는 저장소의 우측 상단에서 포크 버튼을 눌러 내 저장소로 fork 한다.


## Clone 방법
### 1. Clone 하기
* 자신의 저장소에서 clone 주소를 복사하여 Local에서 clone 한다.

```
git clone #[fork한 자신의 원격 저장소 주소]
```

### 2. 자신이 작업할 브랜치를 생성한다.

```
git checkout -b [생성할 브랜치 이름]
```

### 3. IDE로 Import 하기
* clone한 프로젝트를 IDE로 연다.



## Commit
```
git status #변경된 파일 확인
git add -A(또는 .) #변경된 전체 파일을 한번에 반영
git commit -m "메시지" #작업한 내용을 메시지에 기록
```

## Push
```
git push origin [브랜치명]
```


## PullRequest
* Pull Request는 코드리뷰 요청을 보낼 때 사용
### 1. 자신이 코드를 작성한 원격 저장소의 브랜치에서 Compare & pull request 버튼을 통해 메세지와 함께 요청을 보낸다.

