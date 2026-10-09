# 스위트 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: SUNN YOUN
- 원본 배포처: https://sunn.us/suite/
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [SUITE-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Bold.otf) | OTF | 0.29 MB |
| [SUITE-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Bold.ttf) | TTF | 0.55 MB |
| [SUITE-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-ExtraBold.otf) | OTF | 0.29 MB |
| [SUITE-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-ExtraBold.ttf) | TTF | 0.54 MB |
| [SUITE-Heavy.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Heavy.otf) | OTF | 0.29 MB |
| [SUITE-Heavy.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Heavy.ttf) | TTF | 0.54 MB |
| [SUITE-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Light.otf) | OTF | 0.30 MB |
| [SUITE-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Light.ttf) | TTF | 0.56 MB |
| [SUITE-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Medium.otf) | OTF | 0.29 MB |
| [SUITE-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Medium.ttf) | TTF | 0.55 MB |
| [SUITE-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Regular.otf) | OTF | 0.28 MB |
| [SUITE-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-Regular.ttf) | TTF | 0.55 MB |
| [SUITE-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-SemiBold.otf) | OTF | 0.29 MB |
| [SUITE-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUITE/SUITE-SemiBold.ttf) | TTF | 0.55 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "SUITE";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-Light.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "SUITE";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-019-v3/SUITE/SUITE-Heavy.woff2") format("woff2");
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

원본 폰트: https://sunn.us/suite/
