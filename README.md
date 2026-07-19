# 触れる作品空間 — ネイル試着連結版

元の「触れる作品空間」を複製し、独自のカメラ式ネイル試着体験を連結した版です。元サイトは変更していません。

## 開き方（Mac）

1. `このサイトを開く.command` をダブルクリックします。
2. ブラウザが開いたら、最初の円形ボタン「触れる」を押します。
3. 最後の `NAIL MATERIAL TEST` から試着画面へ進み、カメラを許可します。
4. 終了するときは、開いたターミナルで `control + C` を押します。

`index.html` を直接ダブルクリックしても映像・粒子・スクロール演出は見られます。GLBの3D表示だけは、インターネット接続中に上の `.command` から開いてください（3D本体はローカル、表示ライブラリだけを外部から読み込みます）。

## ファイル構成

- `index.html` — CSSとJavaScriptを含むサイト本体
- `このサイトを開く.command` — 3D表示を含めて開くMac用ファイル
- `assets/` — 作品画像・動画・GLB
- `nail/index.html` — カメラ式ネイル素材試着

## 作品を差し替える

`assets/` 内の同名ファイルへ上書きすると、HTMLを編集せず差し替えられます。

- `contemplative-hand.mp4` — オープニングの手
- `mandala-hand.mp4` — 中盤の手と球
- `orbiting-hand.mp4` — 後半の接続映像
- `contemplative-hand.glb` — 3D表示する手
- `hand-orb-01.png` / `hand-orb-02.png` / `hand-trace.png` — 最後の断片アーカイブ

動画は MP4（H.264）、画像は PNG・JPEG・WebP、GLBは1ファイルにテクスチャを埋め込んだ形式が適しています。

## 今回参照した研究ノート

- `10_Wiki/research/concepts/触感的視覚性.md`
- `10_Wiki/research/concepts/身体性と装飾.md`
- `10_Wiki/research/concepts/立体曼荼羅.md`
- `10_Wiki/research/projects/修士制作_立体絵画.md`

元素材は変更せず、Web用の複製だけを `assets/` に置いています。
