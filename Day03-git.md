[깃허브] 뉘앙스 -> 날짜 및 시간 -> 변경사항

웹페이지 꾸미기, 잔디 관리(출첵.1일1커밋)

git init 설치 코드 : winget install --id Git.Git -e --source winget

- Staging Area: 변경 사항을 선택해 두는 공간. `git add`를 실행하면 변경 사항이 등록됨.
- git add . 현재 폴더의 모든 변경 사항 등록
- Commits: `git commit`으로 확정한 버전 기록이 저장되는 공간.
- git commit -m "버전" : 버전 관리
- git status : 저장소의 파일 상태를 확인함.

## Git 작업 순서

```text
폴더 생성
    ↓
git init
    ↓
Git이 관리 시작
    ↓
git add
    ↓
git commit
    ↓
git push
