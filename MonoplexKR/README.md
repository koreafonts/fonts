# 모노플렉스KR — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김양수
- 원본 배포처: https://github.com/y-kim/monoplex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [MonoplexKR-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Bold.otf) | OTF | 2.93 MB |
| [MonoplexKR-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Bold.ttf) | TTF | 2.54 MB |
| [MonoplexKR-ExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-ExtraBold.otf) | OTF | 2.33 MB |
| [MonoplexKR-ExtraBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-ExtraBold.ttf) | TTF | 2.53 MB |
| [MonoplexKR-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-ExtraLight.otf) | OTF | 2.89 MB |
| [MonoplexKR-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-ExtraLight.ttf) | TTF | 2.58 MB |
| [MonoplexKR-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Light.otf) | OTF | 2.93 MB |
| [MonoplexKR-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Light.ttf) | TTF | 2.56 MB |
| [MonoplexKR-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Medium.otf) | OTF | 2.91 MB |
| [MonoplexKR-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Medium.ttf) | TTF | 2.55 MB |
| [MonoplexKR-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Regular.otf) | OTF | 2.91 MB |
| [MonoplexKR-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Regular.ttf) | TTF | 2.56 MB |
| [MonoplexKR-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-SemiBold.otf) | OTF | 2.92 MB |
| [MonoplexKR-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-SemiBold.ttf) | TTF | 2.54 MB |
| [MonoplexKR-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Thin.otf) | OTF | 2.04 MB |
| [MonoplexKR-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/MonoplexKR/MonoplexKR-Thin.ttf) | TTF | 2.62 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Monoplex KR";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-Light.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-Bold.woff2") format("woff2");
}
@font-face {
  font-family: "Monoplex KR";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@8c4173b46423c37ab346aa04498596aca064670b/MonoplexKR/MonoplexKR-ExtraBold.woff2") format("woff2");
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
