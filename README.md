# saypenguin.github.io
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ペンギンの世界 ― このサイトはお茶の水女子大学共創工学部「デザイン思考とロジックモデル」講義の一環で作成されています（チームF）</title>
    <style>
        /* デザインの基本設定 */
        body {
            font-family: "Helvetica Neue", Arial, "Hiragino Kaku Gothic ProN", "Hiragino Sans", Meiryo, sans-serif;
            line-height: 1.8;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff; /* 薄い水色 */
        }

        header {
            background-color: #003366; /* 濃い紺色 */
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin-top: 10px;
            font-size: 1.1em;
            opacity: 0.9;
        }

        nav {
            background-color: #002244;
            position: sticky;
            top: 0;
            z-index: 1000;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: inline-block;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #0055aa;
        }

        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            background-color: white;
            padding: 40px;
            margin-bottom: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        h2 {
            color: #0055aa;
            border-left: 6px solid #0055aa;
            padding-left: 15px;
            margin-bottom: 25px;
            font-size: 1.8em;
        }

        h3 {
            color: #003366;
            margin-top: 30px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #e6f2ff;
            padding: 20px;
            border-radius: 8px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table th, table td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }

        table th {
            background-color: #0055aa;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        .alert {
            background-color: #fff0f0;
            border: 1px solid #ffcccc;
            padding: 20px;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
        }

        /* レスポンシブ対応 */
        @media (max-width: 600px) {
            header h1 { font-size: 1.8em; }
            section { padding: 20px; }
            nav a { padding: 10px; font-size: 0.9em; }
        }
    </style>
</head>
<body>

<header>
    <h1>ペンギンの世界</h1>
    <p>海を駆ける飛べない鳥の真実</p>
</header>

<nav>
    <a href="#basic">基本情報</a>
    <a href="#ability">身体能力</a>
    <a href="#lifecycle">ライフサイクル</a>
    <a href="#species">種類</a>
    <a href="#crisis">環境問題</a>
</nav>

<div class="container">

    <section id="intro">
        <p>「ペンギン」と聞くと、多くの人が「氷の上をよちよち歩く可愛い姿」を思い浮かべるでしょう。しかし、彼らの本当の姿は、<strong>過酷な自然環境に適応し、驚異的な身体能力を持つ「海のハンター」</strong>です。</p>
        <p>このサイトでは、知っているようで知らないペンギンの生態を、科学的な視点と親しみやすい解説で紐解いていきます。(
        このサイトはお茶の水女子大学共創工学部「デザイン思考とロジックモデル」講義の一環で作成されています（チームF）)
        </p>
    </section>

    <section id="basic">
        <h2>1. ペンギンってどんな動物？</h2>
        <p>ペンギンは、主に南半球に生息する「海鳥（うみどり）」の仲間です。鳥でありながら空を飛ぶことはできませんが、その代わりに海の中を飛ぶように泳ぐ能力を身につけました。</p>
        <div class="grid">
            <div class="card">
                <strong>種類</strong><br>
                世界に18種類（分類により前後します）
            </div>
            <div class="card">
                <strong>生息地</strong><br>
                南極から熱帯のガラパゴス諸島まで
            </div>
            <div class="card">
                <strong>サイズ</strong><br>
                最大：コウテイペンギン (120cm)<br>
                最小：コガタペンギン (40cm)
            </div>
        </div>
    </section>

    <section id="ability">
        <h2>2. 驚きの身体能力</h2>
        <h3>フリッパー（翼）</h3>
        <p>空を飛ぶための翼は、水中で力強く水をかくための「フリッパー」へと進化しました。時速30km以上のスピードで泳ぐ種もいます。</p>
        
        <h3>カウンターシェーディング</h3>
        <p>背中が黒く、お腹が白いのは敵から身を守るためのカモフラージュです。空から見ると深い海の底の色に溶け込み、海中から見ると水面の光に紛れます。</p>
        
        <h3>究極の防寒機能</h3>
        <p>分厚い皮下脂肪と、高密度で油分を含んだ羽毛により、氷点下の環境でも体温を維持できます。水は決して皮膚まで届きません。</p>
    </section>

    <section id="lifecycle">
        <h2>3. ペンギンのライフサイクル</h2>
        <p>多くのペンギンは、「コロニー」と呼ばれる巨大な集団を作って生活します。</p>
        <ol>
            <li><strong>求愛とペアリング：</strong> 鳴き声でお互いを識別し、特定のパートナーとペアを組みます。</li>
            <li><strong>卵を守る：</strong> オスとメスが交代で、あるいはオスが専念して卵を温めます。</li>
            <li><strong>クレイシ（保育所）：</strong> 親がエサを獲りに行く間、ヒナ同士が集まって身を守ります。</li>
            <li><strong>換羽（かんう）：</strong> 年に一度、羽が全て生え変わります。この間は水に入れず絶食します。</li>
        </ol>
    </section>

    <section id="species">
        <h2>4. 主なペンギンの種類</h2>
        <table>
            <thead>
                <tr>
                    <th>種類名</th>
                    <th>特徴</th>
                    <th>主な生息地</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>コウテイペンギン</td>
                    <td>最大種。最も過酷な冬に繁殖。</td>
                    <td>南極大陸</td>
                </tr>
                <tr>
                    <td>アデリーペンギン</td>
                    <td>タキシード模様の典型的な姿。</td>
                    <td>南極沿岸</td>
                </tr>
                <tr>
                    <td>フンボルトペンギン</td>
                    <td>日本の水族館で最も一般的。</td>
                    <td>チリ・ペルー</td>
                </tr>
                <tr>
                    <td>イワトビペンギン</td>
                    <td>黄色の飾り羽をもち、岩場を跳ねる。</td>
                    <td>亜南極の島々</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="crisis">
        <h2>5. ペンギンが直面している危機</h2>
        <div class="alert">
            <p>今、多くのペンギンが絶滅の危機に瀕しています。</p>
            <ul>
                <li><strong>気候変動：</strong> 海氷の減少による繁殖地の消失。</li>
                <li><strong>海洋汚染：</strong> プラスチックごみの誤飲や重油流出。</li>
                <li><strong>過剰な漁業：</strong> エサとなる魚やオキアミの減少。</li>
            </ul>
        </div>
    </section>

    <section id="trivia">
        <h2>ペンギン雑学</h2>
        <ul>
            <li><strong>トボガン：</strong> お腹で氷の上をソリのように滑る移動法。</li>
            <li><strong>膝はあるの？：</strong> 実は足の中に隠れています。常に中腰の状態です。</li>
            <li><strong>飲み水：</strong> 海水を飲み、「塩類腺」で塩分をろ過して排出します。</li>
        </ul>
    </section>

</div>

<footer>
    <p>&copy; 2023 ペンギンの世界 ― 知的好奇心を満たす動物図鑑</p>
</footer>

</body>
</html>
