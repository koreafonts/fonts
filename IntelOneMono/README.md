# Intel One Mono — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: Intel
- 원본 배포처: https://github.com/intel/intel-one-mono
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [IntelOneMono-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Bold.otf) | OTF | 0.10 MB |
| [IntelOneMono-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Bold.ttf) | TTF | 0.06 MB |
| [IntelOneMono-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Light.otf) | OTF | 0.10 MB |
| [IntelOneMono-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Light.ttf) | TTF | 0.06 MB |
| [IntelOneMono-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Medium.otf) | OTF | 0.10 MB |
| [IntelOneMono-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Medium.ttf) | TTF | 0.06 MB |
| [IntelOneMono-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Regular.otf) | OTF | 0.10 MB |
| [IntelOneMono-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMono-Regular.ttf) | TTF | 0.06 MB |
| [IntelOneMonoItalic-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Bold.otf) | OTF | 0.10 MB |
| [IntelOneMonoItalic-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Bold.ttf) | TTF | 0.06 MB |
| [IntelOneMonoItalic-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Light.otf) | OTF | 0.10 MB |
| [IntelOneMonoItalic-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Light.ttf) | TTF | 0.06 MB |
| [IntelOneMonoItalic-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Medium.otf) | OTF | 0.10 MB |
| [IntelOneMonoItalic-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Medium.ttf) | TTF | 0.06 MB |
| [IntelOneMonoItalic-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Regular.otf) | OTF | 0.10 MB |
| [IntelOneMonoItalic-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IntelOneMono/IntelOneMonoItalic-Regular.ttf) | TTF | 0.06 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Intel One Mono";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMono-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMono-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMono-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMono-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 300;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMonoItalic-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 400;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMonoItalic-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 500;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMonoItalic-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Intel One Mono";
  font-weight: 700;
  font-style: italic;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IntelOneMono/IntelOneMonoItalic-Bold.woff2") format("woff2");
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

원본 폰트: https://github.com/intel/intel-one-mono
