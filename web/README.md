# Turn City 인트라넷 - 웹 UI

## 배포: Cloudflare Pages

1. GitHub에 push
2. Cloudflare Pages → 새 프로젝트 → GitHub 연결
3. 빌드 설정:
   - 빌드 명령: 없음 (정적 HTML)
   - 빌드 출력 디렉토리: `public`
4. 커스텀 도메인: `intranet.turncity.kr` 등

## 파일 구조
```
web/
└── public/
    └── index.html  ← 인트라넷 메인 (단일 HTML)
```
