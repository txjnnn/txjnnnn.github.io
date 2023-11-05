# txjnnnn.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>自我介紹網站</title>
    <style>
        /* 樣式與您先前提供的相同，這裡不再重複 */
    </style>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link rel="stylesheet" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
    <script>
        $(document).ready(function() {
            // 當點擊專輯圖片時，彈出對話框
            $('.left-image img').click(function() {
                // 使用 jQuery UI 對話框插件
                $('<div>更多專輯信息和詳細內容在此處。</div>').dialog({
                    title: '專輯詳情',
                    modal: true,
                    width: 400
                });
            });
        });
    </script>
</head>
<body>
    <header>
        <h1>專輯介紹</h1>
    </header>

    <div class="container">
        <div class="left-image">
            <img src="https://upload.wikimedia.org/wikipedia/en/c/cd/Ed_Sheeran_-_Equals.png" alt="左側圖片">
        </div>
        <div class="right-content">
            <h2>專輯名稱和內容</h2>
            <p>=，專輯封面以親筆畫作搭配蝴蝶拼貼，象徵傳遞「新生」。</p>

            <h2>關於作者</h2>
            <p>於1991年出生於英國，在全球共取得了2600萬專輯和1億單曲銷量，是當紅的音樂藝人。</p>

            <h2>社群媒體</h2>
            <p>以下是作者的社群平台</p>
            <ul>
                <li>Instagram: teddysphotos</li>
                <li>Youtube: Ed Sheeran</li>
                <li>Twitter: Ed Sheeran HQ</li>
            </ul>
        </div>
    </div>
</body>
</html>
