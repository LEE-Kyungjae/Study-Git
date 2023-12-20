# git_study
깃을 사용을 하면서 긴가민가하는 부분이많다.
되면 말고 안되면 그때 찾아보고 이러다보니 한번제대로 아는것이 좋을거같아 정리해보려고한다.

Git 기본 기능:
저장소 초기화 및 복제:

git init: 새로운 Git 저장소 초기화
git clone <repository_url>: 원격 저장소를 로컬로 복제
변경 사항 추적:

git status: 변경된 파일 확인
git diff: 수정된 내용 확인
git add <file>: 변경 사항 스테이징
git reset <file>: 스테이징 취소
커밋:

git commit -m "Commit message": 스테이징된 변경 사항을 커밋
브랜치:

git branch: 브랜치 목록 확인
git checkout <branch>: 다른 브랜치로 이동
git checkout -b <new_branch>: 새 브랜치 생성 및 이동
원격 저장소:

git remote -v: 연결된 원격 저장소 확인
git push <remote> <branch>: 로컬 변경 사항을 원격 저장소로 푸시
git pull <remote> <branch>: 원격 저장소에서 변경 사항을 가져오기
Git 활용 팁:
로그 확인:

git log: 커밋 이력 확인
git log --oneline: 간략한 형식으로 커밋 이력 확인
git log --graph --all --decorate: 브랜치와 병합 정보를 포함한 그래프 형태로 확인
병합과 리베이스:

git merge <branch>: 현재 브랜치에 다른 브랜치를 병합
git rebase <branch>: 현재 브랜치에 다른 브랜치를 리베이스
태그 추가:

git tag <tag_name>: 현재 커밋에 태그 추가
git tag -a <tag_name> -m "Tag message": 주석과 함께 태그 추가
커밋 수정:

git commit --amend: 최근 커밋을 수정
.gitignore 파일:

.gitignore 파일을 사용하여 Git에서 무시할 파일 및 디렉토리 목록 지정
Stash:

git stash: 현재 변경 사항을 일시적으로 저장
git stash apply: 저장한 변경 사항을 다시 적용
Interactive Rebase:

git rebase -i HEAD~n: 최근 n개의 커밋에 대한 대화형 리베이스
Git Alias:

자주 사용하는 명령어에 별칭을 지정하여 간편하게 사용할 수 있음
GitHub 및 GitLab 활용:

이슈 트래킹, 코드 리뷰, 프로젝트 관리 등을 위해 GitHub 또는 GitLab과 같은 플랫폼과 통합하여 사용
Git GUI 도구 사용:

SourceTree, GitKraken과 같은 GUI 도구를 사용하여 Git을 시각적으로 관리
이러한 기능과 팁은 Git을 효과적으로 사용하는데 도움이 될 것입니다. Git은 강력하면서도 다양한 기능을 제공하므로 필요에 따라 적절한 기능을 선택하여 사용하면 됩니다.
