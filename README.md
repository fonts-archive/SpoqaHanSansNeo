# 스포카 한 산스 네오

[배포처 바로가기](https://spoqa.github.io/spoqa-han-sans/ko-KR/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Spoqa Han Sans Neo`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: "Spoqa Han Sans Neo";
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Thin.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Thin.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Thin.ttf")
      format("truetype");
}
@font-face {
  font-family: "Spoqa Han Sans Neo";
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Light.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Light.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Light.ttf")
      format("truetype");
}
@font-face {
  font-family: "Spoqa Han Sans Neo";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Regular.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Regular.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Regular.ttf")
      format("truetype");
}
@font-face {
  font-family: "Spoqa Han Sans Neo";
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Medium.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Medium.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Medium.ttf")
      format("truetype");
}
@font-face {
  font-family: "Spoqa Han Sans Neo";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Bold.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Bold.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/SpoqaHanSansNeo-Bold.ttf")
      format("truetype");
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/subsets/SpoqaHanSansNeo-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SpoqaHanSansNeo/subsets/SpoqaHanSansNeo-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Spoqa Han Sans Neo", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
본 폰트 소프트웨어는 SIL 오픈 폰트 라이선스 버전 1.1에 따라 라이선스 취득을 하였습니다.
본 라이선스는 하단에 복사되었고 http://scripts.sil.org/OFL의 FAQ란 에서도 열람가능 합니다.

SIL 오픈 폰트 라이선스
버전 1.1 (2007년 2월 26일)

본 폰트 소프트웨어를 사용하도록 허가 받은 개인/기업/단체 누구라도 다음 명시된 조건에 따라
폰트 소프트웨어의 수정 혹은 수정되지 않은 복사본을 무료로 사용, 연구, 복사, 통합, 삽입, 수정,
재배포할 수 있도록 허가합니다.

본 폰트 소프트웨어의 원본 혹은 수정본은 상기 저작권 안내와 본 라이선스에 대한 내용을 포함하는
경우에는 다른 소프트웨어와 함께 묶이거나 재배포 혹은 판매가 가능합니다. 이는 독립 텍스트 파일과
가독성이 있는 헤더 혹은 유저가 용이하게 열람 가능한 이상 텍스트파일 혹은 이진파일 내 기계가 읽을
수 있는 메타데이터 형태를 모두 의미 합니다.

본 폰트 소프트웨어의 어떠한 수정본도 동일한 저작권자가 명시적 허가서를 부여하지 않는 한 저작권이
있는 폰트명을 사용해서는 안 됩니다. 본 제한 사항은 유저들에게 제공된 기존 폰트명을 뜻합니다.

본 폰트 소프트웨어의 저작권자 혹은 저자의 이름은 그들의 명시적 서면 허가가 있거나 또는 그들의 공헌을
인정하기 위한 경우를 제외하고는 수정본에 대한 사용을 유도,추천 혹은 광고하기 위한 목적으로 사용할 수
없습니다.

본 폰트 소프트웨어는 전체나 부분, 혹은 수정 여부에 상관없이 본 라이선스 하에 배포가 되어야 하며 기타
다른 라이선스 하에서는 배포를 할 수 없습니다. 폰트에 대한 요구조건은 이 라이선스 하에서만 유효하며
이 라이선스 하에 있기 위한 폰트에 대한 요구사항은 본 폰트 소프트웨어를 사용해 제작한 어떠한 문서에도
적용되지 않습니다.
```
