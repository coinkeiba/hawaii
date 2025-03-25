<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>三世代ハワイ旅行プラン</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, 'Hiragino Kaku Gothic ProN', 'Meiryo', sans-serif;
    }
    
    body {
      background: linear-gradient(to bottom right, #fff9c4, #ffcdd2);
      min-height: 100vh;
      padding: 12px;
      line-height: 1.4;
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      background-color: white;
      border-radius: 16px;
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
      padding: 16px;
      border: 4px solid #f8bbd0;
    }
    
    .title {
      font-size: 1.5rem;
      font-weight: bold;
      text-align: center;
      color: #d81b60;
      margin-bottom: 1rem;
      background-color: #fff9c4;
      padding: 0.75rem;
      border-radius: 0.75rem;
      word-break: break-all;
    }
    
    .tab-buttons {
      display: flex;
      justify-content: center;
      margin-bottom: 1rem;
    }
    
    .tab-button {
      padding: 8px 16px;
      margin: 0 4px;
      border-radius: 8px;
      border: none;
      cursor: pointer;
      font-weight: bold;
      font-size: 0.9rem;
      transition: all 0.3s ease;
      white-space: nowrap;
    }
    
    .tab-button.active {
      background-color: #ec407a;
      color: white;
    }
    
    .tab-button:not(.active) {
      background-color: #fce4ec;
      color: #c2185b;
    }
    
    .tab-content {
      display: none;
    }
    
    .tab-content.active {
      display: block;
    }
    
    .flight-info {
      background-color: #fce4ec;
      padding: 12px;
      border-radius: 8px;
      margin-bottom: 12px;
    }
    
    .family-group {
      margin-bottom: 16px;
    }
    
    .family-title {
      display: flex;
      align-items: center;
      margin-bottom: 8px;
      font-weight: bold;
      color: #c2185b;
    }
    
    .family-title span {
      margin-right: 8px;
    }
    
    .flight-list {
      list-style-type: disc;
      padding-left: 20px;
      color: #4a148c;
      font-size: 0.9rem;
    }
    
    .flight-list li {
      margin-bottom: 8px;
      word-break: break-word;
    }
    
    .schedule-day {
      background-color: white;
      border: 4px solid #f8bbd0;
      border-radius: 12px;
      padding: 12px;
      margin-bottom: 12px;
    }
    
    .day-title {
      display: flex;
      align-items: flex-start;
      margin-bottom: 8px;
      font-weight: bold;
      font-size: 1.1rem;
      color: #880e4f;
    }
    
    .day-title span {
      font-size: 1.5rem;
      margin-right: 8px;
      min-width: 24px;
    }
    
    .day-title h3 {
      flex: 1;
      font-size: 1.1rem;
    }
    
    .day-list {
      list-style-type: disc;
      padding-left: 20px;
      color: #4a148c;
      font-size: 0.9rem;
    }
    
    .day-list li {
      margin-bottom: 6px;
      word-break: break-word;
    }
    
    .sub-list {
      padding-left: 20px;
      list-style-type: disc;
      margin-top: 4px;
      margin-bottom: 8px;
    }
    
    /* スマートフォン用のメディアクエリ */
    @media (max-width: 480px) {
      body {
        padding: 8px;
      }
      
      .container {
        padding: 12px;
        border-width: 3px;
      }
      
      .title {
        font-size: 1.2rem;
        padding: 10px;
      }
      
      .tab-button {
        padding: 6px 12px;
        font-size: 0.8rem;
      }
      
      .day-title {
        font-size: 1rem;
      }
      
      .day-title span {
        font-size: 1.2rem;
      }
      
      .day-list, .flight-list {
        font-size: 0.85rem;
      }
      
      .sub-list {
        padding-left: 16px;
      }
      
      .flight-list li, .day-list li {
        margin-bottom: 8px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="title">📘 三世代ハワイ旅行（2025年3月31日〜4月3日） ✈️</h1>
    
    <div class="tab-buttons">
      <button class="tab-button active" id="schedule-btn" onclick="showTab('schedule')">📅 日別スケジュール</button>
      <button class="tab-button" id="flight-btn" onclick="showTab('flight')">✈️ フライト情報</button>
    </div>
    
    <!-- 日別スケジュール -->
    <div id="schedule" class="tab-content active">
      <div class="schedule-day">
        <div class="day-title">
          <span>🏖</span>
          <h3>3月31日(月) - コオリナへ移動 & 三世代合流</h3>
        </div>
        <ul class="day-list">
          <li>午前：シェラトンをチェックアウト</li>
          <li>昼前：マリオット・コオリナにチェックイン</li>
          <li>午後：ビーチ & プールでのんびり</li>
          <li>夕方：カ・マカナ・アリイでBBQ食材の買い出し</li>
          <li>夜：マリオットのBBQエリアでBBQディナー 🍖 家族団らん！</li>
        </ul>
      </div>
      
      <div class="schedule-day">
        <div class="day-title">
          <span>🚐</span>
          <h3>4月1日(火) - アウラニでモーニング & ノースショアへドライブ</h3>
        </div>
        <ul class="day-list">
          <li>10:00：アウラニのレストランでキャラクターブレックファスト（予約済み）</li>
          <li>12:00：大きな車でノースショアへ出発 🚐</li>
          <li>午後：
            <ul class="sub-list">
              <li>ハレイワタウンを散策（ショップ・カフェ）</li>
              <li>ガーリックシュリンプランチ（ジョバンニ or フミズ）🍤</li>
              <li>マツモトシェイブアイスでスイーツタイム 🍧</li>
              <li>Mele Mele Bakery にも立ち寄り 🍞</li>
              <li>ワイメア or ラニアケアビーチでのんびり 🌊</li>
            </ul>
          </li>
          <li>18:30：コオリナに帰着</li>
          <li>夜：スーパーで買い出し → ホテルの部屋でディナー</li>
        </ul>
      </div>
      
      <div class="schedule-day">
        <div class="day-title">
          <span>🛍</span>
          <h3>4月2日(水) - お買い物Day</h3>
        </div>
        <ul class="day-list">
          <li>朝：ホテルでゆっくり朝食</li>
          <li>午前：ワイケレ・プレミアム・アウトレットでショッピング 🛍</li>
          <li>昼：Tanioka's Seafoods or カイナハワイアンBBQ</li>
          <li>午後：コオリナラグーンでのんびり or アウラニを散歩</li>
          <li>夜：Mina's Fish House（フォーシーズンズ）で家族全員そろっての豪華ディナー ✨</li>
        </ul>
      </div>
      
      <div class="schedule-day">
        <div class="day-title">
          <span>✈️</span>
          <h3>4月3日(木) - 野口家は帰国 / 他の家族は延泊</h3>
        </div>
        <ul class="day-list">
          <li>朝：朝食をとってチェックアウト</li>
          <li>【野口家】：ホノルル空港へ移動 → 12:15発 JL73で帰国</li>
          <li>【祖父母・井元家】：ワイキキへ移動し、さらにもう1泊 🏨</li>
        </ul>
      </div>
    </div>
    
    <!-- フライト情報 -->
    <div id="flight" class="tab-content">
      <div class="flight-info">
        <div class="family-group">
          <div class="family-title">
            <span>👴👵</span>
            <h3>祖父母（大阪 ⇄ ホノルル）</h3>
          </div>
          <ul class="flight-list">
            <li>3月31日(月) 22:10 大阪（関空）→ 4月1日(火) 10:45 ホノルル（JL792）</li>
            <li>4月4日(金) 11:35 ホノルル → 4月5日(土) 15:40 大阪（JL791）</li>
          </ul>
        </div>
        
        <div class="family-group">
          <div class="family-title">
            <span>👨‍👩‍👧‍👦</span>
            <h3>野口家（東京 ⇄ ホノルル）</h3>
          </div>
          <ul class="flight-list">
            <li>3月27日(木) 21:00 東京（羽田）→ 3月27日(木) 09:00 ホノルル（JL74）</li>
            <li>4月4日(金) 12:15 ホノルル → 4月5日(土) 15:55 東京（羽田）</li>
          </ul>
        </div>
        
        <div class="family-group">
          <div class="family-title">
            <span>👨‍👩‍👧‍👦</span>
            <h3>井元家（沖縄 ⇄ ホノルル）</h3>
          </div>
          <ul class="flight-list">
            <li>3月29日(土) 16:15 沖縄 → 18:15 名古屋（NU44）</li>
            <li>3月29日(土) 20:30 名古屋 → 3月30日(日) 08:30 ホノルル（JL794）</li>
            <li>4月4日(金) 11:40 ホノルル → 4月5日(土) 15:40 大阪（JL791）</li>
            <li>4月5日(土) 20:05 大阪 → 22:20 沖縄（NU9）</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  
  <script>
    function showTab(tabId) {
      // すべてのタブコンテンツを非表示にする
      document.querySelectorAll('.tab-content').forEach(function(content) {
        content.classList.remove('active');
      });
      
      // すべてのタブボタンから active クラスを削除
      document.querySelectorAll('.tab-button').forEach(function(button) {
        button.classList.remove('active');
      });
      
      // 選択されたタブを表示
      document.getElementById(tabId).classList.add('active');
      
      // クリックされたボタンに active クラスを追加
      document.getElementById(tabId + '-btn').classList.add('active');
    }
  </script>
</body>
</html>
