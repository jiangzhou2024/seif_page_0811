html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>响应式新闻网页</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

       .header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

       .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

       .news-item {
            border: 1px solid #ddd;
            padding: 10px;
            margin-bottom: 20px;
        }

       .news-title {
            font-size: 20px;
            font-weight: bold;
        }

       .news-date {
            color: #888;
            font-size: 12px;
        }

       .news-content {
            margin-top: 10px;
        }

        /* 响应式设计 */
        @media screen and (max-width: 768px) {
           .container {
                padding: 10px;
            }

           .news                font-size: 16px;
            }
        }
    </style>
</head>

<body>
    <div class="header">
        <h1>新闻头条</h1>
    </div>
    <div class="container">
        <div class="news-item">
            <div class="news-title">重大新闻事件标题</div>
            <div class="news-date">2024 年 9 月 14 日</div>
            <div class="news-content">这里是新闻的详细内容...</div>
        </div>
        <!-- 更多新闻条目 -->
    </div>
</body>

</html>

