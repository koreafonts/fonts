# 북엔드 바탕 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: (주)북엔드
- 원본 배포처: https://www.bookend.tech/font
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [BookendBatang-Regular.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/BookendBatang/BookendBatang-Regular.otf) | OTF | 1.17 MB |
| [BookendBatang-Regular.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/BookendBatang/BookendBatang-Regular.ttf) | TTF | 1.38 MB |
| [BookendBatang-SemiBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/main/BookendBatang/BookendBatang-SemiBold.otf) | OTF | 1.18 MB |
| [BookendBatang-SemiBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/main/BookendBatang/BookendBatang-SemiBold.ttf) | TTF | 1.41 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@a2df28fa82cfac616684f731501e72be3175dcac/BookendBatang/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@a2df28fa82cfac616684f731501e72be3175dcac/BookendBatang/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Bookend Batang";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@a2df28fa82cfac616684f731501e72be3175dcac/BookendBatang/BookendBatang-Regular.woff2") format("woff2");
}
@font-face {
  font-family: "Bookend Batang";
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@a2df28fa82cfac616684f731501e72be3175dcac/BookendBatang/BookendBatang-SemiBold.woff2") format("woff2");
}
```

## 사용 범위

| 용도 | 범위 | 조건 |
|---|---|---|
| 앱 임베딩 | 허용 | — |
| 상업 이용 | 허용 | — |
| 로고 | 허용 | — |
| 수정 | 미확인 | 공식 안내에 왜곡·변형 금지와 OFL 수정 가능 문구가 함께 있습니다. 수정·서브셋은 제작자 확인이 필요합니다. |
| 포장 | 허용 | — |
| 인쇄 | 허용 | — |
| 재배포 | 허용 | — |
| 서브셋 | 미확인 | 공식 안내에 왜곡·변형 금지와 OFL 수정 가능 문구가 함께 있습니다. 수정·서브셋은 제작자 확인이 필요합니다. |
| 영상 | 허용 | — |
| 웹 | 허용 | — |

세부 조건과 저작권 표시는 [LICENSE.txt](LICENSE.txt)를 확인하세요.

## 출처

원본 폰트: https://www.bookend.tech/font
