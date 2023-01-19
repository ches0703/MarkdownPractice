# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

```md
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```



# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
무궁화 삼천리 화려강산
대한 사람 대한으로 길이 보전하세

```md
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
무궁화 삼천리 화려강산
대한 사람 대한으로 길이 보전하세
```



# 줄바꿈(Line Breaks) : \<br> or "space" 두번

동해물과 백두산이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br>
대한 사람 대한으로 길이 보전하세  

```md
동해물과 백두산이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br>
대한 사람 대한으로 길이 보전하세  
```



# 강조(Emphasis)

_Italic : \_(Italic을 적용할 문장)\__<br>
**Bold : \*\*(Bold를 적용할 문장)\*\***<br>
**_Italic + Bold : \*\*\_(Italic + Bold를 적용할 문장)\_\*\*_**<br>
~~Strikethrough : \~\~(Strikethrough를 적용할 문장)\~\~~~<br>
<u>Underscore : \<u> 태그 사용</u>

```md
_Italic : \_(Italic을 적용할 문장)\__<br>
**Bold : \*\*(Bold를 적용할 문장)\*\***<br>
**_Italic + Bold : \*\*\_(Italic + Bold를 적용할 문장)\_\*\*_**<br>
~~Strikethrough : \~\~(Strikethrough를 적용할 문장)\~\~~~<br>
<u>Underscore : \<u> 태그 사용</u>
```



# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요없는 목록
- 순서가 필요없는 목록
    - 순서가 필요없는 목록
- 순서가 필요없는 목록

```md
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요없는 목록
- 순서가 필요없는 목록
    - 순서가 필요없는 목록
- 순서가 필요없는 목록
```



# 링크(Link)
- 기본적인 출력 :  
    <a herf="https://www.google.com/">Google1</a>
    ```md
    <a herf="https://www.google.com/">Google</a> 
    ```
    [Google2](https://www.google.com/)
    ```md
    [Google](https://www.google.com/)
    ```

- title 값 존재시 :  
    <a herf="https://www.naver.com/" title="Naver">Naver1</a>
    ```md
    <a herf="https://www.naver.com/" title="Naver">Naver1</a>  
    ````
    [Naver2](https://www.naver.com/ "Naver")
    ```md
    [Naver2](https://www.naver.com/ "Naver")
    ```



# 이미지(Image)

- \[대체 텍스트](이미지 링크) : 이미지 바로가기 링크  
    [Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)
    ```md
    [Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)
    ```

-  \![대체 텍스트](이미지 링크) : 이미지 출력  
    ![Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)
    ```md
    ![Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)
    ```

- \[![대체 텍스트](이미지 링크)](사이트 링크) : 이미지에 링크 추가  
    [![Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)](https://www.yu.ac.kr/main/index.do)
    ```md
    [![Yeungnam](https://portal.yu.ac.kr/sso/image/logo.png)](https://www.yu.ac.kr/main/index.do)
    ```




# 인용문(BlcakQuote)
> 인용문 : 남의 말이나 글에서 직접 또는 간저으로 따온 문장
(네이버 국어 사전)
>> 인용문 중첩
```md
> 인용문 : 남의 말이나 글에서 직접 또는 간저으로 따온 문장
(네이버 국어 사전)
>> 인용문 중첩
```



# 인라인(Inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
```md
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
```



# 블록(Block) 코드 강조
다음과 같이 사용함
> \```(Language)  
code    
\```

Example :
```md
<a herf="https://www.google.com/">Google</a>
```



# 표(Table)

position 속성
값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소자신 | X
absoluste | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

```md
position 속성
값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소자신 | X
absoluste | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
```



# 원시 HTML(Raw HTML)

Markdown의 일부 문법이 적용이 안되는 경우가 있음(ex 줄바꿈을 위한 space 두번) -> 태그를 활용하여 이를 방지할 수 있음  

>동해물과 <u>백두산</u>이 마르고 닳도록<br>
>하느님이 보우하사 <span style="text-decoration: >underline;">우리나라</span> 만세

```md
동해물과 <u>백두산</u>이 마르고 닳도록<br>
하느님이 보우하사 <span style="text-decoration: underline;">우리나라</span> 만세
```

또한 HTML문법을 사용하여 style을 사용 할 수도 있음



# 수평선(Horizontal Rule)
---
***
___

```md
---
***
___
```