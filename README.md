# OMP Studio

[Oh My Pi (omp)](https://github.com/can1357/oh-my-pi) CLI 위에서 동작하는 한국어 데스크톱 에이전트 GUI입니다.
코딩과 게임 개발을 주 용도로 만들었고, 플러그인으로 레이아웃·옵션·기능을 바꿀 수 있습니다.

이 저장소는 **설치 파일 배포용**입니다. 소스 코드는 공개하지 않습니다.

## 설치

1. [Releases](../../releases/latest)에서 `OMP-Studio-Setup-<버전>.exe`를 받습니다.
2. 실행해서 설치합니다(Windows 10/11, 사용자별 설치, 설치 경로 선택 가능).
   코드 서명이 없어 SmartScreen 경고가 뜨면 **추가 정보 → 실행**을 누르세요.
3. 처음 실행 안내에 따라 omp CLI를 설치하고 모델 계정에 로그인합니다.

각 릴리스 설명에 설치 파일의 SHA256이 있습니다. PowerShell에서 확인:

```powershell
Get-FileHash .\OMP-Studio-Setup-<버전>.exe -Algorithm SHA256
```

## 주요 기능

- omp 세션 관리, 스트리밍 대화, 도구 카드, 승인/질문 창, 명령 팔레트, 작업 과정 접기
- 멀티 에이전트 워크플로우 편집기와 실행 실시간 보기
- 플러그인 시스템과 플러그인 스토어(앱 안에서 내려받기)
- 내장 터미널, 내장 브라우저, 파일 탐색기·편집기·Git 패널
- AI 앱 제어와 위험 등급별 자동 승인, 변경 기록과 되돌리기
- MCP 서버 관리·OAuth 로그인, 프로바이더 사용량 표시
- 휴대폰 원격(종단간 암호화 릴레이)
- 다크·라이트 테마

## 제거

Windows 설정 → 앱 → OMP Studio → 제거. 설정과 데이터(`%APPDATA%\omp-studio`)는 남으니 필요하면 직접 지우세요.
omp의 설정(`~/.omp`)은 OMP Studio와 별개입니다.

## 이용 조건

[`LICENSE.md`](LICENSE.md)를 보세요. 요약: 개인·업무용으로 무료로 쓸 수 있고, 재배포·수정·판매는 할 수 없습니다.

OMP Studio는 Oh My Pi와 무관한 독립 프로젝트입니다.
