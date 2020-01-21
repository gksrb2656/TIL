# Git

1. git 시작하기

```sh
$ git init
```

이제부터 해당 디렉토리를 git으로 관리하겠다!



2. 상태 확인하기

```sh
$ git status
```



3. 스테이지에 올리기 ( add - commit - push >> 한 사이클 )

```sh
$ git add 파일명
$ git add . #스테이지에 올라가지 않은 모든 변경 사항들을 스테이지로 올리겠다.
```



4. 커밋하기(사진찍기)

```sh
$ git commit -m '메세지'
```



5. 기록 확인하기

```sh
$ git log
```



6. 리모트(원격저장소)를 등록하기

```sh
$ git remote add origin 원격저장소 주소
```



7. 파일 푸쉬하기(업로드하기)

```sh
$ git push origin master
```