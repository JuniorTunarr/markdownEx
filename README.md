# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

<!-- 띄어쓰기 2번이 작동하지 않는다면 br태그 -->

동해물과 백두산이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세 <br/>

# 강조(Emaphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**. 
~~취소선~~  
<u>밑줄</u>

# 목록(List)

<!-- 숫자 1번만 넣으면 ol이 적용됨 -->
<!-- 2번 들여쓰기해서 내부에 ol만들 수 있음 -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요한 목록
- 순서가 필요한 목록
  - 순서가 필요한 목록
- 순서가 필요한 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>
[GOOGLE](https://google.com). 

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>
[NAVER](https://naver.com "NAVER로 이동!"). 

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)

<!-- ![대체텍스트](링크) -->

![다음](https://t1.daumcdn.net/daumtop_chanel/op/20200723055344399.png)

[![다음](https://t1.daumcdn.net/daumtop_chanel/op/20200723055344399.png)](https://www.daum.net/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전)

> 인용문 작성
>
> > 중첩된 인용문
> >
> > > 3중첩된 인용문 1
> > > 3중첩된 인용문 2

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > ul {
  position: absolute;
  top: 20px;
}
```

```javascript
function func() {
  let a = "123";
  return a;
}
```

```bash
$ git commit -m "마크다운 연습"
```

```plaintext
내일도 서울과 청주의 한낮 기온 28도로 중부 지역은
낮더위가 계속되겠구요.
전국적으로 자외선이 강하겠습니다.
```

# 표(Table)

position 속성

<!-- 표의 머리부분  -->
<!-- 기본적으로 왼쪽 정렬, :--: 중앙, --: 오른쪽 -->

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      0 |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

# 원시 HTML(Raw HTML)

내일 아침 최저 기온 <span style="text-decoration: underline;">서울</span>이 19도, <u>대구</u>가 15도가 예상되구요,
한낮 기온은 서울이 28도, 부산이 21도 안팎을 보이겠습니다.

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 수평선(Horizontal Rule)

---

---

---
