# git_test
git_test


원격저장소로부터 내려받기: fetch
내려받은 데이터를 병합: merge
하지만 이 둘을 함께 처리하는 명령은 pull

// 수정했지만 아직 스테이지에 추가하지 않은 파일을 되돌릴 때,
git checkout -- 파일명
// 수정했고 스테이지에 추가한 파일을 다시 스테이지에서제거 할 때,
git reset HEAD 
// 수정했고 로컬저장소에 commit 한 파일을 되돌릴 때,
git fetch origin
git reset --hard origin/master

git add aa.txt
git commit
git push
-------
git fetch 
git merge orgin/master

// remote 파일과diff
git diff origin/master -- 로컬패스

git stash list
git stash drop
git stash clear

