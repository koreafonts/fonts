# 프리젠테이션 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 이주임
- 원본 배포처: https://freesentation.blog/
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [Freesentation-1Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-1Thin.otf) | OTF | 4.55 MB |
| [Freesentation-1Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-1Thin.ttf) | TTF | 2.92 MB |
| [Freesentation-2ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-2ExtraLight.otf) | OTF | 4.66 MB |
| [Freesentation-2ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-2ExtraLight.ttf) | TTF | 2.92 MB |
| [Freesentation-3Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-3Light.otf) | OTF | 4.70 MB |
| [Freesentation-3Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-3Light.ttf) | TTF | 2.91 MB |
| [Freesentation-4Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-4Regular.otf) | OTF | 4.72 MB |
| [Freesentation-4Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-4Regular.ttf) | TTF | 2.91 MB |
| [Freesentation-5Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-5Medium.otf) | OTF | 4.67 MB |
| [Freesentation-5Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-5Medium.ttf) | TTF | 2.91 MB |
| [Freesentation-6SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-6SemiBold.otf) | OTF | 4.71 MB |
| [Freesentation-6SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-6SemiBold.ttf) | TTF | 2.91 MB |
| [Freesentation-7Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-7Bold.otf) | OTF | 4.70 MB |
| [Freesentation-7Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-7Bold.ttf) | TTF | 2.91 MB |
| [Freesentation-8ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-8ExtraBold.otf) | OTF | 4.70 MB |
| [Freesentation-8ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-8ExtraBold.ttf) | TTF | 2.91 MB |
| [Freesentation-9Black.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-9Black.otf) | OTF | 4.75 MB |
| [Freesentation-9Black.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/Freesentation-9Black.ttf) | TTF | 2.91 MB |
| [variables/Freesentation-VF.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/Freesentation/variables/Freesentation-VF.ttf) | TTF | 6.64 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Freesentation";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-1Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-2ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-3Light.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-4Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-5Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-6SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-7Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-8ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "Freesentation";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-002-v3/Freesentation/Freesentation-9Black.woff2") format("woff2");
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

원본 폰트: https://freesentation.blog/
