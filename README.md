# 교육장 인사말 큐카드 스튜디오 v7.7

GitHub Pages에 바로 업로드할 수 있는 배포 세트입니다.

## 폴더 구성

- `index.html` — 실행 프로그램
- `manifest.webmanifest` — 홈 화면 설치/PWA 정보
- `service-worker.js` — 핵심 파일 오프라인 캐시
- `favicon.ico` — 브라우저 탭 아이콘
- `apple-touch-icon.png` — iPhone/iPad 홈 화면 아이콘
- `assets/icons/` — 앱 아이콘 PNG/SVG 세트
- `.nojekyll` — GitHub Pages 정적 파일 배포용

## GitHub Pages 배포

1. 새 GitHub 저장소를 만듭니다.
2. 이 폴더의 **내용물 전체**를 저장소 최상위(root)에 업로드합니다.
3. GitHub 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, Folder는 `/(root)`를 선택하고 저장합니다.
6. Pages 주소가 생성되면 해당 주소로 실행합니다.

## 업데이트할 때

프로그램 파일을 수정하면 `index.html`을 교체하십시오. 서비스워커의 캐시 이름(`CACHE_NAME`)도 버전별로 바꾸면 기존 캐시 때문에 구버전이 남는 일을 줄일 수 있습니다.

## 출력 참고

150×100mm 엽서 출력은 프로그램의 출력 모드와 프린터 드라이버의 용지 설정이 서로 독립적입니다. 프린터 환경에 따라 `직접 용지설정` 또는 `A4 수동급지 호환` 모드를 선택하십시오.

© 2026 박주가리교감
