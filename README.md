# 셀비ai 공식 다운로드

사이트: https://selvi.kr

[Windows 64비트 다운로드](https://github.com/cineraria01/selvi_app/releases/latest/download/selvi-windows-amd64.zip) · [macOS Apple Silicon 다운로드](https://github.com/cineraria01/selvi_app/releases/latest/download/selvi-darwin-arm64.zip)

같은 버튼에서 항상 최신 공개 버전을 받습니다. 설치 후에는 프로그램이 자동으로 업데이트됩니다.

[최신 릴리스](https://github.com/cineraria01/selvi_app/releases/latest) · [업데이트 내역](https://selvi.kr/updates) · [SHA-256 체크섬](https://github.com/cineraria01/selvi_app/releases/latest/download/checksums.txt)

- **macOS (Apple Silicon)**: `selvi-darwin-arm64.zip`을 완전히 풀고, 만들어진 일반 폴더 안에서 `Launch Selvi.command`를 두 번 클릭합니다. `selvi.app`과 실행 도우미는 같은 폴더에 두세요. 터미널로 실행하려면 `sh`와 공백 한 칸을 입력하고 `Launch Selvi.command`를 터미널 창으로 끌어다 놓은 뒤 Enter를 누릅니다. 계속 차단되면 시스템 설정 → 개인정보 보호 및 보안 → 그래도 열기를 확인하세요. 자세한 안내는 https://selvi.kr/download 에 있습니다.
- **Windows (64비트)**: `selvi-windows-amd64.zip`을 풀고 `selvi.exe`를 실행합니다. `v0.1.64` 이전 공개본 ZIP 이름은 `sellpick-windows-amd64.zip`입니다. WebView2와 FFmpeg/ffprobe 등 미디어 도구의 준비 상태는 앱 설정에서 확인합니다.
- GitHub의 “Source code” ZIP은 앱 설치 파일이 아닙니다.

앱은 새 버전을 확인하고 Ed25519 서명과 SHA-256을 검증한 뒤 안전하게 교체합니다. 작업·저장이 끝나면 자동 재시작하거나 설정에서 저장 후 재시작할 수 있습니다. 프로젝트와 설정은 앱 밖에 보관됩니다.

현재 macOS 앱은 ad-hoc 서명이며 Apple Developer ID 공증은 적용되지 않았습니다. Windows EXE는 Authenticode 서명과 타임스탬프를 적용합니다. 업데이트 무결성 서명과 OS 코드 서명은 별개입니다.

`selvi-darwin-arm64.app.zip`은 기존 앱의 자동 업데이트 호환용입니다. 직접 내려받을 때는 위의 `selvi-darwin-arm64.zip`을 사용하세요.

이 저장소는 앱 배포 전용입니다. 소스 코드는 포함하지 않습니다.
