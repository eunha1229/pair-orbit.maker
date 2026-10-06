# PAIR ORBIT MAKER v16.3.4

## v16.3.4
- 캐릭터 높이 정렬을 '본문 섹션만'이 아니라 카드 상단부터 누적 정렬하도록 수정
  - 이름/헤더
  - 캐치프레이즈
  - AGE/HEIGHT/BUILD
  - 키워드
  - 이미지 영역
  - 특징 및 외관
  - 동물화
  - 소품/상징물
  - 필수/NG
- 따라서 한쪽 상단 텍스트가 한 줄 더 차지해도 아래 모든 섹션 시작선이 맞음
- 전신 이미지를 absolute + translateX 방식에서 일반 flex 배치로 변경
  - html2canvas가 PNG 저장 시 좌표를 다르게 해석하던 원인을 제거
  - Full Body X는 relative left 값으로 그대로 지원
  - 발끝 정렬/신장 비례/Full Body Scale 유지
- PNG 캡처의 강제 scrollY 보정을 제거하고 저장 직전 레이아웃을 재계산

PAIR ORBIT MAKER
made by @2by4_JourNey
