# 모노플렉스KR Nerd — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김양수
- 원본 배포처: https://github.com/y-kim/monoplex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [MonoplexKRNerd-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Bold.otf) | OTF | 5.32 MB |
| [MonoplexKRNerd-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Bold.ttf) | TTF | 3.29 MB |
| [MonoplexKRNerd-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-ExtraBold.otf) | OTF | 4.72 MB |
| [MonoplexKRNerd-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-ExtraBold.ttf) | TTF | 3.29 MB |
| [MonoplexKRNerd-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-ExtraLight.otf) | OTF | 5.28 MB |
| [MonoplexKRNerd-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-ExtraLight.ttf) | TTF | 3.33 MB |
| [MonoplexKRNerd-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Light.otf) | OTF | 5.32 MB |
| [MonoplexKRNerd-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Light.ttf) | TTF | 3.31 MB |
| [MonoplexKRNerd-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Medium.otf) | OTF | 5.29 MB |
| [MonoplexKRNerd-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Medium.ttf) | TTF | 3.31 MB |
| [MonoplexKRNerd-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Regular.otf) | OTF | 5.29 MB |
| [MonoplexKRNerd-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Regular.ttf) | TTF | 3.32 MB |
| [MonoplexKRNerd-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-SemiBold.otf) | OTF | 5.30 MB |
| [MonoplexKRNerd-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-SemiBold.ttf) | TTF | 3.29 MB |
| [MonoplexKRNerd-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Thin.otf) | OTF | 4.43 MB |
| [MonoplexKRNerd-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKRNerd/MonoplexKRNerd-Thin.ttf) | TTF | 3.37 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-007-v3/MonoplexKRNerd/MonoplexKRNerd-ExtraBold.woff2") format("woff2");
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
