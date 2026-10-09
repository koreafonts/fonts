# IBM Plex Sans KR — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: IBM
- 원본 배포처: https://github.com/IBM/plex
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [IBMPlexSansKR-Bold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Bold.otf) | OTF | 0.73 MB |
| [IBMPlexSansKR-Bold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Bold.ttf) | TTF | 2.74 MB |
| [IBMPlexSansKR-ExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.otf) | OTF | 0.87 MB |
| [IBMPlexSansKR-ExtraLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.ttf) | TTF | 2.73 MB |
| [IBMPlexSansKR-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Light.otf) | OTF | 0.87 MB |
| [IBMPlexSansKR-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Light.ttf) | TTF | 2.67 MB |
| [IBMPlexSansKR-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Medium.otf) | OTF | 0.88 MB |
| [IBMPlexSansKR-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Medium.ttf) | TTF | 2.73 MB |
| [IBMPlexSansKR-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Regular.otf) | OTF | 0.87 MB |
| [IBMPlexSansKR-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Regular.ttf) | TTF | 2.67 MB |
| [IBMPlexSansKR-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-SemiBold.otf) | OTF | 0.89 MB |
| [IBMPlexSansKR-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-SemiBold.ttf) | TTF | 2.72 MB |
| [IBMPlexSansKR-Thin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Thin.otf) | OTF | 0.66 MB |
| [IBMPlexSansKR-Thin.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/IBMPlexSansKR/IBMPlexSansKR-Thin.ttf) | TTF | 2.40 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-Thin.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-Light.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-Medium.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-SemiBold.woff2") format("woff2");
}
@font-face {
  font-family: "IBM Plex Sans KR";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@3be6c84bed735d55b4d9cec7f7f9f33fbda2d2ee/IBMPlexSansKR/IBMPlexSansKR-Bold.woff2") format("woff2");
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

원본 폰트: https://github.com/IBM/plex
