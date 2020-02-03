### Markdown 연습히기
* * *
## Markdown은 왜 사용할까?
Github Repository에 들어가면 보이는 README.md 파일은 작성자가 Repository에 대한 설명을 적어둔 것으로
나중에 우리가 github에 게시물을 올리게 될 경우 작성해야하는 것이다. 하지만 이 README파일은 일반 text문서와는 달리
Markdown이라는 언어로 쓰이기 때문에 알아둘 필요가 있다.

## 1. HEADER(제목)
   ```markdown
    # h1
    ## h2
    ### h3
    #### h4
    ##### h5
    ###### h6
    ####### h7 -> 지원하지 않음
   ```

 # h1
 ## h2
 ### h3
 #### h4
 ##### h5
 ###### h6
 
 - ##### h1과 h2의 경우 다음과 같은 방법으로도 나타낼수 있다
   ```markdown
   h1
   ===
   h2
   ---
   ```
   h1
   ===
   h2
   ---

## 2. 들여쓰기
   ```markdown
  > This is a first blockqute.
   >> ## h2
   >>> ``code작성``
   ```
> This is a first blockqute.
>> ## h2
>>> ``code작성``

## 3. 목록
```markdown
1. a
2. b
3. c
```
1. a
2. b
3. c
---
```markdown
* a
  * b
    * c

+ a
  + b
    + c

- a
  - b
    - c

* a
  + b
    - c
```
* a
  * b
    * c

+ a
  + b
    + c

- a
  - b
    - c

* a
  + b
    - c

## 4. codeblock
```markdown
`인라인 코드`

```여러줄의 code```
 
```
`인라인 코드`

```
여러줄의 코드
```
 - Code Highlight
  ```markdown
   ```java(사용한 언어 이름 넣기)
   let sum = (first, last) => {
   return first + last;
   };
   sum(10, 20);
   ```　

   ```python
   num = 10
   print(num)
   ```　
  ```

   ```java
   let sum = (first, last) => {
   return first + last;
   };
   sum(10, 20);
   ```   

   ```python
    num = 10
    print(num)
   ```
## 5.수평선
```markdown
***
-----
__ __ __ __ __ __
```
***
-----
__ __ __ __ __ __ 

## 6. 링크
```markdown
[인라인 링크](https://github.com/wotjd0715/markdown)

<https://github.com/wotjd0715/markdown>

[markdown]:(https://github.com/wotjd0715/markdown)
```
[인라인 링크](https://github.com/wotjd0715/markdown)

<https://github.com/wotjd0715/markdown> 

[markdown]: (https://github.com/wotjd0715/markdown)

```markdown
![이미지 설명](이미지 링크)
![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)
이미지에 링크를 걸고 싶을 경우
[![이미지 설명](이미지 링크)](연결하고자하는 url "마우스 오버 시 나타낼 링크 title")
[![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg"이미지 무료 사이트 pixabay")
```
![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)
* * *
[![고양이애옹](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg)](https://cdn.pixabay.com/photo/2019/03/13/08/29/cat-4052454_1280.jpg"이미지 무료 사이트 pixabay")

## 7. 폰트
```
__굵게__
**굵게**
_기울여 쓰기_
*기울여 쓰기*
~~취소선~~
```
__굵게__

**굵게**

_기울여 쓰기_

*기울여 쓰기*

~~취소선~~

## 8. Table
```markdown
| 이름 | 나이 | 생일 |
|:----------|:----------:|----------:|
| 박재성 | 24 | 07.15 |
| 홍길동 | 153 | 08.31 |
| 김상덕 | 43 | 08.09 |
```
| 이름 | 나이 | 생일 |
|:----------|:----------:|----------:|
| 박재성 | 24 | 07.15 |
| 홍길동 | 153 | 08.31 |
| 김상덕 | 43 | 08.09 |

## 9. Checkbox
```markdown
- [ ] 빨래
- [x] 과제
```
- [ ] 빨래
- [x] 과제

## 참고링크
1. <https://velog.io/@yuuuye/velog-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4MarkDown-%EC%9E%91%EC%84%B1%EB%B2%95>
2. <https://gist.github.com/ihoneymon/652be052a0727ad59601#22-blockquote>
