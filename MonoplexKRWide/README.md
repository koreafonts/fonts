# 모노플렉스KR Wide — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김양수
- 원본 배포처: https://github.com/y-kim/monoplex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [MonoplexKRWide-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Bold.otf) | OTF | 2.91 MB |
| [MonoplexKRWide-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Bold.ttf) | TTF | 2.52 MB |
| [MonoplexKRWide-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-ExtraBold.otf) | OTF | 2.30 MB |
| [MonoplexKRWide-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-ExtraBold.ttf) | TTF | 2.52 MB |
| [MonoplexKRWide-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-ExtraLight.otf) | OTF | 2.86 MB |
| [MonoplexKRWide-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-ExtraLight.ttf) | TTF | 2.57 MB |
| [MonoplexKRWide-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Light.otf) | OTF | 2.90 MB |
| [MonoplexKRWide-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Light.ttf) | TTF | 2.55 MB |
| [MonoplexKRWide-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Medium.otf) | OTF | 2.89 MB |
| [MonoplexKRWide-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Medium.ttf) | TTF | 2.54 MB |
| [MonoplexKRWide-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Regular.otf) | OTF | 2.88 MB |
| [MonoplexKRWide-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Regular.ttf) | TTF | 2.58 MB |
| [MonoplexKRWide-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-SemiBold.otf) | OTF | 2.89 MB |
| [MonoplexKRWide-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-SemiBold.ttf) | TTF | 2.53 MB |
| [MonoplexKRWide-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Thin.otf) | OTF | 2.01 MB |
| [MonoplexKRWide-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWide/MonoplexKRWide-Thin.ttf) | TTF | 2.61 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@309fddcc68a6c33d0f6bd12526a42c91aa819828/MonoplexKRWide/MonoplexKRWide-ExtraBold.woff2") format("woff2");
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

원본 폰트: https://github.com/y-kim/monoplex
