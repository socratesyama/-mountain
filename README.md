# 等高線クラフト

ぐるぐる描いた線から、等高線のような地形と山をつくって遊ぶブラウザアプリです。

## 遊び方

1. `index.html` をブラウザで開きます。
2. 左側のキャンバスに線を描きます。
3. 描いた線の高さをカラーパレットで選びます。
4. 右側に生成された山の形や名前が表示されます。
5. 完成した山は画像としてシェアできます。

## 主な機能

- マウス・タッチ操作で地形を描画
- 高さごとのカラーパレット
- おまかせ生成、消しゴム、取り消し、全消去
- 水位の調整
- ダークモード対応
- 山の名前・標高・地形情報の自動表示
- シェア画像の作成とX投稿用リンク
- `prefers-reduced-motion` に対応したアニメーション制御

## 起動方法

ビルドツールやサーバーは不要です。リポジトリのルートにある `index.html` をブラウザで開いてください。

```bash
open index.html       # macOS
xdg-open index.html   # Linux
```

または、ローカルサーバーから起動できます。

```bash
python3 -m http.server 8000
```

その後、<http://localhost:8000/> を開きます。

## 使用ライブラリ・外部リソース

- [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)
- [Google Fonts](https://fonts.google.com/): Dela Gothic One / Zen Maru Gothic

## ファイル構成

```text
.
├── index.html  # アプリ本体（HTML / CSS / JavaScript）
└── README.md   # この説明書
```

## ライセンス

このリポジトリのライセンスは、別途指定があるまで未定義です。
