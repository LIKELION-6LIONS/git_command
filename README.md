# 깃허브 터미널 명령어

## 터미널 명령어
현재 디렉토리 위치
```
pwd
```
디렉토리 이동
```
cd 디렉토리명
```

## Git 
깃 생성
```
git init
```
스테이징 가능 여부 확인
```
git status
```

커밋 내역 확인
```
git log
```


## Git Staging (Add)
폴더 내 모든 파일 스테이징
```
git add .
```
특정 파일만 스테이징
```
git add 파일명
```

## Git Commit 
커밋메시지와 함께 커밋(스테이징 된 모든 파일 커밋)
```
git commit -m "커밋메시지"
```
특정 파일만 커밋
```
git commit 파일명 -m "커밋메시지"
```

## Branch
branch 생성
```
git branch 브랜치명
```

branch 변경
```
git checkout 브랜치명
```

branch 삭제
```
git branch --delete 브랜치명
```

현재 branch 위치
```
git branch
```

merge (main에 머지할 때)
```
git merge 병합할브랜치명
```
