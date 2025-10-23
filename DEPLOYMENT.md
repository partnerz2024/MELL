# GitHub Pages 설정

이 저장소는 GitHub Pages를 통해 자동으로 배포됩니다.

## 배포 방법

1. 이 저장소를 GitHub에 업로드
2. Settings > Pages에서 Source를 "Deploy from a branch"로 설정
3. Branch를 "main"으로 선택
4. Save 버튼 클릭

## 접속 URL

배포 완료 후 다음 URL로 접속할 수 있습니다:
`https://[사용자명].github.io/[저장소명]`

## 파일 구조

```
├── index.html          # 메인 HTML 파일
├── styles.css          # CSS 스타일
├── app.js             # JavaScript 애플리케이션
├── parts.manifest.json # 파츠 매니페스트
├── assets/            # 이미지 리소스
│   ├── hair/          # 머리 이미지
│   ├── cloth/         # 옷 이미지
│   ├── accessory/     # 액세서리 이미지
│   ├── hat/           # 모자 이미지
│   ├── face/          # 얼굴 이미지
│   └── thumbnail/      # 썸네일 이미지
└── README.md          # 프로젝트 설명
```

## 주의사항

- 모든 이미지 파일은 `assets/` 폴더에 있어야 합니다
- 파일명에 특수문자나 공백이 있으면 URL 인코딩이 필요할 수 있습니다
- 대용량 이미지 파일은 GitHub의 파일 크기 제한을 확인하세요
