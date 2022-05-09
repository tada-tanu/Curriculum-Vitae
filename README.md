# 職務経歴書

## 基本情報

| key      | value                                                 |
| -------- | ----------------------------------------------------- |
| 名前     | 多田悠二 (Tada Yuji)                                  |
| 生まれ   | 1994/09/30 （27才）, 青森県弘前市出身                 |
| 最終学歴 | 八戸高専 専攻科 機械システムデザインコース (大卒相当) |

### 職歴

| 期間              | 社名・職種                                             |
| ----------------- | ------------------------------------------------------ |
| 現職 (2021/01~)   | vivit株式会社 iOSエンジニア / アナリティクスエンジニア |
| 2019/03 ~ 2020/12 | 株式会社イオシス 社内SE                                |
| 2017/04 ~ 2019/02 | 日揮株式会社 機械設計エンジニア                        |



## スキル

### 言語

- SQL
    - MySQLとBigQuery
- Python
    - 現職にてELTと可視化に使用。主にPandasとPlotly
    - 自社メディアレコメンドエンジン開発時にはscikit-learn
- Swift
    - RxSwit, ReactorKit
- 日本語
	  - ネイティブ
- English
	  - 新卒の会社(6年前)にて、海外ベンダーと技術的折衝の経験あり。当時はTOEIC650点程。
- 他、業務経験ありの言語
    - PHP, HTML, CSS, Ruby, Golang, Java, JavaScript, TypeScript, ShellScript, Git, ApacheSpark

### ツール

- GCP
- スプレッドシート
    - EDAや軽く可視化する時に使用
- データポータル
    - ダッシュボード作りと丁寧にレポーティングする時に使用
    - データポータルをBIツールとして社内導入した経験あり
- GAS
    - レポートの定時Slack通知やスプレッドシートでのETLに使用

### その他

- 機械設計
- 統計学（再入門中）

## 強み

- PJを推し進めた経験が多い。自責で物事を捉え、自分が成功させるという気概がある。
- 物事を論理的に整理する事が得意。
- 人に何かを教えやり説明する事が得意。1対1でも、1対多の状況でも。

## 弱み

- 理論の堅固性を掴むために、懐疑的な態度になる事がしばしば。個人的な批判と取られる可能性が大きいため、人ではなくデータ・事実に意識が向けられていることをわかってもらうよう努めている。

## やったことはないが興味があるもの

- データ分析チームに入り、PDCAを回し続ける事
- dbtを用いたパイプライン構築
- 競合他社サイトのスクレイピング及び自然言語処理を用いての自社サイトとの定量比較
- 勉強会・セミナーでの登壇

## 職務経歴

### 2021/1- 現在 : [vivit株式会社](https://vivit.co.jp)

　入社から約半年はiOSエンジニアとして、自社アウトドアメディア[hinata](https://hinata.me)の [iOSアプリ](https://apps.apple.com/jp/app/%E3%82%AD%E3%83%A3%E3%83%B3%E3%83%97%E6%83%85%E5%A0%B1%E3%81%AA%E3%82%89-hinata-%E3%81%8D%E3%81%A3%E3%81%A8%E3%81%9D%E3%81%A8%E3%81%8C%E5%A5%BD%E3%81%8D%E3%81%AB%E3%81%AA%E3%82%8B/id1215525884)機能開発に従事していました。その後、経営方針の変更によりアプリ開発が凍結されたため、予てより興味があったデータエンジニアに転身しました。社内にデータ分析・データエンジニアチームがあったわけではなかったため、ゼロから独学でスタートしました。主に、社内からデータ分析課題を収集してELT, 可視化, レポーティングに従事しています。

#### 社内のアクセス解析ツール移行（UAからGA4へ） (2022/04 - 現在)

- 要旨: 社内で使用されているアクセス解析ツールはGoogle Analyticsで、バージョンは「Universal Analytics(以降、UA)」です。UAは2023年7月に測定が停止される旨がGoogle公式から発表されたため、新しいバージョン「GA4」へ速やかに移行する必要があります。私はこの移行PJのリーダーとして、計画立案、UAとGA4の仕様調査、移行設計を行っています。
- ポジション: PJリーダー（対全社）
- 使用技術: Python, BigQuery, Google Analytics, データポータル

#### hinata 記事定量分析 (2022/02 - 現在)

- 要旨: hinataの記事に関して、社内で定量的な分析が行えていない課題を収集し、可視化・考察を関係各所へレポーティングしています。
    - 課題例①: hinataのブランディング戦略をするための繁閑比記事閲覧傾向
    - 課題例②: 自社サイト上とスマートニュース上でのヒット記事傾向
- ポジション: 分析作業メンバー
- 使用技術: Python, BigQuery, Google Analytics, データポータル, スプレッドシート

#### hinata 記事レコメンドエンジン開発 (2022/11 - 2022/01)

- 要旨: hinataの記事ページに類似記事を表示させて内部回遊を向上させるために、レコメンドエンジンの開発に従事しました。SaaSのレコメンドエンジンが導入されていたものの、この時開発したレコメンドエンジンに置き換える事でCTRは約5倍向上する結果となりました。
- ポジション: 開発リード (メンバー4名)
- 使用技術: Python(自然言語処理), BigQuery(DWH), Google Cloud Storage(中間データ), Docker(デプロイ)

#### データエンジニア・アナリストとしての社内営業活動 (2021/08 - 2021/11)

- 要旨: データ分析チームがない状況で、知見ゼロからデータエンジニア・アナリストに転向した私の最初の活動です。データ分析チームが存在しないため、社内で自分の売り込みを行い仕事を作る必要がありました。当時私が保有していた分析スキルはSQLとデータポータルのみだった事と、社内で使われている分析ツールがGoogle Analyticsのみだった事から、Webアクセス解析におけるGAよりも少し踏み込んだデータ可視化を粛々と行っていました。
    - 参考記事: [社内転職してアプリエンジニアからデータエンジニアになった話 - vivit engineering blog](https://vivit.hatenablog.com/entry/2021/11/22/070000)

#### hinataアプリ iOS版の機能開発 (2021/01 - 2021/08)

- 要旨: hinata iOSアプリの機能開発に従事しました。
    - 開発事例①: Firebaseを用いたIn-appメッセージ及びPush通知機能導入
    - 開発事例②: 自社運営キャンプ場検索サイト[hinata spot](https://hinata-spot.me)閲覧タブの追加
    - 開発事例③: Firebaseを用いたABテスト機能導入
    - 開発事例④: RxSwift単体で書かれたページをReactorKitで書き換え
- ポジション: 開発メンバーとスクラムマスター兼任 (開発メンバー2名, デザイナー1名, ビジネスサイド2名)
- 使用技術: Swift5 (ReactorKit, XCTest, XCUITest), Fastlane, Firebase

### 2019/3 - 2020/12: [株式会社イオシス](https://corporate.iosys.co.jp/)

　社内SEとして、社内システムの開発・運用・保守と社内ネットワーク機器導入・整備に従事しました。社内システムはLAMP環境のWebアプリとiOSアプリです。入社当時はITエンジニア未経験だったため、この会社でコンピューターサイエンスの基礎およびWeb/iOS開発のイロハを習得しました。

　経験PJは今のキャリアに大きく影響を与えた代表1つを紹介致します。

#### 社内向けBIツール開発・導入PJ  (2020/03 - 2020/08)

- 要旨: 社内にGoogleデータポータルをBIツールとして導入しました。具体的には、データ基盤の設計・開発、ETLパイプライン構築、データポータルマニュアル作成及び経営層へのトレーニングを行いました。
- ポジション: PJリーダー （要件定義・設計・実装・社内調整、メンバーは私一人）
- 使用技術: MySQL(ソース),  gcloud/PHP/Shell(ETLパイプライン), BigQuery(DWH), データポータル
