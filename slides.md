---
# try also 'default' to start simple
theme: light-icons
colorSchema: light

fonts:
  # like font-family in css, you can use `,` to separate multiple fonts for fallback
  sans: 'Helvetica Neue, Noto Sans JP'
  serif: 'Helvetica Neue, Noto Sans JP'

# first page
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

<style>
  body #slide-content {
    font-size: 20px;
    color: #3a453a;
  }
  h1 {
    font-size: 2.6rem !important;
    line-height: 1.4 !important;
    font-weight: bold !important;
  }
  h2 {
    font-size: 1.5rem !important;
    font-weight: bold !important;
    border-bottom: 1px solid #cceedd;
  }
  body ul {
    padding-left: 24px;
  }
  .slidev-layout p + h2, .slidev-layout ul + h2, .slidev-layout table + h2 {
    margin-top: 1rem !important;
  }
  ul ul {
    font-size: .9rem;
  }
  li {
    margin-top: .8rem;
    list-style-type: initial;
  }
  li + li {
    margin-top: .5rem;
  }
</style>

<h1 class="flex flex-col">
<span>一部上場企業から</span>
<span>ベンチャー転職の</span>
<span>Before/After</span>
</h1>

<section>
<p class="flex flex-col mt-16">
<span class="text-gray-500">event: ITエンジニアの転職経験談 LT会</span>
<span class="text-gray-500">author: meijin(@Meijin_garden)</span>
</p>
</section>

---
layout: image-right-customed
image: https://user-images.githubusercontent.com/7464929/142981142-a7bd942d-b210-4ef1-8c2a-52765279d941.png
---

# 自己紹介

- ニックネーム「名人」
  - https://meijin.dev
  - https://zenn.com/meijin
- Twitter: <span class="ml-2 text-[#1d9bf0] font-bold">@Meijin_garden</span>
- 株式会社 NoSchool CTO
  - オンライン家庭教師マナリンク -> https://manalink.jp
- 2016年LIFULL新卒入社→2019年から現職
- 趣味は将棋（初段くらい）

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 転職前(2016〜2019年)

- 一部上場企業のWebエンジニア
  - 役職は**メンバー**
  - 企画やデザイン、技術選定や負債解消には**ほぼ関わらない**
  - 主に**jQuery、Symfony、Sinatra**で機能追加やバグ改修
  - 1Qに5営業日程度、自由に開発できる社内制度があるので、使いまくってAWS等を触る練習をしていた
- エンジニア以外の活動もかなり多かった
  - 社内**新規事業提案**→入賞して1年ほど業務時間のN割で活動
  - 社内イベントや社内制度の**運営委員会(有志)に複数所属**
    - 活動量は社内随一で全社総会で表彰していただいたり。

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 転職後(2019年〜)

- スタートアップでCTO
  - 役職はそのとき**会社に足りないものに応じて変わる**
  - 企画やデザイン、技術選定や負債の認識、採用まで**全部やる**
  - 主に**Vue、React、Laravel、React Native**で次々に新規実装
  - **プライベートの時間や勉強会の主催**などによって新しい技術を習得
  - いろいろあって現在は**1人**でWebサイト、アプリ、メディアを開発
- 主に経験したこと
  - 入社当時の事業がまったくうまく行かず**クローズ→ピボット**
  - 資金が尽きかける中、**オンライン家庭教師サービス**を始め生き延びる
  - 事業が成長し、今は**エンジニアを採用する余裕**ができた(採用中！)

---
layout: image-header-intro
---

# 観点別にBefore/Afterをまとめました

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# スキルマップ

## 前職

- 非常に綿密なスキルマップがあり、**一定のスキルを満たすと証明したら昇級**できる
- なので僕はほとんどスキルマップに関連した勉強のみだけ、それ以外は新規事業提案に割いていた

## 現職

- スキルマップなんて無い
- **いつ何が必要に/不必要になるかわからない**
  - たとえばピボット前はiOSアプリだけやっていたが、ピボット後にクロスプラットフォームになったのでReact Nativeを書き始めた

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 技術力

## 前職

- ほとんどの工数が**既存実装調査と他部署調整とテストとMTG**
- 部署によるが、半期に一度、スキルアップのチャンスが貰えれば良い方

## 現職

- 他部署調整とかMTGはほぼ無く、リリースフローも短いので次々実装、次々リリース
- 特にソフトウェア設計スキルが伸び、**設計分野のWeb教材を執筆(LaravelでFatControllerをリファクタリングしよう)**
- **決済**の実装、インフラ、セキュリティ等の知見も溜まった

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 技術の勉強

## 前職

- 前述の通り、スキルマップに関することに特化してたし、プライベートの時間は新規事業提案に割いてた

## 現職

- **情報収集**
  - 公式ドキュメント、公式Twitter(通知ON)、リポジトリのIssue
  - Twitter、Zenn、GitHubトレンド、各種ブログ
- **手元で試す**
  - 試してGitHubにPush、template repositoryとして公開
- そして**業務で運用して痛い目に遭う。これが一番勉強になる**

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# キャリア形成

## 前職

- 社内に**エンジニアのロールモデル**がいる(総勢100人以上)
- 大量の物件データを扱う**大規模なサービスの負債解消**は貴重な実績や経験になる

## 現職

- **会社の成長そのものがキャリア**
- 大規模なトラフィックを捌いたり、脳死で札束で捌くような経験をすることはできない
- 少人数で仕事をしていると価値観が固まるので、複業等で他社(のSlack)に入らせてもらうといった工夫が必要と思う

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 会社に対するスタンス

## 前職(かなり正直に言うと...)

- ○○という制度を作って欲しい（尚その制度の実現方法や負の側面については考えてない。制度化されないとやらない）
- ボーナス低くて辛い（利益が出ていないのは自分のせいじゃない。そもそも目標数値がおかしいんだ！的な）

## 現職

- 広めたい考え方は**自分でまずやる**（施策要望はGitHub Issueに書こうとか、ノウハウはesaにまとめようとか、日中に通院しても全然構わないとかｗ）
- 本当に今やっている開発で事業が伸びるのか考え、自分でもいろいろ数値を集めて**施策案をどんどん出す**

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 総評的なもの

- エンジニアとしては地力がついて良かった
  - 弊社はWebアプリもメディアもアプリもやるので特にそうかも
  - 逆にいうと、自分は(特定の技術)で生きていくんだって強い意志がある人には大半のアーリースタートアップ向いてないかも
  - 根本的に**好奇心旺盛な人はめっちゃ向いている**と思う
- 価値観が相当変わった
  - **話を聞くのと、「その時間軸に居る」ことは全く違う**
  - ビジネスモデルが仕上がった場所から仕上げる場所に
    - 実際会社がやばくなるといろいろと達観する
  - 組織が作られるのを待つ立場から作る立場に

---
layout: image-header-intro
---

# 告知

---
layout: center-image
---
<style>
  body h1 {
    font-size: 2.rem;
    margin-bottom: 16px;
  }
  body .text-center {
    text-align: left;
  }
  body .col-span-12 {
    margin: auto 48px;
  }
</style>

# マナリンクではエンジニアを採用中です！

<div class="mt-4 text-gray-500 text-sm">
<p>
塾や通信教育に代わるオンライン家庭教師という選択肢を日本中・世界中の学生に普及させませんか？
</p>
<p>
オンライン家庭教師サイトや、オンライン指導アプリを開発する2人目、3人目のエンジニアを採用中です！
</p>
</div>

<h2 class="mt-8">採用技術を知りたい方→テックブログ</h2>

<div class="mt-4 text-gray-500">
<p>
頑張って毎週書いているので読んでください！
</p>
<p class="mt-2">
<a class="underline" href="https://zenn.dev/manalink">https://zenn.dev/manalink</a>
</p>
</div>

<h2 class="mt-8">事業について知りたい方→カジュアル面談</h2>

<div class="mt-4 text-gray-500">
<p>
詳しく訊きたいと思っていただいた方はMeetyでぜひご連絡を！
</p>
<p class="mt-2">
「Meety マナリンク」で検索！
</p>
</div>
