# learning_git
깃허브 공부하기

## git 명령어

```
git init => 저장소 생성
git status => 깃 상태확인
git add filename => 작업파일 스테이지에 올리기
git commit -m "text" => 스테이지에 있는 파일 커밋하기
git rm filename => 파일삭제
git branch => 현재 브랜치 상태확인
git branch branchname => 브랜치 생성
git checkout branchname => 해당 브랜치로 이동
git merge branchname => 브랜치 병합 (해당 브랜치 위치에서 병합할 브랜치명 작성)
git push (origin) (main) => 연결된 git origin으로 (main or master 헤드) 푸시
git log => log확인
git log --graph --all --decorate => log확인시 같이 적용하면 좋은 옵션들

```

📌 git remote add origin (repository link) => 생성한 vscode 파일에 저장소 연결하기

📌 .gitignore => 커밋하지 않을 파일들 작성하기

📌 .gitignore를 작성하고 스테이지에 add 할 경우 git add. 사용

"메인 작업 완료 후 서브 브랜치 생성하고 커밋, 푸시 이후 merge로 병합."
