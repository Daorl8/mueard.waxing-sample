# STRUCTURE · mueard.waxing-sample (v0.1 · 배포 예정 mueardwaxing-sample.lgt3232.workers.dev)

```
mueard.waxing-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = mueardwaxing-sample (Cloudflare 이름에 점 불가)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ mu-italiana.woff2          MUEARD 워드마크 · 큰 영문 제목 (Italiana 400, 영문 · 기호만)
├─ mu-pretendard.woff2        본문 · 한글 제목 · 버튼 (Pretendard 300–600, 페이지 글자 전부)
├─ mu-hero.webp               히어로 · 덩굴 벽 (흑백)
├─ mu-chair · mu-pearl .webp  소개 분위기 사진 (흑백)
├─ mu-shadow.webp             방문 전 안내 아래 띠 (흑백)
├─ mu-ba-leg · mu-ba-knee · mu-ba-arm .webp   시술 전후 (컬러)
├─ favicon.png · og-mu.jpg
├─ img/                       다올 제공 원본 + _원문.md + mu-cup_미사용.webp (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로(흑백 사진 + 그라데이션) → `#about` → `#care`(#1A1A1A · 시술항목 3 · 진정케어 · 세트 4) → `#price` → `#result`(#1A1A1A) → `#prep`(+ 그림자 띠) → `#visit`(#1A1A1A) → 푸터 + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 예약 `https://m.place.naver.com/place/1302654610/home`: 헤더 · 히어로 · 가격 안내 · 오시는 길 · 하단 바(메인)
- 카카오채널 `https://pf.kakao.com/_gXDbG`: 히어로 · 오시는 길 · 푸터 · 하단 바
- 전화 `tel:050713728758`(0507-1372-8758): 히어로 · 오시는 길 · 푸터 · 하단 바
- 네이버 길찾기 `https://map.naver.com/p/entry/place/1302654610` · 인스타(전후 안내 · 푸터) · 블로그(푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만(페이지 글자 전부), Italiana는 영문만.
