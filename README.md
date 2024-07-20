# 좋은이웃체

[배포처 바로가기](https://blog.naver.com/gnikor/222893018907)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Good Neighbors`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Good Neighbors';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Good Neighbors';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoodNeighbors/GoodNeighbors-Bold.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Good Neighbors", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
개인 및 기업 사용자를 포함한 
⭐ 모든 분이 사용 가능하며, 
 
글꼴 자체를 판매하는 것을 제외한 
⭐ 상업적으로 활용 가능합니다.
```
