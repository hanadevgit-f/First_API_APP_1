# First_API_APP_1
## 프로젝트 구조
```
First_API_APP_1/
├── app/
│   ├── build.gradle
│   └── src/
├── build.gradle
├── gradle/
│   └── wrapper/
├── gradle.properties
├── gradlew*
├── gradlew.bat
├── local.properties.example
└── settings.gradle
```

## 실행 방법
1. `local.properties.example` 파일을 복사하여 `local.properties`를 생성하고, Android SDK 경로와 API 키 등 환경별 값을 입력합니다.
2. Gradle wrapper 스크립트(`./gradlew`)를 이용해 프로젝트를 동기화하거나 빌드합니다.
3. Android Studio에서 프로젝트 루트를 열고 필요에 따라 에뮬레이터 또는 실제 기기에서 실행합니다.

## 환경 변수
`local.properties`에서 다음 항목을 설정할 수 있습니다.
- `VFOR_BASE_URL`
- `VFOR_API_KEY`
- `VFOR_AGE`
- `VFOR_PSIZE`
- `info1`
- `info2`

## Development Notes
- API 키와 개인 환경 설정은 `local.properties`에 보관하고 버전 관리에는 포함하지 않습니다.
- 빌드 산출물(`build/`, `.gradle/` 등)은 `.gitignore`로 관리하여 저장소를 깔끔하게 유지합니다.
