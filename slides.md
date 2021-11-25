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
  - https://zenn.dev/meijin
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
- エンジニア以外の活動
  - 社内**新規事業提案**→入賞して1年ほど業務時間のN割で活動
  - 社内イベントや社内制度の**運営委員会(有志)に複数所属**

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 転職後(2019年〜)

- スタートアップでCTO
  - 企画やデザイン、技術選定や負債の認識、採用まで**全部やる**
  - **プライベートの時間や勉強会の主催**などによって新しい技術を習得
- 事業の変遷
  - 入社当時の事業がまったくうまく行かず、入社1年後に**クローズし、ピボット**
  - 資金が尽きかける中、**オンライン家庭教師サービス**を始めて生き延びる！
  - 事業が成長し、今は**エンジニアを採用する余裕**ができた(採用中！)

---
layout: image-header-intro
---

# 観点別Before/After

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 技術力

## 前職

- フロントからバックエンドまで薄く広く
- 主に**jQuery、Symfony、Sinatra**で機能の追加やバグ改修

## 現職

- 自分で技術選定するので、より設計や品質管理、基礎技術を深めるようになった
- 主に**Vue、React、Laravel、React Native**で次々に新規実装
  - QiitaでDDDの記事を書いてバズったり、ZennでReactの記事でバズったり、個人のリポジトリに80starくらいもらえたり

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# スキルマップ

## 前職

- 非常に綿密なスキルマップがあり、**一定のスキルを満たすと証明したら昇級**できる
  - スタートアップに来て、これは本当に凄い制度だと思う

## 現職

- **いつどんなスキルが必要に/不必要になるかわからない**
  - たとえばピボット前はiOSアプリだけやっていたが、ピボット後にクロスプラットフォームになったのでReact Nativeを書き始めた

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 技術に割ける時間

## 前職

- ほとんどの工数が**既存実装調査と他部署調整とテストとMTG**

## 現職

- 他部署調整とかMTGはほぼ無く、リリースフローも短いので次々実装、次々リリース。業務中でもどんどん勉強する

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 技術の勉強

## 前職

- 最低限スキルマップを満たすための勉強と、他のプライベートの時間は新規事業に割いてた
- 社内にテックリード的な方は何人もいるので、レガシーも数年経てば解消されていく

## 現職

- **情報収集**
  - 公式ドキュメント、公式Twitter(通知ON)、リポジトリのIssue
  - Twitter、Zenn、GitHubトレンド、各種ブログ
- **手元で試す**
  - 試してGitHubにPush、template repositoryとして公開
- そして**業務で運用して痛い目に遭う**

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 積める経験

## 前職

- 内部実装が肥大化しているので、社内独特の知識が重要
- 大量の物件データを扱う**大規模なサービスの負債解消**は貴重な実績や経験になる

## 現職

- Webフレームワークに従うことで、他社でも通じる経験を積む
- 大規模なトラフィックを捌いたり、脳死で札束で捌くような経験をすることはできない

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 売上に対する価値観

## 前職(あえて極端な言い方をしてます)

- 等級上げて欲しい（売上収益の伸びが悪くても、自分の技術力が上がったなら無関係に昇級させて欲しい）
- どこからともなく企画がやってきて、そのとおりに実装すると営業さんが売ってくれる

## 現職

- **事業が伸びないと始まらない**ので、施策案を出したり企画から入ったり、CI/CDといった開発速度向上の工夫も欠かさない
- サービスを閉じてピボットするとか言葉としては聞くけど、実際に体験すると不安とか初めて売上が立ったときの達成感とかすごかった
  - **話を聞くのと、「その時間軸に居る」ことは別物**

---
layout: image-right
image: https://raw.githubusercontent.com/lightvue/slidev-theme-light-icons/master/static/light-icons-cover.svg
---

# 総評的なもの

## 大企業のいいところ

- スキルマップがあるため自分の指針になったり、安定したキャリア形成ができる
- 強い人にレビューしてもらったり、負債を解消してもらえる(可能性がある)

## スタートアップのいいところ

- 技術選定を繰り返すので深い知識や幅広い視野、情報収集力が求められるが、待ちの姿勢で過ごすより遥かに成長できる
  - 他社でも通じる技術を使う合理的な理由があるので、ある意味”お買い得”な職歴が積める
- 世の中に無いものを作って、それで売上を立てて、人件費などにどう投資していくかが全て見える

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

# マナリンクはこんなサービスを作っています

<p className="text-[#777] mb-4">
オンライン家庭教師マナリンク(<a target=_blank href=https://manalink.jp>https://manalink.jp</a>)は主に3つのサービスを運営しています。
</p>

<div className="flex w-full gap-3">
  <div className="flex-1 p-4 rounded-md bg-[#A3CFCF44]">
    <h2 className="font-bold">先生を選べるWebサービス</h2>
    <p className="text-xs mt-2">多くの家庭教師サービスとは異なり、一人ひとり厳正に審査した先生のプロフィールページや、自己紹介動画を見て、先生を直接指名することができます。LaravelとNuxt.jsで開発しています。</p>
    <img className="mt-4 mx-auto w-[200px]" src="https://manalink.jp/_ipx/f_webp,s_400x246/img/components/top/feature02.jpg" />
  </div>
  <div className="flex-1 p-4 rounded-md bg-[#A3CFCF44]">
    <h2 className="font-bold">保護者の方も参加する指導アプリ</h2>
    <p className="text-xs mt-2">教育サービスの大きな課題は<b>価値を受ける人（生徒）と対価を支払う人（親）が別人</b>なことです。<br />マナリンクでは専用のReact Native製アプリで先生-生徒間の指導を実施していただき、<b>保護者さんに閲覧権限を与えることで指導内容を可視化</b>します。</p>
    <img className="mt-4 mx-auto w-[160px]" src="https://prtimes.jp/i/40725/16/resize/d40725-16-eb211c51287f6ba5bd44-0.png" />
  </div>
  <div className="flex-1 p-4 rounded-md bg-[#A3CFCF44]">
    <h2 className="font-bold">憧れの仕事にするためのメディア</h2>
    <p className="text-xs mt-2">オンライン家庭教師自体はここ数年でZoom等の普及によって生まれた新しい職業です。<br />そのため、オンライン家庭教師という仕事を普及し<b>より多くの方のキャリアの選択肢に入れてもらう</b>ため、マナリンクTeachersというメディアを公開・運営しています。<br />Next.js × microCMS製です。</p>
    <img className="mt-4 mx-auto w-[240px]" src="https://user-images.githubusercontent.com/7464929/139240626-0b2408e8-95a0-4563-a4aa-6637862029d0.png" />
  </div>
</div>

---
layout: center-image
---

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
