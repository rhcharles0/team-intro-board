# Team Rules

전체 규칙:

- main 직접 push 금지
- 모든 변경은 issue 기반
- 모든 커밋 메시지에 issue 번호 포함
- 모든 작업은 feature branch 에서 진행
- PR 후 최소 1명 리뷰
- pull 사용 금지, fetch 후 직접 merge/rebase 판단

이슈 규칙:

- #1 저장소 초기 세팅
- #2 README 메인 페이지 작성
- #3 팀 규칙 문서 작성
- #4 팀원 A 소개 문서 작성
- #5 팀원 B 소개 문서 작성
- #6 추천 주제 1 문서 작성
- #7 추천 주제 2 문서 작성
- #8 수정 이력 테이블 추가
- #9 README 레이아웃 개선
- #10 충돌 해결

커밋 컨벤션 규칙:
[#이슈번호] docs: 작업 설명
[#이슈번호] chore: 작업 설명
[#이슈번호] fix: 작업 설명
[#이슈번호] merge: 작업 설명

브랜칭 전략:
main
└─ 항상 안정 상태

feature/<이슈번호>-<작업명>
└─ 작업용 브랜치

feature/3-team-rules
