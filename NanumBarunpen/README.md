# 나눔 바른펜 — KoreaFonts

KoreaFonts에서 제공하는 설치용 원본 폰트와 웹폰트입니다. 폰트의 저작권은 원 제작자에게 있습니다.

- 제작자: 네이버
- 원본 배포처: https://hangeul.naver.com/font
- 라이선스: [LICENSE.txt](LICENSE.txt)

## 설치용 원본 다운로드

TTF·OTF 파일은 내려받은 뒤 운영체제에 설치해 사용할 수 있습니다. 가변 폰트는 파일명에 표시합니다.

| 파일 | 형식 | 크기 |
|---|---|---|
| [NanumBarunpen.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumBarunpen/NanumBarunpen.otf) | OTF | 5.03 MB |
| [NanumBarunpen.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumBarunpen/NanumBarunpen.ttf) | TTF | 10.52 MB |
| [NanumBarunpenBold.otf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumBarunpen/NanumBarunpenBold.otf) | OTF | 5.21 MB |
| [NanumBarunpenBold.ttf](https://github.com/koreafonts/fonts/raw/refs/heads/codex/fonts-archive-import/NanumBarunpen/NanumBarunpenBold.ttf) | TTF | 9.56 MB |

## 웹폰트 적용

KoreaFonts 소유 jsDelivr 배포 버전을 사용합니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-010-v2/NanumBarunpen/koreafonts.css">
```

```css
@import url('https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-010-v2/NanumBarunpen/koreafonts.css');
```

직접 선언하는 경우:

```css
@font-face {
  font-family: "Nanum Barunpen";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-010-v2/NanumBarunpen/NanumBarunpen.woff2") format("woff2");
}
@font-face {
  font-family: "Nanum Barunpen";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/koreafonts/fonts@cdn-010-v2/NanumBarunpen/NanumBarunpenBold.woff2") format("woff2");
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

원본 폰트: https://hangeul.naver.com/font
원본 버전: https://github.com/fonts-archive/NanumBarunpen/tree/da026430bc2bcc465a41c131df1c6053fd4a0c48
기존 이용 범위 자료: https://fonts.taedonn.com/post/Nanum+Barunpen
