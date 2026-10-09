# 에스코어드림 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: S-Core
- 원본 배포처: https://s-core.co.kr/company/font2/
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [SCDreamBlack.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamBlack.otf) | OTF | 0.71 MB |
| [SCDreamBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamBold.otf) | OTF | 0.71 MB |
| [SCDreamExtraBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamExtraBold.otf) | OTF | 0.71 MB |
| [SCDreamExtraLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamExtraLight.otf) | OTF | 0.70 MB |
| [SCDreamHeavy.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamHeavy.otf) | OTF | 0.71 MB |
| [SCDreamLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamLight.otf) | OTF | 0.70 MB |
| [SCDreamMedium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamMedium.otf) | OTF | 0.70 MB |
| [SCDreamRegular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamRegular.otf) | OTF | 0.70 MB |
| [SCDreamThin.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/S-CoreDream/SCDreamThin.otf) | OTF | 0.70 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "S-Core Dream";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamThin.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamExtraLight.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamLight.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamRegular.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamMedium.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamBold.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamExtraBold.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamHeavy.woff2") format("woff2");
}
@font-face {
  font-family: "S-Core Dream";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@ee4054052e251025fe63b73c275455b27ac75852/S-CoreDream/SCDreamBlack.woff2") format("woff2");
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

원본 폰트: https://s-core.co.kr/company/font2/
