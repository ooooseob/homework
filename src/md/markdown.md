# 마크다운 문법 정리

## 마크다운이 뭐지?

마크다운은 2004년에 John Gruber, Aaron Swartz 가 개발한 문법이라고 한다.

---

### 특성

- 간결함
  - 특수 기호를 사용해 간단한 서식을 지정할 수 있다.
- 가독성
  - HTML보다 직관적인 문법이라, 원본 텍스트 그대로 읽어도 쉽게 분석이 가능하다.
- 활용성
  - 코드 작성이 간편해 README 파일, 기술문서, 블로그 포스트, 노트 정리 등 다양하게 사용된다.
- 플랫폼
  - GitHub, Notion, Obsidian, VS Code 등 다양한 도구에서 지원된다.

---

### 마크다운 기본 문법

### 1.제목

마크다운에 # 기호는 제목을 작성한다. #의 개수에 따라 크기가 달라진다.

# 제목1

## 제목2

### 제목3

#### 제목 4

##### 제목 5

###### 근데 왜 #,## 여기만 밑줄이 생기지

```
# 제목1
## 제목2
### 제목3
#### 제목 4
##### 제목 5
###### 근데 왜 #,## 여기만 밑줄이 생기지
```

---

### 2.목록

목록은 순서 있는 목록과 순서없는 목록이 있고, 서로 섞어서 사용도 가능하다.

- \* 또는 \-를 사용해서 순서 없는 목록을 만든다.
  - 들여쓰기를 하면 모양이 바뀐다.
    - 이렇게

1. 숫자를 사용해서 순서 있는 목록을 만든다.
2. 숫자는 왜 들여쓰기가 안되니(탭으로 들여쓰기 하는게 아닌가?)

```
### 2.목록
목록은 순서 있는 목록과 순서없는 목록이 있고, 서로 섞어서 사용도 가능하다.
* \* 또는 \-를 사용해서 순서 없는 목록을 만든다.
  * 들여쓰기를 하면 모양이 바뀐다.
    * 이렇게

1. 숫자를 사용해서 순서 있는 목록을 만든다.
  2. 숫자는 왜 들여쓰기가 안되니(탭으로 들여쓰기 하는게 아닌가?)
```

---

### 3. 코드 블록

` 백틱 세 개를 사용하면 코드 블록을 만들 수 있다.

```HTML
<h1>안녕하세요</h1>
```

---

### 4. 인용문

\> 기호를 사용해서 인용문을 만들 수 있다.

> 여기는 인용문
>
> > 이것도 인용문
> >
> > > \> 기호가 늘어날 수록 중첩이 된다.
> > >
> > > > 어디까지?
> > > >
> > > > > 본인도 모름
> > > > >
> > > > > > 큰일이다
> > > > > >
> > > > > > > 다된다... 라고 하자마자 7개가 끝이다.

---

### 5.링크

- 웹사이트 링크, 이미지 삽입 링크도 된다.

<br>[멋쟁이사자처럼](https://bootcamp.likelion.net/)

```
[멋쟁이사자처럼](https://bootcamp.likelion.net/)
```

- 이미지를 삽일할 때는 \!\[ \] \( \) 형식을 사용한다.

![모바일 배경화면](./../assets/ooooseob_wallpaper3.jpg)

```
![모바일 배경화면](./../assets/ooooseob_wallpaper3.jpg)
```

### 6. 강조

혼합 사용이 가능하다.

- 볼드 주기 : \*\*볼드\*\*
- 이텔릭 : \*이텔릭\* 또는 \_이텔릭\_
- 취소선 : \~\~취소선\~\~

<br>

**볼드** **_이텔릭_** **_~~취소선~~_**

```
**볼드** ***이텔릭*** ***~~취소선~~***
```

---

### 7. 수평선

\-, \*, \_ 을 3개 이상 사용하면 수평선이 넣어진다.<br>
단 \-를 사용하는 경우 Header로 인식할 숭 이싿고 하니 이전 라인은 비워두어야 한다.

---

수평선

---

만들기

---

```
---
수평선
******
만들기
_____________
```
