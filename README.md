# はじめに
私の技術スタック、職務経歴、ポートフォリオ、長所などをまとめたページになります。

# テクニカルスキル
Go/Java/Python/Flask/HTML/CSS/JavaScript

PostgreSQL/MySQL/sqlite/Redis/DynamoDB

AWS/CloudFormation/Terraform/Ansible/Vagrant/Docker/OpenStack/KVM

# 職務経歴
上流〜下流工程の一連のシステム開発、サーバ仮想化環境のインフラ構築、技術選定、スクラム導入などの経験があります。

特に、バックエンドのAPI開発に強みがあります。

## ZOZOTOWNのマイクロサービス化(2020-現在)
[プロジェクト概要]
API Gateway、認証基盤の開発や運用。

[技術スタック]

- Go/OpenAPI/MySQL/Docker/Kubernetes(EKS)/Datadog/Sentry/GitHub Actions/GitHub

[チーム規模、役割]

- 5人のチームでバックエンドエンジニアとして働いております。

[担当業務]

- API Gatewayの開発
  - リトライ機能
  - configバリデーション機能
  - スロットリング機能
  - タイムアウト機能
  - リファクタリングなど
- ID基盤の開発
  - メール本人確認機能
  - 削除バッチのベンチマーク
  - リファクタリングなど
- 運用、監視業務
- テックブログ執筆
  - https://techblog.zozo.com/entry/zozotown-api-gateway-intro
  - https://techblog.zozo.com/entry/zozotown-api-gateway-availability
- 採用

## アパラル商品の生産管理システムの開発(2019-2020、1年6ヶ月)
[プロジェクト概要]

- 工場におけるアパレル商品の生産に関する発注・工程・出荷などを管理するシステムの開発
- アパレル商品のマスタ情報を管理する業務システムの開発
- 社内システム間のデータ連携システムの開発
- Alibaba CloudとAWSの通信性能検証

[技術スタック]

- Go/OpenAPI/gRPC/PostgreSQL/Docker/Nginx/AWS(ECS/Fargate/EC2/OpsWorks/Lambda/RDS/DynamoDB/S3など)/Digdag/Datadog/CircleCI/GitHub

[チーム規模、役割]

- 10人程度のチームでテックリード兼バックエンドエンジニア兼スラクムマスターとして働いておりました。

[担当業務]

- 新規システムの開発、既存システムの改修
  - 技術選定(言語、アーキテクチャ、外部ライブラリなど) 、技術調査
  - インフラ構築
    - インフラアーキテクチャ設計
    - CloudFormationの実装
  - 設計（仕様書、DB、API、ログなど）
  - 実装
  - 試験
  - リリース
  - レビュー 
- 開発補助業務
  - 開発ガイドライン策定
  - テンプレート作成
  - 勉強会開催

## パブリッククラウドサービスの開発(2018、約3ヶ月)
[プロジェクト概要]

- パブリッククラウドサービスの機能追加開発および運用。

[技術スタック]

- Ruby/sidekiq/Redis/Ansible/GitHub/Jenkins/Scrum/JIRA/Confluence/Slack

[チーム規模、役割]

- 10名程度のチームで、バックエンドエンジニアとして働いておりました。

[担当業務]

- SSD寿命情報に関するアラート発砲機能の開発およびUT実装
- Ansibleのplaybook修正
- API公開ドキュメントの修正
- 運用業務

## 大規模IP電話サービスへのOpenStack導入(2018年、約9ヶ月)
[プロジェクト概要]

- 全国規模の大規模IP電話サービスをOpenStack上で運用するための技術検証

[技術スタック]

- OpenStack/KVM/Ansible/SR-IOV/CPUピニング/HugePage/NUMA

[チーム規模、役割]

- 10名程度のチームで、インフラエンジニアとして働いておりました。

[担当業務]

- OpenStack環境構築と構築手順書の作成
- SR-IOV、CPUピニング、HugePage、NUMAなどを用いたインフラの高速化チューニング設定
- Ansibleを用いたOpenStack環境の正常性確認の自動化
- OpenStack環境上の仮想リソースの作成
- 落雷トラブル対応

## 無人受付システムの開発(2017年、約3ヶ月)
[プロジェクト概要]

- オフィスビルの受付業務をスマートフォンとビーコンにより自動化するWebサービスの開発。
- 中国に駐在して開発しました。

[技術スタック]

- Python/Flask/HTML/CSS/JavaScript/Java(Android)/Nginx/AWS/Jenkins/GitLab/Scrum/JIRA/Confluence/mattermost

[チーム規模、役割]

- 10名弱程度(日本人、中国人混在)のチームで、テックリード兼バックエンジニアとして働いておりました。

[担当業務]

- 技術スタック、アーキテクチャ選定
- Python/Flaskをチームメンバへレクチャ
- Gitをチームメンバへレクチャ
- AWS環境構築
- 開発メンバのローカル開発環境構築
- ディレクトリテンプレートの作成
- 設計(IF/DB/画面遷移)
- 実装(UT含む)
- ソースコードレビュー
- 試験
- リファクタリング
- スクラム各種イベント
- ネットワークトラブル(メールやLINEメッセージ送信の失敗、push通知リクエストの失敗など)対応
- 帰国後に50人程度規模の社内向けスクラム開発イベントで登壇発表

## サーバ仮想化および自動化に関する技術調査と提案(2017年、約9ヶ月)
[プロジェクト概要]

- 国内大手通信企業様のサーバの仮想化と自動化の導入に向けた技術的調査と提案。
- サーバ仮想化や自動化に関するOSSの調査および動作検証などを実施し、調査内容を社内共有する。

[技術スタック]

- KVM/KickStart/Ansible/Zabbix
- Docker/kola-ansible/NFV/OpenStack/Vagrant/Virtualbox/Java/Fluentd/Norikra/GitBucket

[チーム規模、役割]

- 2名のチームで、営業SEとして働いておりました。

[担当業務]

- 以下の契約前の技術調査と提案と見積もりの作成
  - KickStartに関する技術調査および動作検証
  - AnsibleによるゲストOSインストールと必要パッケージインストール作業の自動化に関する技術調査および動作検証
  - ZabbixによるホストOS側のIPMIやプロセスなどの監視に関する技術調査および動作検証
- Dockerの調査および動作検証を実施し、社内勉強会を開催。
- kolla-ansible(OpenStackの各コンポーネントをコンテナとして扱うことでOpenStackのバージョン更新作業を簡易化するコンポーネント)の調査および動作検証を実施し、社内勉強会を開催。
- OSSのMANO(OpenBaton/ Tacker/Open Source MANO)の各公式ドキュメントからドキュメント充実度・機能充実度・コミュニティ活発度などを調査比較。OpenBatonを調査対象として決定。
- 検証用物理サーバのOSインストールとネットワーク設定
- VagrantとVirtualboxによるOpenStackのcontrollerとcomputeノード用の仮想インスタンス生成の自動化。
- OpenStack環境構築を自動化するAnsibleのplaybook実装。
- OpenBatonのInstantiation/Termination機能を動作検証。
- 社内セキュリティ環境やバグに対応したOpenBatonの改良を実装。
- OpenBatonのログ処理のバグfixに関するOSSへの貢献。
- OpenBatonのインストールドキュメント不備に関するOSSへの貢献。

## NFV導入に向けたインフラ構築とWebアプリケーションの開発(2016年、約9ヶ月)
[プロジェクト概要]

- 大規模電話サービス向けのNFVシナリオ（オートヒーリング、スケールアウト、システムアップデート）用のインフラ構築
- 試験用ワンコールシステムのIFアダプタの開発
- NFV管理システムの開発

[技術スタック]

- NFV/OpenStack/KVM/Ubuntu
- Python/Flask/Java/HTML/CSS/JavaScript/MySQL/Nginx/Jenkins/GitBucket

[チーム規模、役割]

- 5名程度のチームで、インフラエンジニア兼バックエンドエンジニアとして働いておりました。

[担当業務]

- 検証環境サーバ約10台のLinuxOSのインストール
- Teratermマクロの作成
- ローカルリポジトリ構築
- OpenStack環境構築（手動）
- OpenStack仮想リソース作成・削除のシェルスクリプト作成
- GitBucketサーバの構築
- チャットサーバ(mattermost)の構築
- GitBucketによるスクリプトとマクロのバージョン管理
- ローカル開発環境構築(Python、Javaなど)
- IT環境構築
- CI環境構築
- 外部システム（テストコールシステム、MANO）に関する社外への仕様問い合わせ
- 設計(シーケンス図/REST-API/RDB/画面/メッセージ仕様)
- 実装(UT含む)
- 試験
- リリース

## 4次元可視化システムの開発および提案(2015年、約6ヶ月)
[プロジェクト概要]

- XYZ平面および時間軸でjsonデータを4次元可視化するシステムのプロトタイプを開発し、営業担当と同行し提案する。

[技術スタック]

- JavaScript/Three.js/HTML/CSS

[チーム規模、役割]

- 2名程度のチームで、フロントエンドエンジニアとして働いておりました。

[担当業務]

- 大手海外通信企業様向けにネットワークの帯域使用率を可視化する4次元可視化システムのプロトタイプ開発と提案を実施。
- 水道管理システム企業様向けに河川の水位を可視化する4次元可視化システムのプロトタイプ開発と提案を実施。

# 学生時代の研究
大学および大学院では自然言語処理と機械学習に関する研究をしておりました。
「人間の大脳皮質の情報処理原理を用いたテキストのカテゴリー分類」というテーマで国際学会に登壇して発表した経験があります。以下は論文のリンクになります。

https://www.researchgate.net/publication/268444818_Text_Classification_Using_Computational_Model_of_the_Cerebral_Cortex

# 個人開発
## 猫画像専用のSNSサービス
Commin soon

## ジャニーズ顔判定ができるWebサービス
Python/Flask/HTML/CSS(BootStrap)/JavaScript/Nginx/AWS(EC2/Route53など)/GCP(GCS/GCV)/OpenCV/scikit-learn

ユーザ登録一切不要で、顔写真をアップロードするだけで、その顔がジャニーズ顔かどうかを判定できるWebサービスです。継続的にご利用いただいておりましたが、現在はインフラコストの都合上停止中です。ニュースサイトGigazineでも特集されました。

紹介記事：
[AIを使って自分の顔がジャニーズ系かどうかを判定するWebサービスを作ってみた](https://qiita.com/gold-kou/items/e1a96657a63b043c4564)

GitHub：
https://github.com/gold-kou/face-audition-johnnys

## スマートスピーカーを使った雨傘備忘通知サービス
Python/Node.js/Google Home

帰宅時刻の天気が悪天候であれば毎朝自動で傘を忘れないように音声通知してくれるサービスです。

紹介記事：
[「え！？朝は雨降ってなかったのに！傘持ってきてないよ〜。」を解決するGoogleHome連携アプリを作ってみた](https://qiita.com/gold-kou/items/887c79a58ad496e417d6)

GitHub：
https://github.com/gold-kou/never-forget-umbrella

# 長所
私の最大の長所は、勉強熱心であることです。
業務やキャリアに役立つ技術を日々勉強しています。

学習例：

- 「ジャニーズ顔判定できるWebサービス」、「スマートスピーカーを使った備忘通知アプリ」などの個人開発
  - ジャニーズ顔判定できるWebサービスは、Gigazineに取り上げていただき、リリース1週間で2万リクエストを達成しました。
  - https://gigazine.net/news/20180808-johnnys-face/
- Qiitaへの記事投稿。これまでにGoやDockerなどに関する記事を50以上投稿し、10000以上のContributionsを獲得しております。
  - https://qiita.com/gold-kou
- 大学院卒業後、累計30冊以上の技術書籍の学習
- 毎日30分の英語リスニング・シャドーイング
- 英単語帳学習

勉強熱心であることは、変革の激しいIT業界において、常に成長し、活躍し続けられるために必要な能力だと考えています。
この長所を活かし、たとえ未経験の技術や分野であっても迅速にキャッチアップし、業務で貢献します。

# 資格
- 認定スクラムマスター
- 応用情報技術者
- TOEIC790

# コミュニケーション言語
- 日本語
  - ネイティブ
- 英語
  - 流暢ではないがコミュニケーションは可能です（今後の学習意欲も高いです、継続的に勉強しています。）
  - TOEIC: 790点
  
# 各種リンク
- [Qiita](https://qiita.com/gold-kou)
- [stack overflow](https://stackoverflow.com/users/9048198/gold-kou)
- [LinkedIn](https://www.linkedin.com/in/koki-hatano-258a42166/)
