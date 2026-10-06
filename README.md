# PAIR ORBIT MAKER v16.3.5

- v16.3.4의 fullbody flex 변경을 전부 롤백하고 v16.3.3의 정상 카드 배치를 복구했습니다.
- 오른쪽 캐릭터 카드/두상 이미지가 카드 밖으로 밀려나던 문제를 제거했습니다.
- 높이 정렬 방식을 min-height 추정에서 실제 section top 좌표 보정 방식으로 교체했습니다.
  - 전신/두상 영역
  - 특징 및 외관
  - 동물화
  - 소품/상징물
  - 필수/NG
  의 시작선을 같은 행 캐릭터끼리 직접 맞춥니다.
- PNG 저장 시 전신 이미지의 화면상 실제 x/y/width/height를 픽셀값으로 잠시 고정한 뒤 캡처합니다.
  저장 후 원래 스타일로 즉시 복원됩니다.
- PNG 캡처의 scrollY 보정을 제거했습니다.

PAIR ORBIT MAKER
made by @2by4_JourNey
