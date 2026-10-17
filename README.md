# ROCKY GROUP 배포 파일

ROCKY GROUP 앱의 Windows 설치 파일과 자동 업데이트 정보만 올리는 공개 저장소입니다. 앱 소스는 비공개 저장소에 있습니다.

- 설치 파일: [Releases](../../releases) 의 `ROCKY_GROUP_Setup_<버전>_<빌드>.exe`
- 자동 업데이트 정보: [`windows/update.json`](windows/update.json) — 앱이 시작할 때 읽습니다.
  - `latest`: 최신 설치 파일(주소, SHA-256)
  - `minBuild`: 이 빌드 번호 미만은 실행할 수 없고 업데이트해야 합니다.

이 저장소는 앱 저장소의 `scripts/publish-windows-release.sh` 로만 갱신합니다. 직접 고치지 마세요.
