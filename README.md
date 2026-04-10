<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AFLL 的个人主页</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft YaHei', sans-serif;
        }
        body {
            background: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .container {
            text-align: center;
            max-width: 800px;
        }
        h1 {
            font-size: 3rem;
            color: #58a6ff;
            margin-bottom: 1rem;
        }
        .intro {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            color: #8b949e;
        }
        .links {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
        }
        .link {
            padding: 0.8rem 1.5rem;
            border: 1px solid #30363d;
            border-radius: 6px;
            color: #c9d1d9;
            text-decoration: none;
            transition: all 0.3s;
        }
        .link:hover {
            background: #30363d;
            border-color: #8b949e;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>你好，我是 AFLL</h1>
        <p class="intro">一名热爱技术、学习 Linux 与 AI 的开发者</p>
        <div class="links">
            <a href="#" class="link">我的博客</a>
            <a href="#" class="link">GitHub</a>
            <a href="#" class="link">联系方式</a>
        </div>
    </div>
</body>
</html>
