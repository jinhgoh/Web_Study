# JavaScript

### Reference : <a href="https://www.youtube.com/watch?v=dPRtcRwKo-Y&list=PLuHgQVnccGMBB348PWRN0fREzYcYgFybf&index=1"> 생활코딩 </a>
<br>

### Lecture2_Purpose
 <img src="https://user-images.githubusercontent.com/50551349/106978074-d884af00-679e-11eb-8d8a-a9be3e582b83.png" width="500">
 
### Lecture3_Tag
 - JavaScript는 동적으로 작동한다.
 - 계산기도 동작한다.
 
#### example.html
```html
<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8">
        <title>

        </title>
    </head>
    <body>
        <h1>JavaScript</h1>
        <script>
            document.write('hello world');
            document.write(1+1);
        </script>
    </body>
</html>
```
 
### Lecture4~5_Event & Console
 - 콘솔에서 직접 실행할 수도 있다.
 <img src="https://user-images.githubusercontent.com/50551349/106979225-3a461880-67a1-11eb-8a0b-eff1e787ccba.png" width="500">
 

#### example.html
```html
<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8">
        <title>

        </title>
    </head>
    <body>
        <input type="button" value="hi" onclick="alert('hi')" >
        <input type="text" onchange="alert('changed')">
        <input type="text" onkeydown="alert('key down!')">
    </body>
</html>
```
