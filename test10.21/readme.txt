第一题:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1 id="h1"></h1>
    <script>
        var h1 = document.getElementById('h1');
        var a = '一字符';
        var b = '二字符';
        var c = a.concat(b);
        h1.innerHTML=c;
    </script>
</body>
</html>

第二题:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1 id="h2"></h1>
    <script>
        var h2 = document.getElementById('h2');
        var a = String(prompt('请输入要存入的钱(单位:万):'));
        h2.innerHTML=a.padEnd(6,'0');
    </script>
</body>
</html>

第三题:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1 id="h3"></h1>
    <script>
        var h3 = document.getElementById('h3');
        var a = 79387.348;
        console.log(Number.parseInt(a));
    </script>
</body>
</html>

第四题:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1 id="h4"></h1>
    <img src="img/head/icon/1.jpg" alt="" id="img">
    <script>
        var h4 =document.getElementById('h4');
        var img =document.getElementById('img');
        h4.innerHTML=(img.src);
    </script>
</body>
</html>

第五题:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1 id="h1"></h1>
    <h4 id="h4"></h4>
    <script>
        var h1 = document.getElementById('h1');
        var h4 = document.getElementById('h4');
        var a = prompt('请输入验证码');
    </script>
</body>
</html>
