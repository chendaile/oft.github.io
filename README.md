<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>简单HTML页面</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        section {
            margin: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #222;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>欢迎来到我的网站</h1>
    </header>

    <section>
        <h2>关于我</h2>
        <p>这是一段关于我的介绍文字。这里可以写一些个人信息或兴趣爱好。</p>

        <h3>我的图片</h3>
        <img src="https://via.placeholder.com/600x400" alt="示例图片">

        <h3>更多信息</h3>
        <p>如果你想了解更多内容，可以访问我的 <a href="https://www.example.com" target="_blank">博客</a>。</p>
    </section>

    <footer>
        <p>&copy; 2024 我的个人网站</p>
    </footer>

</body>
</html>
