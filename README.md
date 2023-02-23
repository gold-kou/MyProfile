# はじめに
私の職務経歴、個人開発、長所などをまとめたページになります。

# 職務経歴
要件定義・設計・実装・テスト・リリース・レビューなどの一連のシステム開発と運用、サーバ仮想化環境のインフラ構築、技術選定、スクラム導入などの経験があります。複数の部署が関係する20名程度のプロジェクトをリードした経験もあります。特に、バックエンドのAPI開発が得意です。

## 株式会社ZOZO
### ZOZOTOWNのマイクロサービス化(2020-現在)
[プロジェクト概要]

API Gatewayやマイクロサービスの開発と運用およびレガシーシステムの改修を通じて、ZOZOTOWNのシステムリプレスをする。

[技術スタック]

- Go/VBScript/OpenAPI/MySQL/Docker/Kubernetes(EKS)/Datadog/Sentry/GitHub Actions/GitHub

[チーム規模、役割]

- 5人程度のチームでバックエンドエンジニアとして働いております。

[主な担当業務]

- API Gatewayの開発
  - ターゲットグループを跨いだリトライ機能
  - configバリデーション機能
  - スロットリング機能
  - タイムアウト機能（Exponential Backoff and Jitter）
  - 独自ヘッダー追加に伴うヘッダー伝搬とアクセスログの改修
  - リファクタリング
- ID基盤の開発
  - メール本人確認機能
  - ログイン通知機能
  - 削除バッチのベンチマーク
  - リファクタリング
- 会員基盤の開発
  - 会員基本情報のCRUD機能
  - 年齢認証機能
  - データ移行ツール
- レガシーシステムの改修
  - マイクロサービスのAPI実行
- レビュー
- 運用、監視業務
- Goバージョンアップ
- テックブログ執筆
  - https://techblog.zozo.com/entry/zozotown-api-gateway-intro
  - https://techblog.zozo.com/entry/zozotown-api-gateway-availability
  - https://techblog.zozo.com/entry/zozotown-api-gateway-throttling
- 社内勉強会発表
- スクラム導入
- 採用活動

### 生産管理システムの開発(2019-2020、約1年6ヶ月)
[プロジェクト概要]

新規事業に応じたアパレル商品の生産管理に関するシステムの新規開発および改修。


[技術スタック]

- Go/OpenAPI/gRPC/PostgreSQL/Docker/Nginx/AWS(ECS/Fargate/EC2/OpsWorks/Lambda/RDS/DynamoDB/S3など)/Digdag/Datadog/CircleCI/GitHub

[チーム規模、役割]

- 10人程度のチームでテックリード兼バックエンドエンジニア兼スラクムマスターとして働いておりました。

[主な担当業務]

- 工場におけるアパレル商品の生産に関する発注・工程・出荷などを管理するシステムの開発
- アパレル商品のマスタ情報を管理するシステムの開発
- 社内システム間のデータ連携システムの開発
- Alibaba CloudとAWSの通信性能検証
- レビュー
- 運用、監視業務
- 技術選定(言語、アーキテクチャ、外部ライブラリなど) 、技術調査
- スクラムの導入
- 開発ガイドライン策定
- テンプレート作成
- テックブログ執筆
  - https://techblog.zozo.com/entry/openapi3/go
- 社内勉強会発表

## NTTコムウェア株式会社
### パブリッククラウドサービスの開発(2018、約3ヶ月)
※プロジェクト配属後すぐの転職となったため期間が短いです。

[プロジェクト概要]

パブリッククラウドサービスの開発および運用。

[技術スタック]

- Ruby/sidekiq/Redis/Ansible/GitHub/Jenkins/Scrum/JIRA/Confluence/Slack

[チーム規模、役割]

- 10名程度のチームで、バックエンドエンジニアとして働いておりました。

[主な担当業務]

- SSD寿命に関するアラート発砲機能の開発
- Ansibleのplaybook修正
- 運用業務

### OpenStackの導入検証(2018年、約9ヶ月)
[プロジェクト概要]

大規模IP電話サービスにOpenStackを導入するための技術検証。

[技術スタック]

- OpenStack/KVM/Ansible/SR-IOV/CPUピニング/HugePage/NUMA

[チーム規模、役割]

- 10名程度のチームで、システムエンジニアとして働いておりました。

[主な担当業務]

- OpenStack環境構築と構築手順書の作成
- Ansibleを用いたOpenStack環境の正常性確認の自動化
- OpenStack環境上の仮想リソースの作成
- SR-IOV、CPUピニング、HugePage、NUMAなどを用いたインフラの高速化チューニング設定

### 無人受付システムのPoC開発(2017年、約3ヶ月)
※PoC開発のため期間が短いです。

[プロジェクト概要]

中国に駐在し、オフィスビルの受付業務をスマートフォンとビーコンにより自動化するWebサービスの開発。

[技術スタック]

- Python/Flask/HTML/CSS/JavaScript/Java(Android)/Nginx/AWS/Jenkins/GitLab/Scrum/JIRA/Confluence/mattermost

[チーム規模、役割]

- 10名弱程度(日本人、中国人混在)のチームで、システムエンジニアとして働いておりました。

[主な担当業務]

- 技術スタック、アーキテクチャ選定
- AWS環境構築
- 開発メンバのローカル開発環境構築
- ディレクトリテンプレートの作成
- 設計(IF/DB/画面遷移)
- 実装(UT含む)
- レビュー
- 試験
- リファクタリング
- スクラム各種イベント
- 社内成果発表

### サーバ仮想化・自動化に関する技術調査およびPoC開発(2016-2017年、約1年6ヶ月)
[プロジェクト概要]

技術調査やPoC開発を通じて大手通信企業様のインフラコストを省力化する提案をする。

[技術スタック]

- NFV/OpenStack/KVM/Vagrant/Virtualbox/KickStart/Ansible/Fluentd/Zabbix
- Python/Flask/Java/HTML/CSS/JavaScript/MySQL/Nginx/Jenkins/GitBucket

[チーム規模、役割]

- 10名程度のチームで、システムエンジニアとして働いておりました。

[主な担当業務]

- NFVシナリオ（オートヒーリング、スケールアウト、システムアップデート）用のインフラ構築
  - 検証環境サーバ約10台のLinuxOSのインストール
  - Teratermマクロの作成
  - ローカルリポジトリ構築
  - OpenStack環境構築（手動）
  - OpenStack仮想リソース作成・削除のシェルスクリプト作成
- 試験用ワンコールシステムのIFアダプタ、管理システムの開発
  - ローカル、テスト、CIに関する環境構築
  - 外部システム（テストコールシステム、MANO）に関する社外への仕様問い合わせ
  - 設計(シーケンス図/REST-API/RDB/画面/メッセージ仕様)
  - 実装(UT含む)
  - 試験
  - リリース
- 技術調査
  - KickStart、Ansible、Zabbixによる構成自動化と監視に関する技術調査と提案
  - OSSのMANO(OpenBaton/Tacker/Open Source MANO)の調査および動作検証
　　 - 検証用物理サーバのOSインストールとネットワーク設定
  - Dockerの調査と社内勉強会の開催
  - VagrantとVirtualboxによるOpenStackのcontrollerとcomputeノード用の仮想インスタンス生成の自動化
  - OpenStack環境構築を自動化するAnsibleのplaybook実装

### 4次元可視化システムのプロトタイプ開発および提案(2015年、約6ヶ月)
[プロジェクト概要]

4次元（XYZ平面および時間軸）可視化するシステムのプロトタイプを開発し、お客様へ提案する。

[技術スタック]

- JavaScript/Three.js/HTML/CSS

[チーム規模、役割]

- 2名程度のチームで、システムエンジニアとして働いておりました。

[主な担当業務]

- ネットワークの帯域使用率を可視化する4次元可視化システムのプロトタイプ開発と提案。
- 河川の水位を可視化する4次元可視化システムのプロトタイプ開発と提案。

# 学生時代の研究
大学および大学院では自然言語処理と機械学習に関する研究をしておりました。
「人間の大脳皮質の情報処理原理を用いたテキストのカテゴリー分類」というテーマで国際学会(クアラルンプール)に登壇して発表した経験があります。以下は論文のリンクになります。

https://www.researchgate.net/publication/268444818_Text_Classification_Using_Computational_Model_of_the_Cerebral_Cortex

# 個人開発
## 猫画像専用のSNSサービス
### 概要
猫画像のみを投稿できるSNSサービスです。

### 技術スタック
HTML/CSS/JavaScript/React/Go/OpenAPI/MySQL/Docker/AWS/Terraform/GitHub/GitHub Actions

### GitHub
https://github.com/gold-kou/ToeBeans

## ジャニーズ顔判定ができるWebサービス
### 概要
ユーザ登録一切不要で、顔写真をアップロードするだけで、その顔がジャニーズ顔かどうかを判定できるWebサービスです。継続的にご利用いただいておりましたが、現在はインフラコストの都合上停止中です。ニュースサイトGigazineでも[紹介](https://gigazine.net/news/20180808-johnnys-face/)されました。

説明記事：
[AIを使って自分の顔がジャニーズ系かどうかを判定するWebサービスを作ってみた](https://qiita.com/gold-kou/items/e1a96657a63b043c4564)

### 技術スタック
Python/Flask/HTML/CSS(BootStrap)/JavaScript/Nginx/AWS(EC2/Route53など)/GCP(GCS/GCV)/OpenCV/scikit-learn

### GitHub
https://github.com/gold-kou/face-audition-johnnys

## スマートスピーカーを使った雨傘備忘通知サービス
### 概要
帰宅時刻の天気が悪天候であれば毎朝自動で傘を忘れないように音声通知してくれるサービスです。

説明記事：
[「え！？朝は雨降ってなかったのに！傘持ってきてないよ〜。」を解決するGoogleHome連携アプリを作ってみた](https://qiita.com/gold-kou/items/887c79a58ad496e417d6)

### 技術スタック
Python/Node.js/Google Home

### GitHub
https://github.com/gold-kou/never-forget-umbrella

# 長所
私の最大の長所は、勉強熱心であることです。業務やキャリアに役立つ技術を日々勉強しています。勉強熱心であることは、変革の激しいIT業界において、常に成長し、活躍し続けられるために必要な能力だと考えています。この長所を活かし、たとえ未経験の技術や分野であっても迅速にキャッチアップし、業務で貢献します。

学習例：

- 個人開発を通じた技術力向上
- Qiitaへの記事投稿。これまでにGoやDockerなどに関する記事を50以上投稿し、25000以上のContributionsを獲得しております。
  - https://qiita.com/gold-kou
- 技術書籍

# 資格
- 認定スクラムマスター
- 応用情報技術者
- TOEIC790
  
# 各種リンク
- [Qiita](https://qiita.com/gold-kou)
- [stack overflow](https://stackoverflow.com/users/9048198/gold-kou)
- [LinkedIn](https://www.linkedin.com/in/koki-hatano-258a42166/)
