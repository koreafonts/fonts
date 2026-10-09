# Interop — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 장해민
- 원본 배포처: https://github.com/jhaemin/Interop/
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [Interop-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-Bold.otf) | OTF | 2.36 MB |
| [Interop-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-ExtraBold.otf) | OTF | 2.22 MB |
| [Interop-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-ExtraLight.otf) | OTF | 2.37 MB |
| [Interop-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-Light.otf) | OTF | 2.43 MB |
| [Interop-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-Medium.otf) | OTF | 2.47 MB |
| [Interop-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-Regular.otf) | OTF | 2.43 MB |
| [Interop-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-SemiBold.otf) | OTF | 2.43 MB |
| [Interop-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Interop/Interop-Thin.otf) | OTF | 2.16 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Interop";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Interop";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-005-v3/Interop/Interop-ExtraBold.woff2") format("woff2");
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

원본 폰트: https://github.com/jhaemin/Interop/
