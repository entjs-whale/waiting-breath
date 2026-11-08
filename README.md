# 기다리는 숨

새끼 향고래의 눈으로, 깊은 바다로 내려간 엄마를 기다리는 장면.
숨의 바다 · 화면구성 컨셉 v1.14 · 실사 형태 + 양모펠트

- 양모펠트 향고래 원작: humming whales
- 기획·구성: whales.breathe

👉 https://entjs-whale.github.io/waiting-breath/

## 관람 환경
| 기기 | 필요한 환경 | 권장 브라우저 |
|---|---|---|
| PC (윈도우·맥) | 최신 버전 브라우저 (맥 Safari는 macOS 26 이상) | Chrome, Edge |
| 아이폰 | iPhone 11 이후 모델, iOS 26 이상 | Safari |
| 아이패드 | iPad 8세대·Air 3세대·mini 5세대·Pro(2018) 이후, iPadOS 26 이상 | Safari |
| 안드로이드 | Android 12 이상, 퀄컴(스냅드래곤)·ARM(Mali) 그래픽 칩 | Chrome |

- 카카오톡·인스타그램·네이버 앱 안에서 열리는 브라우저에서는 보이지 않습니다. ‘다른 브라우저로 열기’를 눌러 주세요.
- 삼성 인터넷, 안드로이드 Firefox, 리눅스에서는 열리지 않을 수 있습니다.
- 엑시노스 칩(Xclipse 그래픽)을 쓰는 일부 갤럭시는 Chrome이어도 열리지 않습니다.
- 헤드폰을 쓰면 소리의 방향과 깊이가 들립니다.
- 한 번 연 뒤 공유 → ‘홈 화면에 추가’를 하면 인터넷 없이도 열립니다.

## 파일
- `index.html` — 작품 페이지
- `sw.js` — 첫 방문 때 작품을 기기에 저장해, 이후 인터넷 없이 열리게 함
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` — 홈 화면 아이콘과 전체 화면 실행 설정

## 업데이트할 때
`index.html`을 바꾸면 `sw.js` 첫 줄의 `VERSION` 값도 바꿔 주세요(예: v1.14 → v1.15).
그래야 아이패드가 인터넷에 연결됐을 때 새 버전을 받아 저장합니다.
