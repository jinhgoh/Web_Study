# CSS

### Reference
<a href="https://www.youtube.com/watch?v=-OWx2vM4tLI&list=PLuHgQVnccGMAnWgUYiAW2cTzSBywFO75B&index=1"> 생활코딩 </a>
<br><br>

### Lecture3_Intro
 - <style> </style> 태그 사용 

#### index.html
```html
<!DOCTYPE html> 

<html>
    <head>
        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  
        <style>
            a {
                color:red;
            }
        </style>
    </head>

    <body>       
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>

        <h2>선행학습</h2>

        본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 
        이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다. 

        <h2>웹애플리케이션 만들기</h2>

        위의 수업에서는 웹을 구성하고 있는 여러기술을 얕고 넓게 배웁니다. 각각의 기술들이 어떻게 관계하고 있는지를 알려드리는 것이 위 수업의 목적입니다. 
    </body>
</html>
```
#### 1.html
```html
<!DOCTYPE html> 
<!-- 어떤 버전을 따르는지에 대한 적당한 DocType 선언 -->

<html>

    <head>

        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  

    </head>



    <body>
        
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>


        <h2> 기술 소개 </h2>

        HTML은 HyperText Markup Language의 약자로서 웹페이지를 만드는 언어입니다.

    </body>

</html>
```

#### 2.html
```html
<!DOCTYPE html> 
<!-- 어떤 버전을 따르는지에 대한 적당한 DocType 선언 -->

<html>

    <head>

        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  

    </head>



    <body>
        
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>


        <h2> 기본 문법 </h2>

        HTML의 기본 문법

    </body>

</html>
```

#### 3.html
```html
<!DOCTYPE html> 
<!-- 어떤 버전을 따르는지에 대한 적당한 DocType 선언 -->

<html>

    <head>

        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  

    </head>



    <body>
        
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>


        <h2> 하이퍼텍스트와 속성 </h2>

        하이퍼텍스트와 속성

    </body>

</html>
```

#### 4.html
```html
<!DOCTYPE html> 
<!-- 어떤 버전을 따르는지에 대한 적당한 DocType 선언 -->

<html>

    <head>

        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  

    </head>



    <body>
        
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>


        <h2> 리스트와 태그의 중첩 </h2>

        리스트와 태그의 중첩

    </body>

</html>
```

### Leture 04~06_Basic1
 - 1.html ~ 4.html은 동일
 - style 태그대신 style 속성을 사용
 
#### index.html
```html
<!DOCTYPE html> 

<html>
    <head>
        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  
        <style>
            a {
                color:red;
                text-decoration: none;
            }
            h1 {
                font-size: 60px;
                text-align: center;
            }
        </style>
    </head>

    <body>       
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html">기술 소개 </a></li>
            <li> <a href="2.html" style="color:Blue; text-decoration: underline;">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>

        <h2>선행학습</h2>

        본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 
        이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다. 

        <h2>웹애플리케이션 만들기</h2>

        위의 수업에서는 웹을 구성하고 있는 여러기술을 얕고 넓게 배웁니다. 각각의 기술들이 어떻게 관계하고 있는지를 알려드리는 것이 위 수업의 목적입니다. 
    </body>
</html>
```

<img src="https://user-images.githubusercontent.com/50551349/106885899-9cae0300-6726-11eb-84fe-e7da18d7b8c8.png" width="500">

### Lecture7_Basic2
 - 기본은 검은색
 - 한번 방문한 곳은 회새
 - 현재 위치는 빨간색
 - class에서는 가까이 있는 명령이 더 큰 영향력을 갖는다.
 - 영향력 : id > class > tag (구체적인 것이 우선순위가 높다.)
 - id는 중복X
 - 
 

#### index.html
```html

<!DOCTYPE html> 

<html>
    <head>
        <title>HTML - 수업 소개</title>
        <meta charset = "utf-8">  
        <style>
            a {
                color:black;
                text-decoration: none;
            }
            .saw {
                color:gray;
            }
            #active {
                color:red;
            }
            
            h1 {
                font-size: 60px;
                text-align: center;
            }
        </style>
    </head>

    <body>       
        <h1> <a href="index.html"> HTML </a></h1>

        <ol>
            <li> <a href="1.html" class="saw">기술 소개 </a></li>
            <li> <a href="2.html" class="saw" id="active">기본 문법 </a></li>
            <li> <a href="3.html">하이퍼텍스트와 속성 </a></li>
            <li> <a href="4.html">리스트와 태그의 중첩 </a></li>
        </ol>

        <h2>선행학습</h2>

        본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 
        이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다. 

        <h2>웹애플리케이션 만들기</h2>

        위의 수업에서는 웹을 구성하고 있는 여러기술을 얕고 넓게 배웁니다. 각각의 기술들이 어떻게 관계하고 있는지를 알려드리는 것이 위 수업의 목적입니다. 
    </body>
</html>
```
