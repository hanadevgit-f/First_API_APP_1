# First_API_APP_1
## 프로젝트 구조
```
First_API_APP_1/
├── app/
    ├── build/
        ├── generated/
        ├── intermediates/
        ├── kotlin/
        ├── outputs/
        ├── snapshot/
        ├── tmp/
│   ├── build.gradle
│   └── src/
├── .gradle/
├── gradle/
├── .idea/
├── build.gradle
├── local.properties
└── settings.gradle

## 실행 방법
1. 모든 압축 파일을 해제하고 위 트리와 같은 구조로 위치합니다.
2. `local.properties.example` 파일을 복사하여 `local.properties`를 생성하고, Android SDK 경로와 API 키 등 환경별 값을 입력합니다.
3. Gradle wrapper 스크립트(`./gradlew`)를 이용해 프로젝트를 동기화하거나 빌드합니다.
4. local properties의 api 값과 info값을 채웁니다.
5. Android Studio에서 프로젝트 루트를 열고 필요에 따라 에뮬레이터 또는 실제 기기에서 실행합니다.

API-study.zip은 apk파일로, 안드로이드 환경에서 바로 실행 가능합니다. 
 

## Development Notes
- API 키와 개인 환경 설정은 `local.properties`에 보관하고 버전 관리에는 포함하지 않습니다.
- 빌드 산출물(`build/`, `.gradle/` 등)은 `.gitignore`로 관리하여 저장소를 깔끔하게 유지합니다.

## 개발 목표
 - 애플리케이션 개발 및 api 발급 및 활용 연습을 위함.
