# 제목(Header)

# 제목 1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(paragraph)
<!-- p태그로 인식 -->
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세 

# 줄바꿈(Line Bveaks)
<!-- 줄바꿈이 두번되면 <br>처리가 된다
줄바꿈이 안되면 <br>를 넣으면 된다.-->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이탤릭_    
**두껍게**  
**_이탤릭 = 두껍게_**  
~~취소선~~  
<u>밑줄</u>


# 목록(List)
<!-- ol태그 사용 -->
1. 순서가 필요한 목록  
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

<!-- ul태그 사용 -->
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>  
[NAVER](https://naver.com "NAVER로 이동")

<a href="https://naver.com" title="NAVER로 이동" target="_black">NAVER</a>  


# 이미지(Image)
![]()
![츄잉](https://www.chuing.net/images/head_01.gif)

[![츄잉](https://www.chuing.net/images/head_01.gif)](https://www.chuing.net/images/head_01.gif)


# 인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어사전)

> 인용문을 작성하세요!  
>> 중첩된 인용문  
>>> 중중첩된 인용문1  
>>> 중중첩된 인용문2  
>>> 중중첩된 인용문3  

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블럭(block)) 코드 강조

```html
<a href="https://naver.com" title="NAVER로 이동" target="_black">NAVER</a>   
```

```css
.list > li {
  postion: absolute:
  top: 40px;
}
```

```js
function func(){
  var a= 'AAA';
  return a;
}
```
```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
```

# 표(Table)

position 속성
<!-- 정렬은 왼쪽이 기본 -->
값 | 의미 | 기본값
-- | :--: | --:
static | 기준 없음 | O  
relative | 요소 자신 | X
absolute | 위치상 부모요소 | X
fixed |  뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER 이동" target="_blank"> NAVER</a>
***
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평성(Horizontal Rule)

---

***

___

