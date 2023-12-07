# macha-client

Macha App README 입니다.

## 시작하기

1. **Flutter 설치:**
   - Flutter를 설치하려면 [Flutter 공식 사이트](https://flutter.dev/docs/get-started/install)를 참조하세요.

2. **프로젝트 복제:**
   ```bash
   git clone https://github.com/macha-project/macha-client.git
   
3. **프로젝트 실행**
   ```bash
   flutter doctor #Flutter 개발환경이 올바르게 설치되었는지 확인하는 데 사용됩니다. 실행하면 Flutter 및 Dart SDK의 설치 여부, 필요한 의존성들, 개발 환경 설정 등을 확인하고 문제가 있는 경우에는 해결 방법을 안내해줍니다.
   flutter pub get #프로젝트에 필요한 종속성을 가져오는데 사용됩니다. Flutter 프로젝트에는 종속성이 pubspec.yaml 파일에 명시되어 있고, 이 명령어를 실행하여 해당 종속성을 설치합니다.
   flutter run # Flutter 앱을 실행하는데 사용됩니다. 프로젝트에 여러 플랫폼이 지원되는 경우에는 실행할 타겟 플랫폼을 지정할 수 있습니다.


# Info

sunwoopia@Sunwoo-Kim-MacBook-Pro ~ % flutter --version
Flutter 3.16.2 • channel stable • https://github.com/flutter/flutter.git
Tools • Dart 3.2.2 • DevTools 2.28.3
environment:
  sdk: ">=3.1.3 <4.0.0"
dependencies:
  flutter:
    sdk: flutter

  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  cupertino_icons: ^1.0.2
  flutter_svg: ^2.0.9
  http: ^1.1.0
  flutter_naver_map: ^1.0.2
  shared_preferences: ^2.2.2
  email_validator: ^2.1.17
  geolocator: ^10.1.0
  permission_handler: ^11.0.1
  provider: ^6.1.1
  intl: ^0.18.1
  firebase_messaging: ^14.7.6
  firebase_core: ^2.24.0
  flutter_local_notifications: ^16.2.0

