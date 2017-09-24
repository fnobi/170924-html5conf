# <span>面白法人の</span><span>テクニカルディレクターのしごと</span><footer>面白法人カヤック 藤澤伸 @fnobi</footer>

## 自己紹介

- **fnobi (藤澤伸)**
- 面白法人カヤック HTMLファイ部 リーダー
- 最近の趣味：Vue.js, firebase, docker
- 普段は主に受託事業部で無茶なWebサイトをつくっています
- 今日はカヤックブースでガチャ回したりしてました

### 　
### 　

## 今日のお題

- **2ヶ月で**
- **アプリ並みに動く**
- **HTML5ゲームコンテンツを**
- **2本つくる**

ためにテクニカルディレクター（私）がやったこと。

※調子に乗って「テクニカルディレクター」というテーマで応募してしまったのであんまり技術の話しません

### 　

## うまぷよ

[https://umabi.jp/umapuyo/](https://www.kayac.com/service/client/1555)

- JRAさんとSEGAさんのコラボコンテンツ
- ゲーム２本立て
  - スマホWebサイト上でぷよぷよが遊べる（消すほど上段で馬が速く走る）
  - ぷよをジャンプさせて馬を救出していく

- 実装期間: **ちょうど2ヶ月くらい**
  - first commit 6/14 〜 公開日 8/17
- フロントエンジニア３人 & テクニカルディレクター（藤澤）

## ポイント

テクニカル面で自分が達成しなくてはいけなかったこと。

- **1. アプリ並にぬるぬる動かしたい**
- **2. 何度も体験したくなるゲームにしたい**
- **3. 急ぎたい**

## <span>1. アプリ並に</span><span>ぬるぬる動かしたい</span>

- **WebGL & Vue.js**
  - インゲーム（プレイ中画面）は**WebGL**
    - ジャンプではpixi.js
    - レースではregl（生のWebGLを抽象化して扱える）
  
  - アウトゲーム（画面遷移）は**Vue.js**

## <span>2. 何度も体験したくなる</span><span>ゲームにしたい</span>

- ゲームはとにかく動いてみないと分からない！！ウォーターフォールな進め方ではむずかしい
- **体験のモックをともかく早くつくる**
  - デザインを待つということを一切しない
  - 7月半ばにはAPI連携・基本ルール等のベース機能は完成 そこから体験と演出をひたすら詰める

## 3. 急ぎたい

- 結局自分が一番頑張ったのはここ

- **属人化と非属人化のバランス**
  - 各ゲームについては主担当をつけ、ゲーム内部ロジックについてはあるていど、当人の一番スピードが出るやり方に任せる
  - ゲーム内部と外部のインタフェース・アウトゲームの画面遷移については、しっかりコードレビューするなど属人化しないように

- **仕様については一度TDが咀嚼・issue化**
- **直近一週間の作業についてgithubでマイルストン管理**
  - ※前述の７月半ばまでのフェーズ
  - 各々の仕様把握にかかる時間を短縮
  - issueだけ見ていれば、次に何をすればよいかわかる体制に

## まとめ

- ウォーターフォールの中で高いクオリティの体験を作るには、いかに初速を出すかが大事
  - とにかく実装者が前に向かってコードを書き続けられるように
  - 誰がどこに何を書くか、どのライブラリを使うか迅速にジャッジ
  - 今何をやればいいか、企画面・実装面の両方から優先度を付ける
  - **→エンジニアがディレクションをする強みがこのあたりにある**

- そして当然ながら普段からの鍛錬
  - 見事やりきってくれた実装メンバーには感謝しかない

## ありがとうございました！
