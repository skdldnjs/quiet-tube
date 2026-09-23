# 조용한 튜브

Android 8.0 이상용 검색·영상 재생 앱입니다. 백그라운드 오디오, 영상 좌우 탐색, 앱 실행 시 업데이트 안내를 제공합니다.

## 설치

[최신 APK와 전체 소스 받기](https://github.com/skdldnjs/quiet-tube/releases/latest)

릴리스의 `quiet-tube-버전.apk`를 설치하세요. 기존 앱은 삭제하지 않고 덮어설치합니다.

## 자동 업데이트

0.6부터 배포 주소가 기본으로 포함됩니다. 새 버전이 게시되면 앱 실행 시 변경 내역과 함께 ‘업데이트할까요?’가 표시됩니다. ‘나중에’를 누르면 같은 버전은 6시간 동안 다시 묻지 않습니다. 설치의 마지막 단계는 Android 확인 화면에서 승인해야 합니다.

기존 0.5에서는 업데이트 주소 설정에 아래 주소를 한 번 등록하거나 0.6 APK를 직접 설치하세요.

```
https://github.com/skdldnjs/quiet-tube/releases/latest/download/update.json
```

## 소스와 라이선스

앱 전체 소스는 **GPL-3.0-or-later**로 제공합니다. 각 릴리스의 `quiet-tube-버전-source.zip`에 앱 소스, 빌드 파일, 라이선스와 포함 구성요소의 원본 소스가 들어 있습니다. ZIP 안의 README.md와 THIRD_PARTY_NOTICES.md를 참고하세요. 개인 서명키는 포함하지 않습니다.

NewPipe Extractor와 AndroidX Media3를 사용합니다. Google/YouTube 공식 앱은 아닙니다.

## 검증 범위

자동 테스트 41개, Android Lint 및 APK 서명 검증을 통과했습니다. 실제 휴대폰에서 설치·재생·앱 교체는 아직 확인하지 못했습니다.
