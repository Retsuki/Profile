# 私について

## 自己紹介

| 名前     | 米一 烈希（よねいち れつき）         |
| -------- | ------------------------------------ |
| 生年月日 | 1998/11/18                           |
| 出身     | 石川県                               |
| 趣味     | アプリ開発・小説・ラジオ・漫画・映画 |

### SNS

- 米一烈希 | Facebook https://www.facebook.com/profile.php?id=100007980480408
- Retsuki Yoneichi | LinkedIn https://www.linkedin.com/in/retsuki-yoneichi-ab5408177/
- R ちゃん | Twitter https://twitter.com/duz_mk

## 自己 PR

大学生の頃より企業にてアプリ開発をやっておりましたので、アプリの開発には自信があります！
プログラミングを通して新しい技術のキャッチアップであったり、実装をやっておりましたので、
新しいことへ挑戦することは得意です！自分の意見はしっかりを伝えるタイプです。腑に落ちない場合は徹底的に調べたりするタイプです。
高校生の頃に全校生徒の前でプレゼンをしたことがきっかけで、人前に立つことは好きというか得意になりました。

# 経歴

- [Scheeme 株式会社](https://github.com/Retsuki/Profile/tree/main/career#scheeme-%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%B3%E5%85%A5%E7%A4%BE)
- [ココネ株式会社](https://github.com/Retsuki/Profile/tree/main/career#%E3%82%B3%E3%82%B3%E3%83%8D%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%B3)
- [株式会社 Lightblue-Technology](https://github.com/Retsuki/Profile/tree/main/career#%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE-lightblue-technology%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%B3)
- [東洋大学](https://github.com/Retsuki/Profile/tree/main/career#%E6%9D%B1%E6%B4%8B%E5%A4%A7%E5%AD%A6)

## Scheeme 株式会社（インターン=>入社）

### 期間

2019/05 〜 現在

### 業務内容

補助金・融資支援サービスの構築

誰でも手軽にお金を借りられるサービスの構築です。補助金や融資を受けるには申請書類が必要です。従来は、その申請書類の記入事項が多かったり、そもそも自分にあった補助金や融資を探すこと自体が困難という問題があります。これらの問題を解決するために事業計画書をはじめとする資料の自動作成機能や会計ソフト API や金融機関 API と連携をして損益計算書や資金繰り表などを自動作成する機能の構築を行っております。

担当していることは、Vue, Nuxt によるフロントの構築,Cloud Functions での API の構築, Cloud Build, Cloud Run を使った CI / CD とホスティング環境の構築, 運用, freee や金融機関との API 連携等を幅広くやっております。

新規事業
まだリリースできていないため（クローズドに出している）詳細は言えませんが、
公開しているものとして、本人確認や銀行振込, スコアリングなどの機能があります。

担当していることは、フロントは Flutter, バックエンドは Node, インフラは Firebase メインの GCP を使って横断的に開発しております。直近ですと、prod・stg・dev 環境での構成ミスがあったため terraform の導入と Redis のコストが高いので Redis 排除をすることを行なっております。

## ココネ株式会社（インターン）

### 期間

2019/10 〜 2022/03

### 業務内容

ラジオ配信アプリのユーザープロフィール画像のアップロード機能開発と CMS の作成

s3 署名 URL を使用したプロフのアップロード機能を構築。元々はサーバレス（api gateway, lambda）で作っていたがリクエストのサイズ制限があり、大きめの画像ファイルがアップロードできない問題があったので署名 URL でのアップロードになった。

## 株式会社 Lightblue-Technology（インターン）

### 期間

2018/11 〜 2019/05

### 業務内容

中高生に向けてディープラーニングを説明するサイト制作

cipher100 の約６０００通りの学習モデルを DB に保存。ブラウザ上ではハイパーパラメータを設定できるようになっていて（約６０００通りある）設定に応じて予測精度が変化させることを視認できるように。そうすることでハイパーパラメータによって予測精度も往々に変化することを伝えるような設計にしていた。

## 東洋大学

### 期間

2017/04 〜 2021/03

### 学部・研究内容

情報連携学部・情報連携学科

研究について

研究は盲目の方の補助器具の開発をおこなっておりました。
内容は盲目の方が使用される白状に Lidar をつけて転落事故（駅のホームなど）の未然防止ができないかを実際に装置を作成し、検証するというものでした。

# 個人で開発してきたもの

## 生前贈与アプリ

### 概要

銀行 API を活用した贈与アプリ（最優秀賞受賞）

<img width="400" src="https://prcdn.freetls.fastly.net/release_image/34650/158/34650-158-807226bbf4407f70d07f6e5057dc9d45-816x544.jpg?format=jpeg&auto=webp&quality=85&width=1950&height=1350&fit=bounds" />

### 開発の動機

実務で銀行 API を使用した銀行連携をしていて、たまたま銀行 API を使用したハッカソンがあったので出場することに。
生前贈与アプリを開発するに至った経緯は、少子高齢化の日本を元気にしようとしたいなと思ったからです。そこで、少子高齢化をうまくプラスに考えて人口が多い人たちから子供たちへと気軽にお金を流せるアプリがあればいいなと思ったので生前贈与アプリを開発することになりました。

### 外部リンク

- https://docs.google.com/presentation/d/1nXEOwYIAhc0tPUfYMweHrhVepo5zDlud4l-d9IAmT3Y/edit?usp=sharing
- https://prtimes.jp/main/html/rd/p/000000158.000034650.html

## 石川県版新型コロナのサイト（閉鎖済み）

### 概要

石川県の新型コロナの患者数を日毎にであったり、市毎であったりとグラフ形式で可視化するサイト

### 開発の動機

ちょうど春休みになったタイミングで地元石川県に帰省した。それからコロナの感染が爆発的に拡大し、東京に戻れずインターンも休むことに（当時は、まだリモート環境が整っていなかったため）。暇だったので、東京都が中心に各都道府県のボランティアが新型コロナ感染動向サイトを作っているのを知り、作成することに。

### 外部リンク

- https://qiita.com/Retsuki/items/88eded5e61af200305fb
