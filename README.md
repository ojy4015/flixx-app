바닐라 자바스크립트로 만든 연습용 영화 및 티비 안내 사이트 입니다.

github으로 저장하는 방법

처음으로 시작할 때

git --version

git init
git add .
git status
git commit -m "first commit"
git status
git remote add origin https://github.com/ojy4015/loopstudios.git
git branch -M main
git push -u origin main

변경되어 다시 저장할 때
git add .
git commit -m "second commit"
git push

git 초기화
 로컬 저장소의 .git directory를 삭제합니다.
rm -rf ./.git
