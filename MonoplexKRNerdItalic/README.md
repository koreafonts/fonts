# 모노플렉스KR Nerd Italic — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김양수
- 원본 배포처: https://github.com/y-kim/monoplex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [MonoplexKRNerdItalic-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Bold.otf) | OTF | 5.91 MB |
| [MonoplexKRNerdItalic-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Bold.ttf) | TTF | 3.49 MB |
| [MonoplexKRNerdItalic-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraBold.otf) | OTF | 5.27 MB |
| [MonoplexKRNerdItalic-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraBold.ttf) | TTF | 3.49 MB |
| [MonoplexKRNerdItalic-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraLight.otf) | OTF | 5.88 MB |
| [MonoplexKRNerdItalic-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraLight.ttf) | TTF | 3.53 MB |
| [MonoplexKRNerdItalic-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Light.otf) | OTF | 5.90 MB |
| [MonoplexKRNerdItalic-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Light.ttf) | TTF | 3.51 MB |
| [MonoplexKRNerdItalic-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Medium.otf) | OTF | 5.93 MB |
| [MonoplexKRNerdItalic-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Medium.ttf) | TTF | 3.50 MB |
| [MonoplexKRNerdItalic-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Regular.otf) | OTF | 5.92 MB |
| [MonoplexKRNerdItalic-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Regular.ttf) | TTF | 3.51 MB |
| [MonoplexKRNerdItalic-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-SemiBold.otf) | OTF | 5.90 MB |
| [MonoplexKRNerdItalic-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-SemiBold.ttf) | TTF | 3.50 MB |
| [MonoplexKRNerdItalic-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Thin.otf) | OTF | 4.93 MB |
| [MonoplexKRNerdItalic-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Thin.ttf) | TTF | 3.57 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR Nerd Italic";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-008-v2/MonoplexKRNerdItalic/MonoplexKRNerdItalic-ExtraBold.woff2") format("woff2");
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
원본 버전: https://github.com/fonts-archive/MonoplexKRNerdItalic/tree/b388e9fe0d666ff4ca02443de84da34db2a35be7
기존 이용 범위 자료: https://fonts.taedonn.com/post/Monoplex+KR+Nerd+Italic
