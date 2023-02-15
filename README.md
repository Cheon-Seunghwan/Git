# Git
터미널 깃 사용법

터미널에서 올리고 싶은 디렉토리로 먼저 들어가기

1. 깃 시작 - 맨 처음 프로젝트 시작할 때 올리는 것?
git init
2. 깃 추가
모든 파일
git add .
원하는 파일
git add 파일이름.확장명
3. 깃 커밋 이름 설정
git commit -m "커밋 이름"
4. 깃 연결
git remote add origin 저장소 링크
5. push
git push origin master (main)
6. 이름/토큰 입력
7. 업데이트 - git init 필요 없음
git add . - 변경 사항 확인
git commit -m "커밋 이름"
git push origin master
8. 과거의 커밋에 상관없이 현재의 커밋으로 덮어쓰기 가능
git push origin master --force


기타 사항
1. 깃 연결 상태 확인
git remote -v
2. 깃 상태 확인
git status
3. 연결 삭제
git remote remove origin 
4. 브랜치 변경
git branch -m [현재 branch name] [바꾸고싶은 branch name]
