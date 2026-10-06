# PAIR ORBIT MAKER v16.3.3

## Fixes
- 전신 Scale을 CSS transform 확대가 아니라 실제 이미지 height 계산에 반영하도록 변경
  - 미리보기와 PNG에서 같은 크기로 렌더링
  - html2canvas에서 전신만 거대해지던 문제 제거
  - Full Body X / 신장 비례 / 발끝 정렬 유지
- 캐릭터 행 높이 정렬 로직 수정
  - 이전 버전의 `.detail:nth-of-type()` 선택자가 실제 DOM 구조와 맞지 않던 문제 수정
  - 같은 행의 캐릭터끼리 전신 영역, 특징 및 외관, 동물화, 소품/상징물, 필수/NG를 각각 독립적으로 높이 동기화
  - 본문 길이가 달라도 다음 섹션 시작선이 맞도록 처리
- PNG 저장 직전 실제 레이아웃을 다시 계산한 뒤 캡처

PAIR ORBIT MAKER
made by @2by4_JourNey
