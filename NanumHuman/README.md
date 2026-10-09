# 나눔휴먼 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 네이버
- 원본 배포처: https://m-hangeul.naver.com/font/detail/NanumHuman
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [NanumHumanBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanBold.otf) | OTF | 0.42 MB |
| [NanumHumanBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanBold.ttf) | TTF | 1.04 MB |
| [NanumHumanEB.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanEB.otf) | OTF | 0.42 MB |
| [NanumHumanEB.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanEB.ttf) | TTF | 1.02 MB |
| [NanumHumanEL.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanEL.otf) | OTF | 0.41 MB |
| [NanumHumanEL.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanEL.ttf) | TTF | 0.97 MB |
| [NanumHumanHeavy.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanHeavy.otf) | OTF | 0.40 MB |
| [NanumHumanHeavy.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanHeavy.ttf) | TTF | 1.16 MB |
| [NanumHumanLight.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanLight.otf) | OTF | 0.42 MB |
| [NanumHumanLight.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanLight.ttf) | TTF | 0.95 MB |
| [NanumHumanRegular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanRegular.otf) | OTF | 0.42 MB |
| [NanumHumanRegular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/NanumHuman/NanumHumanRegular.ttf) | TTF | 1.01 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "NanumHuman";
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanEL.woff2") format("woff2");
}
@font-face {
  font-family: "NanumHuman";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanLight.woff2") format("woff2");
}
@font-face {
  font-family: "NanumHuman";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanRegular.woff2") format("woff2");
}
@font-face {
  font-family: "NanumHuman";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanBold.woff2") format("woff2");
}
@font-face {
  font-family: "NanumHuman";
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanEB.woff2") format("woff2");
}
@font-face {
  font-family: "NanumHuman";
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@fd38f5a480a8a683318a3cdd7ec4210a4dcdd9a9/NanumHuman/NanumHumanHeavy.woff2") format("woff2");
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

원본 폰트: https://m-hangeul.naver.com/font/detail/NanumHuman
