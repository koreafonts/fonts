# 김제시체 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 김제시청
- 원본 배포처: https://www.gimje.go.kr/index.gimje?menuCd=DOM_000000102003002001
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [GIMJE-Light.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/GIMJE/GIMJE-Light.otf) | OTF | 1.19 MB |
| [GIMJE-Light.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/GIMJE/GIMJE-Light.ttf) | TTF | 0.78 MB |
| [GIMJE-Medium.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/GIMJE/GIMJE-Medium.otf) | OTF | 0.77 MB |
| [GIMJE-Medium.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/GIMJE/GIMJE-Medium.ttf) | TTF | 0.55 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/GIMJE/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/GIMJE/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "GIMJE";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/GIMJE/GIMJE-Light.woff2") format("woff2");
}
@font-face {
  font-family: "GIMJE";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-003-v3/GIMJE/GIMJE-Medium.woff2") format("woff2");
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

원본 폰트: https://www.gimje.go.kr/index.gimje?menuCd=DOM_000000102003002001
