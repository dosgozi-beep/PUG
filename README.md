# POPPING UP GUNMA (PUG) — 企業連携提案サイト

群馬大学の起業サークル **POPPING UP GUNMA (PUG)** の、企業向け連携提案ページです。

**🌐 公開サイト**: `https://あなたのユーザー名.github.io/リポジトリ名/`

---

## 📂 ファイル構成

```
.
├── index.html              # メインHTML（全体で1ファイル）
├── bg-texture.png          # 背景テクスチャ
├── flow-01-listen.png      # STEP 01「聞く」のイラスト
├── flow-02-think.png       # STEP 02「思考する」のイラスト
├── flow-03-shape.png       # STEP 03「形にする」のイラスト
├── pug-photo-01.jpeg       # ヒーロー画像（勉強会の様子）
├── pug-photo-02.jpeg       # Aboutセクション（講堂）
├── pug-photo-03.jpeg       # ギャラリー1（交流会）
├── pug-photo-04.jpeg       # ギャラリー2（ディスカッション）
└── pug-photo-05.jpeg       # ギャラリー3（大講堂）
```

すべてのファイルを**同じ階層**に置いてください。

---

## 🚀 GitHub Pagesで公開する手順

### ステップ1: リポジトリを作成

1. GitHubにログイン
2. 右上の「+」→「New repository」
3. リポジトリ名を入力（例: `pug-website`）
4. **Public** を選択（GitHub Pagesは無料プランだとPublic限定）
5. 「Create repository」をクリック

### ステップ2: ファイルをアップロード

1. 作成したリポジトリページで「uploading an existing file」をクリック
2. このフォルダ内のすべてのファイル（10個）をドラッグ&ドロップ
3. 下にスクロールして「Commit changes」をクリック

### ステップ3: GitHub Pagesを有効化

1. リポジトリの「**Settings**」タブ
2. 左メニューの「**Pages**」
3. Source の設定で:
   - **Branch**: `main` を選択
   - **Folder**: `/ (root)` を選択
4. 「Save」をクリック

### ステップ4: 公開URLを確認

数分待つと、ページ上部に公開URLが表示されます:

```
https://あなたのユーザー名.github.io/リポジトリ名/
```

このURLを企業担当者に共有できます 🎉

---

## 💻 ローカルでプレビューする

ファイルを解凍して `index.html` をダブルクリックするだけです。ブラウザで開きます。

---

## 🔧 内容を修正する

`index.html` をテキストエディタ（VS Code、メモ帳など）で開いて編集します。主な編集ポイント：

- **メンバー数**: `20<em>名</em>` を検索して変更
- **活動頻度**: `月<em>2</em>回` を検索して変更
- **実績**: `<div class="record-item reveal">` のブロックを追加/編集
- **Instagram URL**: `https://www.instagram.com/poppingup960/` を検索
- **問い合わせ先**: Contact セクションの `btn-primary` リンクを変更

---

## 🎨 主な技術

- HTML + CSS + 素のJavaScript（フレームワーク不要）
- 外部依存: Google Fonts のみ（Shippori Mincho, Zen Kaku Gothic New, Instrument Serif, JetBrains Mono）
- レスポンシブ対応（PC・タブレット・スマホ）
- アニメーション（スクロールリビール、ホバーエフェクト）

---

## 📝 ライセンス

© POPPING UP GUNMA · Gunma University Entrepreneurship Circle
