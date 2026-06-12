# keunson 다운로드

**keunson(큰손탐지기)** — 스트리머를 위한 시청자 후원 분석 프로그램.
투네이션·펀네이션·유튜브 후원을 실시간으로 모아 큰손을 자동 감지하고, 방송 중에도 화면 위에 입장 알림을 띄워줍니다.

## 📥 다운로드

👉 **[최신 버전 다운로드 (Releases)](https://github.com/saguo-495/keunson-releases/releases/latest)**

| 운영체제 | 파일 |
|----------|------|
| Windows | `keunson-Setup-x.x.x.exe` |
| macOS (Apple Silicon) | `keunson-x.x.x-arm64.dmg` |

## 🔧 설치 안내

### Windows
1. `keunson-Setup-x.x.x.exe` 다운로드 후 실행
2. 파란색 **"Windows의 PC를 보호했습니다"** 창이 뜨면:
   **"추가 정보"** 클릭 → **"실행"** 클릭
   (코드 서명 인증서를 준비 중이라 뜨는 안내이며, 앱은 안전합니다)
3. 설치 완료 후 바탕화면의 keunson 아이콘 실행

### macOS
1. `.dmg` 다운로드 후 열어서 keunson을 **Applications**로 드래그
2. **"keunson이 손상되었기 때문에 열 수 없습니다"** 경고가 뜹니다.
   이건 앱이 손상된 게 아니라, 코드 서명이 없는 앱을 인터넷에서 받으면 macOS가 자동으로 막는 것입니다.
   아래 한 줄로 해제할 수 있습니다:
   - **터미널**(응용프로그램 → 유틸리티 → 터미널) 실행 후 다음을 붙여넣고 엔터:
     ```
     xattr -cr /Applications/keunson.app
     ```
   - 이제 keunson을 더블클릭하면 정상 실행됩니다.
   - ⚠️ "휴지통으로 이동"을 누르면 앱이 삭제되니, 위 명령을 먼저 실행해주세요.

> 코드 서명 인증서가 적용되면 위 과정 없이 바로 실행됩니다 (준비 중).

## 💬 문의

- 문의: keunsontamjigi@gmail.com
