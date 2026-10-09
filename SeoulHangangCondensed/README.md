# 서울한강 장체 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 서울시청
- 원본 배포처: https://www.seoul.go.kr/seoul/font.do
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [SeoulHangangCondensed-Black.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeoulHangangCondensed/SeoulHangangCondensed-Black.ttf) | TTF | 6.79 MB |
| [SeoulHangangCondensed-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeoulHangangCondensed/SeoulHangangCondensed-Bold.ttf) | TTF | 7.00 MB |
| [SeoulHangangCondensed-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeoulHangangCondensed/SeoulHangangCondensed-ExtraBold.ttf) | TTF | 7.00 MB |
| [SeoulHangangCondensed-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeoulHangangCondensed/SeoulHangangCondensed-Light.ttf) | TTF | 7.29 MB |
| [SeoulHangangCondensed-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeoulHangangCondensed/SeoulHangangCondensed-Medium.ttf) | TTF | 7.28 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Seoul Hangang Condensed";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/SeoulHangangCondensed-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Seoul Hangang Condensed";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/SeoulHangangCondensed-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Seoul Hangang Condensed";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/SeoulHangangCondensed-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Seoul Hangang Condensed";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/SeoulHangangCondensed-ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "Seoul Hangang Condensed";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeoulHangangCondensed/SeoulHangangCondensed-Black.woff2") format("woff2");
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

원본 폰트: https://www.seoul.go.kr/seoul/font.do
