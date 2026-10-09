# Sero Pro — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: FontFont
- 원본 배포처: https://en.fontsloader.com/types/sero-pro
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [SeroPro-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-Bold.ttf) | TTF | 0.20 MB |
| [SeroPro-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-ExtraBold.ttf) | TTF | 0.19 MB |
| [SeroPro-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-ExtraLight.ttf) | TTF | 0.20 MB |
| [SeroPro-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-Light.ttf) | TTF | 0.20 MB |
| [SeroPro-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-Medium.ttf) | TTF | 0.20 MB |
| [SeroPro-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-Regular.ttf) | TTF | 0.20 MB |
| [SeroPro-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-SemiBold.ttf) | TTF | 0.20 MB |
| [SeroPro-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroPro-Thin.ttf) | TTF | 0.20 MB |
| [SeroProItalic-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-Bold.ttf) | TTF | 0.21 MB |
| [SeroProItalic-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-ExtraBold.ttf) | TTF | 0.20 MB |
| [SeroProItalic-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-ExtraLight.ttf) | TTF | 0.21 MB |
| [SeroProItalic-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-Light.ttf) | TTF | 0.21 MB |
| [SeroProItalic-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-Medium.ttf) | TTF | 0.21 MB |
| [SeroProItalic-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-Regular.ttf) | TTF | 0.21 MB |
| [SeroProItalic-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-SemiBold.ttf) | TTF | 0.21 MB |
| [SeroProItalic-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SeroPro/SeroProItalic-Thin.ttf) | TTF | 0.21 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Sero Pro";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroPro-ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 100;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 200;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 300;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 400;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 500;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 600;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 700;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Sero Pro";
  font-weight: 800;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-018-v3/SeroPro/SeroProItalic-ExtraBold.woff2") format("woff2");
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

원본 폰트: https://en.fontsloader.com/types/sero-pro
