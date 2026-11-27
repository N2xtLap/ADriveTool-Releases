<p align="center"><img src=".github/logo.svg" width="128" alt="ADriveTool-Releases logo"></p>

# ADriveTool Releases

Official binary distribution repository for **ADriveTool**, including the integrated actuator QC workflow.

> 이 저장소는 회사 공식 GitHub organization이 준비될 때까지 `N2xtLap`에서 임시로 관리합니다. 향후 회사 organization으로 소유권을 이전할 예정입니다.

## 배포 원칙

- 소스 코드는 이 저장소에 포함하지 않습니다.
- 승인된 GitHub Release의 실행 파일, 설치 문서, SHA-256 checksum만 배포합니다.
- debug symbol, firmware image, 내부 설정, 장비 정보, 시험 로그와 임시 CI artifact는 공개하지 않습니다.
- Release가 게시되기 전까지 임의의 개발 빌드를 정식 배포본으로 사용하지 마세요.

## 예정된 다운로드 파일

- `ADriveTool_Setup.exe` — Windows installer with the integrated `QC` tab
- `ADriveTool_Setup.exe.sha256`
- `release-manifest.json`
- `INSTALL.md`

최신 승인 Release가 게시되면 다음 고정 주소를 사용할 수 있습니다.

```text
https://github.com/N2xtLap/ADriveTool-Releases/releases/latest/download/ADriveTool_Setup.exe
```

```text
https://github.com/N2xtLap/ADriveTool-Releases/releases/latest/download/ADriveTool_Setup.exe.sha256
```

## Source repository

Source code, pull requests, CI, and release approval are maintained separately in the private `N2xtLap/ADriveTool` repository.
