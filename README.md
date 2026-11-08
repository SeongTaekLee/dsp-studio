# DSP Studio

> **프로토타입** — SAP Datasphere CLI의 활용 범위를 보여주기 위한 시연용 프로그램입니다. 정식 지원 도구가 아니므로 운영 테넌트에서 변경 작업을 하기 전에는 결과를 꼭 확인하세요.

SAP Datasphere CLI(`@sap/datasphere-cli`)가 어디까지 할 수 있는지 보여주는 Windows 데스크톱 앱입니다.
화면의 모든 동작은 CLI 명령으로 실행되고, 실행된 명령은 하단 **CLI 콘솔**에 그대로 보입니다.

## 다운로드

최신 버전 **1.14.0**: [DSP-Studio-1.14.0-portable.exe 바로 받기](https://github.com/SeongTaekLee/dsp-studio/releases/download/v1.14.0/DSP-Studio-1.14.0-portable.exe)

이전 버전은 [Releases](../../releases)에 있습니다. 설치 없이 더블클릭으로 실행됩니다.

## 필요한 것

따로 설치할 것은 없습니다. Node.js도 필요 없습니다.

처음 실행하면 홈 화면의 **CLI 자동 설치** 버튼을 누르세요. SAP 공식 npm 패키지(`@sap/datasphere-cli`)를 받아 exe 옆 `DSP Studio Data\cli` 폴더에 설치합니다. 인터넷(registry.npmjs.org) 연결이 필요하며, 회사 프록시 환경이면 `HTTPS_PROXY` 환경변수가 필요할 수 있습니다.
SAP Datasphere CLI는 SAP Freeware 라이선스를 따르므로 이 배포본에 포함하지 않고, 각 PC가 SAP 패키지에서 직접 받습니다.

## 참고

- 설정, 기록, 암호화된 시크릿, 설치된 CLI는 exe 옆의 `DSP Studio Data` 폴더에 저장됩니다. exe를 옮길 때는 이 폴더도 함께 옮기세요.
- 코드 서명이 없어 처음 실행할 때 Windows SmartScreen 경고가 뜰 수 있습니다. "추가 정보 → 실행"을 누르세요.
- 앱은 네트워크 포트를 열지 않습니다.
