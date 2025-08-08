# bodik-visualizations

BODIKに登録されている自治体オープンデータを、簡単に可視化できるHTML集です。  
本リポジトリには、以下2種類のHTMLが含まれます。

1. **可視化HTML**  
   そのままGoogle SitesやWordPressに `<iframe>` で埋め込める1ファイルHTML
2. **埋め込みHTMLジェネレータ**  
   指定した自治体オープンデータを元に、**埋め込み用の生HTMLコード**を生成するHTMLツール  
   → 生成されたコードを直接貼り付けて利用します

---

## 公開URL（GitHub Pages）

### 1. 可視化HTML（カスタム対応）
- **福岡市防災情報マップ**  
  表示URL: https://shigerutakano.github.io/bodik-visualizations/fukusyo_mail/  
  データソース: https://data.bodik.jp/dataset/401307_fukusyomail

---

### 2. 埋め込みHTMLジェネレータ（自治体標準オープンデータセット対応）
- **人口ピラミッド**  
  https://shigerutakano.github.io/bodik-visualizations/population_pyramid/
- **施設マップ**  
  https://shigerutakano.github.io/bodik-visualizations/facility_map/

---

### 3. 埋め込みHTMLジェネレータ（その他）
- **アメダス情報**  
  https://shigerutakano.github.io/bodik-visualizations/amedas_weather/
- **時計**  
  https://shigerutakano.github.io/bodik-visualizations/clock/

---

## 埋め込み方法

### 可視化HTMLの場合（例: 福岡市防災情報マップ）
`<iframe>` タグを使って外部サイトに読み込みます。
```html
<iframe src="https://shigerutakano.github.io/bodik-visualizations/fukusyo_mail/"
        width="800" height="600" style="border:none;"></iframe>
```
### 埋め込みHTMLジェネレータの場合（例: 施設マップ）
1. ジェネレータページを開き、条件を設定して「埋め込みコードを生成」ボタンを押します。
2. 表示された生HTMLコードをコピーし、そのままGoogle SitesやWordPress等に貼り付けます。
