<h1>HTML</h1>

`tag` : HTML 내에서 요소가 어떤 성질을 가지는지 정의하는 HTML의 문법

---------

### tag를 사용하는 법

```html
<tag_name> text </tag_name>
```

---------

<h3>tag 종류</h3>

#### 가장 많이 사용하는 태그
<p>
```html
<!doctype html>
<html>
<head>
    <title> HTML-Tutorial</title>
    <meta carset="utf-8">
</head>

<body>

</body>
</html>
```

<title> HTML-Tutorial</title>
<meta carset="utf-8">

```html
<!doctype html> : 이 문서가 html문서라는 관용적인 문구
```

```html
<html> : html 문서는 이 태그 안에 반드시 있어야한다.
```

```html
<head> : 제목에 해당하는 태그들을 감싼다
```

```html
<body> : 본문에 해당하는 태그들을 감싼다.
```

```html
<title> : 이 문서를 대표하는 제목
```

```html
<meta> : 인코딩을 설정할 수 있다.
```



<h4>글꼴(Font)</h4>

```html
<strong>bold</strong>   <!-- 굵게 -->
<u>underline</u>        <!-- 밑줄 -->
```

<strong>bold</strong>  
<u>underline</u>

-----
<br>

<h4>제목(header)</h4>

```html
<h1>heading1</h1> <!--제목1-->
<h2>heading2</h2> <!--제목2-->
<h3>heading3</h3> <!--제목3-->
<h4>heading4</h4> <!--제목4-->
<h5>heading5</h5> <!--제목5-->
<h6>heading6</h6> <!--제목6-->
```

<h1>heading1</h1>
<h2>heading2</h2>
<h3>heading3</h3>
<h4>heading4</h4>
<h5>heading5</h5>
<h6>heading6</h6>

#### 이미지

```html
<img src="img-address">
```

<img src="https://images.unsplash.com/photo-1534137667199-675a46e143f3?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=610613600d356ae190e368d73c81e055&auto=format&fit=crop&w=334&q=80" width=200>

### 부모-자식 관계가 있는 태그

#### ul - li태그 (list, 순서X)
```html
<ul>
    <li>egoing</li>
    <li>k8805</li>
    <li>youbin</li>
</ul>
```
<ul>
    <li>egoing</li>
    <li>k8805</li>
    <li>youbin</li>
</ul>

#### ol - li 태그 (순서O)
```html
<ol>
    <li>HTML<br></li>
    <li>CSS<br></li>
    <li>JavaScript<br></li>
</ol>
```

<ol>
    <li>HTML<br></li>
    <li>CSS<br></li>
    <li>JavaScript<br></li>
</ol>

#### table
```html
<table>
    <tr>
        <td>head</td>
        <td>98.1%</td>
    </tr>
    <tr>
        <td>body</td>
        <td>97.9%</td>
    </tr>
    <tr>
        <td>html</td>
        <td>97.9%</td>
    </tr>
</table>
```
<table>
    <tr>
        <td>head</td>
        <td>98.1%</td>
    </tr>
    <tr>
        <td>body</td>
        <td>97.9%</td>
    </tr>
    <tr>
        <td>html</td>
        <td>97.9%</td>
    </tr>
</table>

#### ★링크★

```html
<a href="https://www.naver.com" title="네이버">네이버로 가는 링크</a>
```

<a href="https://www.naver.com" title="네이버">네이버로 가는 링크</a>