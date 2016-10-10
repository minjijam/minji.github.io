# minji.github.io


<!-- #하나는 h1 
두개는 h2  -->

## Markdown 문법 사용법

### 제목 

```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>
```

<!-- (```) 뜻은 화면에 내가 코드를 어떻게 썼는지 웹에서 보이게 해주는 기능이다. -->

# Markdown H1
## Markdown H2
### Markdown H3
#### Markdown H4
##### Markdown H5
###### Markdown H6

### 목록

<!-- 
ul>li{item$}*3 
>은 자식요소
$은 순차적으로 숫자를 내려가게 해줌 
*은 몇개 곱하기  -->

```html 
<ul>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ul>

<ol>
	<li>item</li>
	<li>item</li>
	<li>item</li>
</ol>
```

<!-- 비순차목록은 - 으로만 하면 된다.   -->
비순차목록
-item1
-item2
-item3

<!-- 순차목록은 1. 만 쓰면 된다.  -->
순차목록 
1. item1
1. item2
1. item3

-

# To do
- [x] Study Markdown
- [ ] Make "index.html"

<!-- [ ] 안에 x 를 넣으면 바로 체크박스가 생김  -->

### 이미지

```html
<img src="http://file.instiz.net/data/cached_img/upload/6/0/e/60eefe85012c207d6ad084a63bc387eb.png" alt="ebichu">
```

<!-- 콘트롤 판넬 부르는게 cmmnd + shift + P
누르고 Emmet update image size 를 설치한다 
그리고 ctrl + shift + I 를 누르면 바로 이미지의 사이즈가 적어진다. -->

<!-- 숫자들 바로 나누기 곱하기 하려면 예를들어서> 300/3 을 쓰고 
수식을 붙이고 cmmnd + shift + Y 를 누르면 된다. -->

<img src="http://file.instiz.net/data/cached_img/upload/6/0/e/60eefe85012c207d6ad084a63bc387eb.png" alt="ebichu" width="128.67" height="97.33">

<!-- <!> 표 뒤에 () 괄호 안에 이미지 링크를 적으면 이미지가 나온다 [ ]대괄호 안에는 파일 이름을 적어야한다  -->

![ebichu] (http://file.instiz.net/data/cached_img/upload/6/0/e/60eefe85012c207d6ad084a63bc387eb.png)



