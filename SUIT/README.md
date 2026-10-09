# 수트 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: SUNN YOUN
- 원본 배포처: https://sunn.us/suit/
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [SUIT-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Bold.otf) | OTF | 0.34 MB |
| [SUIT-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Bold.ttf) | TTF | 0.56 MB |
| [SUIT-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-ExtraBold.otf) | OTF | 0.34 MB |
| [SUIT-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-ExtraBold.ttf) | TTF | 0.56 MB |
| [SUIT-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-ExtraLight.otf) | OTF | 0.34 MB |
| [SUIT-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-ExtraLight.ttf) | TTF | 0.57 MB |
| [SUIT-Heavy.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Heavy.otf) | OTF | 0.34 MB |
| [SUIT-Heavy.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Heavy.ttf) | TTF | 0.56 MB |
| [SUIT-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Light.otf) | OTF | 0.34 MB |
| [SUIT-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Light.ttf) | TTF | 0.57 MB |
| [SUIT-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Medium.otf) | OTF | 0.34 MB |
| [SUIT-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Medium.ttf) | TTF | 0.56 MB |
| [SUIT-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Regular.otf) | OTF | 0.34 MB |
| [SUIT-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Regular.ttf) | TTF | 0.57 MB |
| [SUIT-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-SemiBold.otf) | OTF | 0.34 MB |
| [SUIT-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-SemiBold.ttf) | TTF | 0.56 MB |
| [SUIT-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Thin.otf) | OTF | 0.33 MB |
| [SUIT-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/SUIT/SUIT-Thin.ttf) | TTF | 0.58 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "SUIT";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Light.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-ExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "SUIT";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@523f37656d669b21cc8be54e41a89cca516658b5/SUIT/SUIT-Heavy.woff2") format("woff2");
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

원본 폰트: https://sunn.us/suit/
