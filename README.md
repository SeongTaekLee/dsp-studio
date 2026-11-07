# DSP Studio

SAP Datasphere CLI(`@sap/datasphere-cli`)가 어디까지 할 수 있는지 보여주는 Windows 데스크톱 앱입니다.
화면의 모든 동작은 CLI 명령으로 실행되고, 실행된 명령은 하단 **CLI 콘솔**에 그대로 보입니다.

## 다운로드

[Releases](../../releases/latest)에서 `DSP-Studio-<버전>-portable.exe`를 받으세요. 설치 없이 더블클릭으로 실행됩니다.

## 필요한 것

1. Node.js (https://nodejs.org, LTS)
2. SAP Datasphere CLI

```bash
npm install -g @sap/datasphere-cli
```

## 참고

- 설정, 기록, 암호화된 시크릿은 exe 옆의 `DSP Studio Data` 폴더에 저장됩니다. exe를 옮길 때는 이 폴더도 함께 옮기세요.
- 코드 서명이 없어 처음 실행할 때 Windows SmartScreen 경고가 뜰 수 있습니다. "추가 정보 → 실행"을 누르세요.
- 앱은 네트워크 포트를 열지 않습니다.
