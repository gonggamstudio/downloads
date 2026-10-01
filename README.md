# 공감스튜디오 프로그램 받기

공감스튜디오([gonggamstudio.co.kr](https://www.gonggamstudio.co.kr))의 PC 프로그램 설치 파일을 올려 두는 곳입니다.
소스 코드는 공개하지 않습니다.

## 최신 버전

| 프로그램 | 버전 | Windows 10/11 (64비트) | macOS 12 이상 (Apple Silicon) |
|---|---|---|---|
| 공감플레이어 (영상·음악 재생) | 1.0.1 | [GonggamPlayer-Setup-1.0.1.exe](https://github.com/gonggamstudio/downloads/releases/download/player-v1.0.1/GonggamPlayer-Setup-1.0.1.exe) | — |
| 공감그랩 (화면 캡처) | 1.0.3 | [GonggamGrab-Setup-1.0.3.exe](https://github.com/gonggamstudio/downloads/releases/download/grab-v1.0.3/GonggamGrab-Setup-1.0.3.exe) | [GonggamGrab-1.0.3.dmg](https://github.com/gonggamstudio/downloads/releases/download/grab-v1.0.3/GonggamGrab-1.0.3.dmg) |
| 공감컨버터 (이미지·PDF 변환) | 1.0.1 | [GonggamConverter-Setup-1.0.1.exe](https://github.com/gonggamstudio/downloads/releases/download/converter-v1.0.1/GonggamConverter-Setup-1.0.1.exe) | — |
| 공감캔버스 (사진 편집) | 1.0.1 | [GonggamCanvas-Setup-1.0.1.exe](https://github.com/gonggamstudio/downloads/releases/download/canvas-v1.0.1/GonggamCanvas-Setup-1.0.1.exe) | — |
| 공감모션 (영상 편집) | 1.0.1 | [GonggamMotion-Setup-1.0.1.exe](https://github.com/gonggamstudio/downloads/releases/download/motion-v1.0.1/GonggamMotion-Setup-1.0.1.exe) | — |
| 공감시트 (표 계산) | 1.0.2 | [GonggamSheet-Setup-1.0.2.exe](https://github.com/gonggamstudio/downloads/releases/download/sheet-v1.0.2/GonggamSheet-Setup-1.0.2.exe) | — |

지난 버전과 바뀐 점은 [릴리스](https://github.com/gonggamstudio/downloads/releases) 에서 볼 수 있습니다.

## 설치할 때 파란 경고가 뜨면 (Windows)

"Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행** 을 누르세요.
받은 파일이 올바른지 확인하려면 릴리스에 적힌 SHA-256 값과 비교하세요.

```
certutil -hashfile 받은파일.exe SHA256
```

## Mac 에 설치하기

받은 `.dmg` 를 열고 앱을 **응용 프로그램(Applications)** 폴더로 끌어 놓으세요.
맥용 프로그램은 Apple 의 확인(공증)을 받아 경고 없이 열립니다.

```
shasum -a 256 받은파일.dmg
```

## 이용

- 프로그램은 공감스튜디오 회원으로 로그인해 사용합니다.
- 설치 파일과 프로그램의 저작권은 공감스튜디오에 있습니다. 이 저장소의 파일을 다른 곳에 다시 올려 배포하지 마세요.
- 프로그램에 들어 있는 오픈소스 소프트웨어의 라이선스는 각 프로그램의 '오픈소스 라이선스' 메뉴에서 볼 수 있습니다.

## 프로그램·사이트용: 최신 버전 정보

[`latest.json`](latest.json) 에 프로그램별 최신 버전과 받는 주소가 있습니다 (`windows`, `mac`).

```
https://raw.githubusercontent.com/gonggamstudio/downloads/main/latest.json
```
