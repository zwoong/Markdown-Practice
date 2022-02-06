# 재목(Header)

# 제목 1
## 제목 2 
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

<br/>

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록 
하느님이 보우하나 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록 <br/>
하느님이 보우하나 우리나라 만세 <br/>
무궁화 삼천리 화려강산 <br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_ <br/> 
**두껍게** <br/>
**_이텔릭 + 두껍게_** <br/>
~~취소선~~ <br/>
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목룍
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목룍
    1. 순서가 필요한 목룍
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br/>

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<!-- 마크다운 문법에는 a태그에 target 기능을 지원해주지는 않음 -->
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<br/>

# 이미지

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장. <br/>
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1 <br/>
>>> 중중첩된 인용문 2 <br/>
>>> 중중첩된 인용문 3 <br/>

<br/>

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 <br/>
`background-image` 속성으로 요소에 배경 <br/>
이미지를 삽입할 수 있습니다.

<br/>

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
    position: absolute;
    top: 40px;
}
```

```javascript
function func() {
    var a = 'AAA';
    return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

<br/>

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

<br/>

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="NAVER로 이동!" 
target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

<br/>

# 수평선(Horizontal Rule)

---

***

___