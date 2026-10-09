# 모노플렉스KR Wide Nerd — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김양수
- 원본 배포처: https://github.com/y-kim/monoplex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [MonoplexKRWideNerd-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.otf) | OTF | 5.24 MB |
| [MonoplexKRWideNerd-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.ttf) | TTF | 3.27 MB |
| [MonoplexKRWideNerd-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.otf) | OTF | 4.64 MB |
| [MonoplexKRWideNerd-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.ttf) | TTF | 3.28 MB |
| [MonoplexKRWideNerd-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.otf) | OTF | 5.20 MB |
| [MonoplexKRWideNerd-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.ttf) | TTF | 3.32 MB |
| [MonoplexKRWideNerd-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.otf) | OTF | 5.24 MB |
| [MonoplexKRWideNerd-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.ttf) | TTF | 3.30 MB |
| [MonoplexKRWideNerd-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.otf) | OTF | 5.22 MB |
| [MonoplexKRWideNerd-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.ttf) | TTF | 3.30 MB |
| [MonoplexKRWideNerd-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.otf) | OTF | 5.21 MB |
| [MonoplexKRWideNerd-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.ttf) | TTF | 3.34 MB |
| [MonoplexKRWideNerd-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.otf) | OTF | 5.22 MB |
| [MonoplexKRWideNerd-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.ttf) | TTF | 3.28 MB |
| [MonoplexKRWideNerd-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.otf) | OTF | 4.35 MB |
| [MonoplexKRWideNerd-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.ttf) | TTF | 3.36 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Wide Nerd";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.woff2") format("woff2");
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
