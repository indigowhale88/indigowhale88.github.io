# indigowhale88.github.io

INDIGO WHALE 앱 개발 회사 웹사이트 — https://indigowhale88.github.io/

## 구조

```
index.html          메인 페이지 (회사소개 · 서비스 · 앱 · 문의)
404.html            404 페이지
assets/css/style.css
assets/js/main.js   스크롤 헤더, 모바일 메뉴, 스크롤 애니메이션
assets/img/logo.svg 로고 / 파비콘
.nojekyll           Jekyll 처리 없이 정적 파일 그대로 배포
```

## 로컬 미리보기

```bash
python -m http.server 8000
```

브라우저에서 http://localhost:8000 접속.

## 배포

`main` 브랜치에 push 하면 GitHub Pages가 자동으로 배포합니다.
(Settings → Pages → Source: `Deploy from a branch`, `main` / `root`)
