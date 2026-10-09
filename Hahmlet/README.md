# 함렛 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: Hypertype
- 원본 배포처: https://github.com/hyper-type/hahmlet
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [Hahmlet-Black.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Black.otf) | OTF | 0.44 MB |
| [Hahmlet-Black.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Black.ttf) | TTF | 1.96 MB |
| [Hahmlet-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Bold.otf) | OTF | 0.53 MB |
| [Hahmlet-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Bold.ttf) | TTF | 1.94 MB |
| [Hahmlet-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-ExtraBold.otf) | OTF | 0.54 MB |
| [Hahmlet-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-ExtraBold.ttf) | TTF | 1.95 MB |
| [Hahmlet-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-ExtraLight.otf) | OTF | 0.51 MB |
| [Hahmlet-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-ExtraLight.ttf) | TTF | 1.77 MB |
| [Hahmlet-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Light.otf) | OTF | 0.51 MB |
| [Hahmlet-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Light.ttf) | TTF | 1.82 MB |
| [Hahmlet-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Medium.otf) | OTF | 0.52 MB |
| [Hahmlet-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Medium.ttf) | TTF | 1.89 MB |
| [Hahmlet-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Regular.otf) | OTF | 0.43 MB |
| [Hahmlet-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Regular.ttf) | TTF | 1.84 MB |
| [Hahmlet-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-SemiBold.otf) | OTF | 0.53 MB |
| [Hahmlet-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-SemiBold.ttf) | TTF | 1.94 MB |
| [Hahmlet-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Thin.otf) | OTF | 0.39 MB |
| [Hahmlet-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Hahmlet/Hahmlet-Thin.ttf) | TTF | 1.66 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Hahmlet";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "Hahmlet";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/Hahmlet/Hahmlet-Black.woff2") format("woff2");
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

원본 폰트: https://github.com/hyper-type/hahmlet
