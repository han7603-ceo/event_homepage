# 국립스포츠박물관 개관 이벤트 미니사이트

정적 사이트 (빌드 없음). `index.html` + `assets/`.

## 자주 고치는 곳 (index.html)
- 날짜: 하단 `<script>`의 `TRIAL`, `OPEN`
- 색상: `<style>` 맨 위 `:root` 변수
- 문구: 각 섹션 주석(`<!-- 1. 히어로 -->` 등) 아래
- 약도 경로: `<svg>` 안 `d="M738 907 ..."` (map.webp 기준, SVG viewBox 1287×1222 좌표계)

## 배포
GitHub 저장소에 올린 뒤 Netlify / Vercel / GitHub Pages에서 저장소 연결 → push할 때마다 자동 배포.

## 확인 필요
- 팝콘 교환 방식(현재: 실시간 시계 화면 제시)
- 주소·교통편, 도보 안내 문구
