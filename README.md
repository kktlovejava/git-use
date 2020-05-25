# git-use
git-use
깃 설치
1. window

https://gitforwindows.org/

2. Linux

sudo dnf install git-all

3. ubuntu

sudo apt install git-all

깃 최초 설정

git config --global user.name "성명"

git config --global user.email "깃 이메일"(123456@naver.com 이면 12345로 이메일 작성)

ex) git config --global user.email "12345"

깃 설정 후 

git remote add origin "주소" 입력 후 

fatal: remote origin already exists. 오류 이면 상단의 깃 최초 설정이 잘못됨.

git remote rm origin 입력 후 다시 깃 최초 설정

깃 자주 사용하는 명령어

git init - 깃 생성

git add * - 변경된 모든사항 스테이징

git commit -m “{변경 내용}”  - 커밋

git push origin master  - 원격으로 보내기

git remote add origin {원격서버주소} - 원격 저장소 추가

git status - 변경사항 확인

git log - 모든 커밋로그 확인

git log -3 - 최근 3개 커밋로그 확인

git log --pretty=oneline - 각 커밋을 한 줄로 표시

git reflog - reset 혹은 rebase로 없어진 과거의 커밋 이력 확인
