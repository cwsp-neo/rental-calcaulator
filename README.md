# KBR 렌탈료 계산기

렌탈료_산정파일.xlsx '스케줄' 시트 산식을 그대로 옮긴 모바일 계산기입니다.

## 파일 구성
- `index.html` — 계산기 본체 (산식 포함)
- `manifest.webmanifest` — 홈 화면 앱 설정 (이름, 아이콘, 전체화면)
- `sw.js` — 오프라인 캐시 (전파가 약한 현장에서도 실행)
- `icons/` — 앱 아이콘

## 배포 (GitHub Pages)
1. GitHub에서 새 저장소 생성 (예: `rental-calculator`, Public)
2. 이 폴더의 파일을 구조 그대로 업로드 (Add file → Upload files)
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `(root)` → Save
4. 1~2분 후 `https://<계정명>.github.io/rental-calculator/` 로 접속

## 수정 후 재배포
`index.html`을 바꿔 올릴 때는 `sw.js` 맨 위 `VERSION`을 `v2`, `v3`…로 올려 주세요.
