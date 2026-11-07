# 기다리는 숨

새끼 향고래의 눈으로, 깊은 바다로 내려간 엄마를 기다리는 장면.
숨의 바다 · 화면구성 컨셉 v1.9 · 실사 형태 + 양모펠트

- 양모펠트 향고래 원작: humming whales
- 기획·구성: whales.breathe

## 파일
- `index.html` — 작품 페이지
- `sw.js` — 첫 방문 때 작품을 기기에 저장해, 이후 인터넷 없이 열리게 함
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` — 홈 화면 아이콘과 전체 화면 실행 설정

## 업데이트할 때
`index.html`을 바꾸면 `sw.js` 첫 줄의 `VERSION` 값도 바꿔 주세요(예: v1.9 → v1.10).
그래야 아이패드가 인터넷에 연결됐을 때 새 버전을 받아 저장합니다.
