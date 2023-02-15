# 터미널 깃 사용법
## 터미널에서 올리고 싶은 디렉토리로 먼저 들어가기

1. 깃 시작 - 맨 처음 프로젝트 시작할 때 올리는 것?
- git init
2. 깃 추가
- git add .
- git add 파일이름.확장명
3. 깃 커밋 이름 설정
- git commit -m "커밋 이름"
4. 깃 연결
- git remote add origin 저장소 링크
5. push
- git push origin master / main
6. 이름/토큰 입력
7. 업데이트
- git pull origin master / main
- git add .
- git commit -m "커밋 이름"
- git push origin master / main
8. 과거의 커밋에 상관없이 현재의 커밋으로 덮어쓰기 가능
- git push origin master / main --force


# 기타 사항
1. 깃 연결 상태 확인
- git remote -v
2. 깃 상태 확인
- git status
3. 연결 삭제
- git remote remove origin
4. 브랜치 확인
- git branch
5. 브랜치 변경
- git branch -m [현재 branch name] [바꾸고싶은 branch name]
6. 브랜치 default 변경
- git config --global init.defaultBranch [브랜치 이름]
