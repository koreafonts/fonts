# 나눔 고딕 코딩 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 네이버
- 원본 배포처: https://github.com/naver/nanumfont?tab=readme-ov-file
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [NanumGothicCoding-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumGothicCoding/NanumGothicCoding-Bold.ttf) | TTF | 1.72 MB |
| [NanumGothicCoding.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumGothicCoding/NanumGothicCoding.ttf) | TTF | 2.65 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-012-v2/NanumGothicCoding/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-012-v2/NanumGothicCoding/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "NanumGothicCoding";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-012-v2/NanumGothicCoding/NanumGothicCoding.woff2") format("woff2");
}
@font-face {
  font-family: "NanumGothicCoding";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-012-v2/NanumGothicCoding/NanumGothicCoding-Bold.woff2") format("woff2");
}
```

## 사용 범위

| 용도 | 범위 | 조건 |
|---|---|---|
| 앱 임베딩 | 허용 | — |
| 상업 이용 | 허용 | — |
| 로고 | 허용 | — |
| 수정 | 허용 | — |
| 포장 | 허용 | — |
| 인쇄 | 허용 | — |
| 재배포 | 허용 | — |
| 서브셋 | 허용 | — |
| 영상 | 허용 | — |
| 웹 | 허용 | — |

세부 조건과 저작권 표시는 [LICENSE.txt](LICENSE.txt)를 확인하세요.

## 출처

원본 폰트: https://github.com/naver/nanumfont?tab=readme-ov-file
원본 버전: https://github.com/fonts-archive/NanumGothicCoding/tree/170e8ab27ffbfd211dcd39a57b1cf8927aa1842b
기존 이용 범위 자료: https://fonts.taedonn.com/post/NanumGothicCoding
