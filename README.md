# Sugoi Sushi Website

シドニーを拠点とするプライベート寿司シェフ Jin(仁)によるビジネス「Sugoi Sushi」の一枚ページサイトです。

## ファイル構成

- `index.html` — サイト本体(HTML/CSS/JSを1ファイルにまとめています)
- `images/` — 掲載画像(現在はプレースホルダー画像。実際の写真に差し替えてください)

## ローカルで確認する方法

`index.html` をブラウザで直接開くか、このフォルダで簡易サーバーを立てて確認できます。

```bash
python3 -m http.server 8000
```

その後ブラウザで `http://localhost:8000` を開いてください。

## 差し替えが必要な箇所

- `images/` 内の画像を実際の料理写真・シェフ写真に差し替え
- `index.html` 内の Instagram / 電話番号 / メールアドレス(`#contact` セクション)
- About セクション、お客様の声の仮テキスト
