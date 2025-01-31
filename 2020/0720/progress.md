# 進捗管理 2020.07.20

## 書籍からの分析
### WEB DESIGN FORUM
- ページレイアウトの基本的な考え方
- ページの構成要素の種類
- １ページあたりの情報量
- 採択する段組み（カラム）レイアウトの選択基準について
- 段組みの使い分けについて
  - 情報量によってカラム数を使い分ける
  - 視認性や可読性を重視したい場合は１ページあたりの情報量を絞り、2-3段組みでデザインするのが良い
  - 逆にニュースサイトのように可読性が低下しても一覧性を向上した方が効率的なサイトは4-5段組みが効果的
- フィックスドとリキッドレイアウトのどちらが良いか
  - フィックスドは再現性が高い（レイアウトを正確に表現できる）
  - リキッドは閲覧環境に依存しない
- 文字の読みやすさ
  - 文字サイズ、行間、行の長さ、マージンによって決まる
  - 行間が詰まっていると可読性が低下する
- Webページの基本的なレイアウト手法について
  - 固定レイアウト
    - フィックスドレイアウト
  - 可変レイアウト
    - リキッドレイアウト（単位 [%]）
    - エラスティックレイアウト（単位 [em]）
    - ハイブリッドレイアウト（単位 [%, em]）
- 逆L字レイアウトについて
  - ページ上部と左部に優先度の高い情報や機能を置くレイアウト

  | レイアウト | サンプル |
  | --- | --- |
  |![逆L字レイアウト](https://cdn-ak.f.st-hatena.com/images/fotolife/h/haruka-i1997/20180207/20180207092048.png)|![サンプル](https://cdn-ak.f.st-hatena.com/images/fotolife/h/haruka-i1997/20180206/20180206140020.png)|

- F字パターンを考慮したレイアウトについて
  - ヤコブ・ニールセン博士の調査報告によって人の視線はF字のように動こことを発表
  - 目立たせたい情報は左上が効果的
- ナビゲーションに役割と機能について
- 色の視認性について
  - 色固有の性質ではなく、地色との配色による相対的なもの



### Webデザイン、これからどうなるの？
#### 目次
- UI
- レイアウト
- グラフィック
- タイポグラフィ
- 配色

#### レイアウトについて
- シングルカラムレイアウト
  - モバイルファースト時代の標準形
  - モバイル中心にあらゆるWeb閲覧環境でも閲覧しやすい標準形
  - 環境によるデザインの差を抑えることが可能
- レスポンシブデザインの現在
  - あらゆる解像度においてシームレスに変動
- パララックスエフェクトの現在
  - スクロールに連動した演出の総称で動作も使用帯域も軽量を重視する
  - スクロールを視点の移動に見立てて立体感を持たせる演出
- スプリットレイアウトの現在
  - ２カラムレイアウトと同意
  - モバイルとPCで表示比率を維持しやすい
- フルスクリーンレイアウト
  - 画面全体を用いた演出やUI用のレイアウト
  - インパクトのある表現や自由なレイアウトが可能
- カードレイアウト
  - カード型のコンポーネントを並べることでレイアウトの自由度を高める
  - 情報密度が高くなる一方で**情報の強弱が生まれにくい**
  - デザインで文脈を作る工夫が必要になることもある
- ブロークングリッド
  - グリッドによるレイアウトをあえて壊す
  - デザインに変化や動きを与える
  - **ビジュアルの印象を高める**効果がある
- AMPとモバイルファースト
- 画面遷移とトランジション


### レイアウトについてよくまとめられているサイト
- [Webの基本レイアウトまとめとサンプルコード](http://information-bibouroku.hatenablog.com/entry/2018/02/07/102402)

### レイアウトパターン
- シングルカラム([Balumuda](https://www.balmuda.com/jp/toaster/))
- カラムレイアウト
  - ２カラム
  - ３カラム
  - ４カラム
- カードレイアウト ([Pinterest](https://www.pinterest.jp/))
- ブロークングリッドレイアウト ([BAKE](https://cheesetart.com/))
- フルスクリーンレイアウト

![参考パターン](https://www.mdn.co.jp/di/contents/2094/12612/attach/images/201003/book6102/p222-223-01.jpg)

## 今後の課題とタスク
- 今回決めたレイアウトに分類を行う
- それぞれにパターンごとに視線データ（顕著性マップ）はどのように異なるのかを分析する
- パターンの傾向ごとに重み付けを行いオリジナルシステムに導入する
- 評価実験を行う