# Rilog. 랜딩 페이지

정적 파일만 있는 페이지라 빌드 과정이 없습니다.

## Vercel에 배포
```
cd rilog-landing
npx vercel          # 처음 한 번: 로그인 + 프로젝트 연결 (질문에는 기본값 Enter)
npx vercel --prod   # 운영 주소로 배포
```
- Framework Preset: Other / Build Command: 없음 / Output Directory: `.` (기본값 그대로)

## 구성
- `index.html` — 페이지 (Pretendard 글꼴은 쓰는 글자만 남겨 파일 안에 넣어 둠)
- `media/*.mp4` — 기능 소개 영상 4개, `media/*.jpg` — 영상 첫 화면
- `vercel.json` — 영상 파일 캐시 설정
