1. 로컬 환경에 깃허브 계정 연동
2. 저장소 복사(Repository Clone)
3. 브랜치 생성(Github flow 전략에 따라)
** feature / fix 브랜치는 반드시 develop 브랜치로부터 딸 것!
4. 파일 추가/수정과 같은 작업 진행
5. git add [파일 위치] [파일명]
6. git commit -m [커밋 메세제]
** 커밋 메세지 작성시에는 사전에 정의한 컨벤션에 맞춰 작성
7. git push
8. (작업 완료 후) 깃허브에서 Pull Request 생성
- PR 제목
- 작업 내용
- Reviewer
- Assigner(담당자)
- (가능하다면) 태그
설정 후 Create
9. Slack에 노티
10. 작업 담당자 외 Reviewer들로부터 코드 리뷰 및 메세지 확인
11. Merge 진행 후 작업 브랜치 삭제(remote에서만 삭제되기 때문에 로컬은 자가 판단)
12. Slack에 노티 
13. (추가 작업 필요 시) 3번부터 반복