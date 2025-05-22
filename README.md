## 프로그래머스 과제

---

`CLI`를 사용하여 `GITHUB`에 프로젝트 올리기

```
git init //.git 생성(새로운 저장소 생성)

git add 파일명 // 파일을 stage에 올림
git add . //수정 및 생성한 모든 파일을 stage에 올림

git commit -m "[생성] taks.html,README.md,.gitIignore"
//커밋(메세지)
git commit -am "메세지"
//스테이징과 커밋(메세지)

git remote add origin https://github.com/kimym98/task-day1.git
//원격저장소와 git연결결

git push origin main
//원격저장소로 main 브랜치 PUSH
```

---

### 내용 정리

GIT

1. GUL
2. CLI

이전 버전 불러오기

1. Soft : 코드를 지우지 않고 버전변경
2. Hard : 코드를 지우고 버전변경

```
git merge (branch name) //병합(merge)
git branch //브랜치 목록
git branch -D (branch name) // 브랜치 삭제

git log // history
git --oneline

//버전 되돌릴 때
git reset --soft 히스토리 해시값
git reset --hard 히스토리 해시값

//branch 변경
git checkout (branch name)

//git 설정 파일 열기
git config --global -e  git

```
