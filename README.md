<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <title>墩墩的30岁生日庆祝</title>
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>墩墩的30岁生日</strong></li>
        </ul>
        <ul>
            <li><a href="#">首页</a></li>
            <li><a href="#">相册</a></li>
            <li><a href="#" role="button">留言</a></li>
        </ul>
    </nav>
    <main class="container">
        <div class="grid">
            <section>
                <hgroup>
                    <h2>生日快乐，墩墩！</h2>
                    <h3>欢迎来到30岁的世界</h3>
                </hgroup>
                <p>在这特别的日子里，我们一起庆祝你的成长与成就，祝愿你未来的日子充满快乐和惊喜。</p>
                <figure>
                    <img src="https://source.unsplash.com/random/800x600?birthday" alt="生日庆祝" />
                    <figcaption><a href="https://unsplash.com" target="_blank">图片来源: Unsplash</a></figcaption>
                </figure>
                <h3>特别的祝福</h3>
                <p>愿你的每一天都像今天一样特别，充满欢笑和美好的回忆。</p>
                <h3>分享快乐</h3>
                <p>请在下方留下你的祝福，让墩墩感受到你的爱和关怀。</p>
            </section>
        </div>
    </main>
    <!-- 订阅区域，可用于留言 -->
    <section aria-label="Subscribe example">
        <div class="container">
            <article>
                <hgroup>
                    <h2>留下你的祝福</h2>
                    <h3>分享你的美好祝愿</h3>
                </hgroup>
                <form class="grid">
                    <input type="text" id="firstname" name="firstname" placeholder="你的名字" aria-label="你的名字" required />
                    <input type="email" id="email" name="email" placeholder="你的邮箱" aria-label="你的邮箱" required />
                    <button type="submit" onclick="event.preventDefault()">发送祝福</button>
                </form>
            </article>
        </div>
    </section>
    <footer class="container">
        <small><a href="#">关于我们</a> • <a href="#">联系方式
