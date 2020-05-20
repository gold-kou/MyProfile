# 職務経歴書
私の職務経歴や技術スタック、ポートフォリオ、長所などをまとめたページになります。

## 職務経歴概要
- 約3年間のシステム開発の業務経験があります。設計、実装、テスト、リリースなど一連の開発工程に加えて、アーキテクチャ選定や技術選定、スクラム導入などの経験もあります。
- 約2年間のプライベートクラウド、サーバ仮想化、自動化関連のインフラ業務経験があります。ホストOSのインストールから始まり、OpenStack環境の構築、仮想リソース作成、Ansibleを使った自動化などを実施しました。

## 職務経歴詳細
### アパラル商品の生産・発注管理システムの開発(2019-現在、約1年3ヶ月)
[プロジェクト概要]

- アパレル商品の生産発注・生産工程・出荷などを管理するシステムの開発
- アパレル商品のマスタ情報を管理するシステムの開発
- 社内システム間のデータ連携システムの開発
- AlibabaとAWSの通信性能検証

[技術スタック]

- Go/OpenAPI/gRPC/PostgreSQL/Docker/Nginx/AWS(ECS/Fargate/EC2/OpsWorks/Lambda/RDS/DynamoDB/S3/CloudFormationなど)/Digdag/Datadog/CircleCI/GitHub/JIRA/Confluence/Slack

[チーム規模、役割]

- 10人弱程度のチームでテックリード兼バックエンドエンジニア兼スラクムマスターとして働いております。

[担当業務]

- 開発作業
  - インフラ構築
    - インフラアーキテクチャ選定
    - CloudFormationの実装
  - 設計
    - 機能要件書作成
    - RDBテーブル設計
    - DynamoDBテーブル設計
    - IF設計(OpenAPI/gRPC)
    - ログ設計
  - 実装  
    - コーディング
    - UT
    - ソースコードレビュー
  - 試験
    - 結合試験の実施
    - 総合試験項目書の作成
  - リリース
- 開発管理業務  
  - タスク管理
  - 業務委託者管理
  - 開発ルール整備
    - コーディング規約の策定
    - RVパスルールの策定
    - JIRA運用ルールの策定
    - PRルールの策定
  - 各種ドキュメント整備
    - リリース手順書
    - 連携システムAPI実行手順書
    - DB接続手順書
    - ローカル環境構築手順書
    - API追加開発の手引き
    - 障害発生時の原因解析手順書
    - 開発Tipsページの作成
- 開発補助業務
  - リファクタリング
  - 技術選定(言語、アーキテクチャ、外部ライブラリなど) 
  - ディレクトリテンプレート作成
  - 事前技術調査
  - AWSとAlibabaの性能比較  
  - 新規ソリューションの導入
    - MultiServices/MicroServicesの導入
    - gRPCの導入
    - スクラム導入
      - 勉強会開催
      - ルール整備
      - イベント用ページの整備
      - 妨害BLの管理

### パブリッククラウドサービスの開発(2018、約3ヶ月)
[プロジェクト概要]

- 企業向けパブリッククラウドサービスEnterprise Cloud2.0におけるベアメタルサービスの追加開発および運用。

[技術スタック]

- Ruby/sidekiq/Redis/Ansible/GitHub/Jenkins/Scrum/JIRA/Confluence

[チーム規模、役割]

- 10名程度のチームで、バックエンドエンジニアとして働いておりました。

[担当業務]

- SSD寿命情報の定期取得とアラーム発砲機能の開発およびUT実装
- Ansibleのplaybook修正
- API公開ドキュメントの修正
- 運用業務

### 大規模IP電話サービスのOpenStack導入に向けた検証(2018年、約9ヶ月)
[プロジェクト概要]

- 全国規模の大規模IP電話サービスをOpenStack上で構築・運用するために、商用環境を想定した技術検証。

[技術スタック]

- OpenStack/KVM/Ansible/SR-IOV/CPUピニング/HugePage/NUMA

[チーム規模、役割]

- 10名程度のチームで、PM補佐兼インフラエンジニアとして働いておりました。

[担当業務]

- 複数のOpenStack環境構築と構築手順書の作成
- SR-IOV、CPUピニング、HugePage、NUMAなどを用いたインフラの高速化チューニング設定
- Ansibleを用いたOpenStack環境の正常性確認の自動化
- OpenStack環境上の仮想リソースの作成
- 協力会社と社内メンバへの作業指示および管理
- 2度の落雷トラブル発生時の復旧作業と問題切り分けを指揮し、他社のアプリベンダや物理インフラ担当ベンダなどとコミュニケーションをとりながら、短期間で復旧。
- 自身の英語力を活かしてアプリベンダの海外エンジニアと直接コミュニケーションを取ることで効率的に作業を進めた。

### 中国での無人受付システムの開発(2017年、約3ヶ月)
[プロジェクト概要]

- 受付業務をネイティブアプリとビーコンにより無人化するWebサービスを中国に常駐して開発する。

[技術スタック]

- Python/Flask/HTML/CSS/JavaScript/Android/Nginx/AWS/Jenkins/GitLab/Scrum/JIRA/Confluence/mattermost

[チーム規模、役割]

- 10名弱程度(日本人、中国人混在)のチームで、テックリード兼バックエンジニアとして働いておりました。

[担当業務]

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
- プロジェクト開始前からプロダクトオーナーやSDK開発チームと積極的にコミュニケーションし開発メンバへ情報共有
- 技術スタック、アーキテクチャ選定
- Python/Flaskをチームメンバへレクチャ
- Gitをチームメンバへレクチャ
- 帰国後に50人程度規模の社内向けスクラム開発イベントで登壇

### サーバ仮想化および自動化に関する技術調査と提案(2017年、約3ヶ月)
[プロジェクト概要]

- 国内大手通信企業様のカスタマーコントローラサーバ（エンドユーザが自身の申し込んだ通信サービスの設定を変更できるサーバ）のハイパーバイザ型仮想化と自動化の導入に向けた調査と提案。

[技術スタック]

- KVM/KickStart/Ansible/Zabbix

[チーム規模、役割]

- 2名のチームで、営業SEとして働いておりました。

[担当業務]

- 契約前の技術調査と提案と見積もり
- KickStartに関する調査および動作検証
- AnsibleによるゲストOSインストールと必要パッケージインストール作業の自動化に関する調査および動作検証と工数見積もり
- ZabbixによるホストOS側のIPMIやプロセスなどの監視に関する調査および動作検証

### サーバ仮想化関連のOSS調査(2017年、約6ヶ月)
[プロジェクト概要]

- サーバ仮想化や自動化に関するOSSの調査および動作検証などを実施し、調査内容を社内共有する。

[技術スタック]

- Docker/kola-ansible/NFV/OpenStack/Vagrant/Virtualbox/Java/Fluentd/Norikra/GitBucket/Jenkins/JIRA/Confluence/mattermost

[チーム規模、役割]

- 1名で、OSS調査員として働いておりました。

[担当業務]

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

### NFV検証用システムの開発(2016年、約6ヶ月)
[プロジェクト概要]

- NFV検証に関する「試験用ワンコールシステムのIFアダプタの開発」および「NFV管理システムの開発」

[技術スタック]

- Python/Flask/Java/HTML/CSS/JavaScript/MySQL/Nginx/Jenkins/NFV/GitBucket/JIRA/Confluence/mattermost

[チーム規模、役割]

- 5名程度のチームで、バックエンドエンジニアとして働いておりました。

[担当業務]

- ローカル開発環境構築(Python、Javaなど)
- IT環境構築
- CI環境構築
- 外部システム（テストコールシステム、MANO）に関する社外への仕様問い合わせ
- 設計(シーケンス図/REST-API/RDB/画面/メッセージ仕様)
- 実装(UT含む)
- 試験
- リリース

### NFV検証環境の構築(2016年、約3ヶ月)
[プロジェクト概要]

- 大規模電話サービス向けのNFVシナリオ（オートヒーリング、スケールアウト、システムアップデート）検証用の環境構築および検証を実施し、提案する。

[技術スタック]

- NFV/OpenStack/KVM/Ubuntu/GitBucket/Redmine/mattermost

[チーム規模、役割]

- 10名弱程度のチームで、インフラエンジニアとして働いておりました。

[担当業務]

- 検証環境サーバ約10台のLinuxOSのインストール
- Teratermマクロの作成
- ローカルリポジトリ構築
- OpenStack環境構築（手動）
- OpenStack仮想リソース作成・削除のシェルスクリプト作成
- GitBucketサーバの構築
- チャットサーバ(mattermost)の構築
- GitBucketによるスクリプトとマクロのバージョン管理

### エンタープライズ企業向け営業活動(2016年、約3ヶ月)
[プロジェクト概要]

- エンタープライズ企業向け営業OJT

[チーム規模、役割]

- 2名のチームで、営業担当として働いておりました。

[担当業務]

- 電力業界の企業様向けSaaS型勤怠管理システムの提案
- 電力業界の企業様向け基盤システムの運用保守契約更新
- 官公庁向けThinクライアント端末移行プロジェクトにおける大規模トラブルにおけるエンドユーザ対応
- 重要顧客への年末挨拶および準備
- その他事務処理

### 4次元可視化システムの開発および提案(2015年、約6ヶ月)
[プロジェクト概要]

- XYZ平面および時間軸でjsonデータを4次元可視化するシステムのプロトタイプを開発し、営業担当と同行し提案する。

[技術スタック]

- JavaScript/Three.js/HTML/CSS

[チーム規模、役割]

- 2名程度のチームで、フロントエンドエンジニアとして働いておりました。

[担当業務]

- 大手海外通信企業様向けにネットワークの帯域使用率を可視化する4次元可視化システムのプロトタイプ開発と提案を実施。
- 水道管理システム企業様向けに河川の水位を可視化する4次元可視化システムのプロトタイプ開発と提案を実施。

## 学生時代の研究
大学および大学院では自然言語処理と機械学習に関する研究をしておりました。
「人間の大脳皮質の情報処理原理を用いたテキストのカテゴリー分類」というテーマで国際学会に登壇して発表した経験があります。以下は論文のリンクになります。

https://www.researchgate.net/publication/268444818_Text_Classification_Using_Computational_Model_of_the_Cerebral_Cortex

## ポートフォリオ
### 家事管理ソフトウェア
Go/OpenAPI(Swagger)/Nginx/PostgreSQL/Docker/CircleCI/Gitなど

家事管理をするソフトウェアです。現状はバックエンドのみの実装となっています。UTも実装しております。

開発規模：
（HTMLはcoverage.htmlのものです。）

```sh
$  cloc ./ --exclude-dir=go-modules
     178 text files.
     174 unique files.
     294 files ignored.

github.com/AlDanial/cloc v 1.84  T=0.58 s (263.3 files/s, 24609.2 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Go                             137           1100           1243           6857
HTML                             1            605              0           3059
YAML                             3              3              4           1007
Markdown                         1             34              0            214
Dockerfile                       4             30             33             62
SQL                              3              4              0             45
make                             1              8              1             29
Bourne Shell                     4             12             23             20
-------------------------------------------------------------------------------
SUM:                           154           1796           1304          11293
-------------------------------------------------------------------------------
```

GitHub：
https://github.com/gold-kou/go-housework

### ジャニーズ顔判定ができるWebサービス
Python/Flask/HTML/CSS(BootStrap)/JavaScript/Nginx/AWS(EC2/Route53など)/GCP(GCS/GCV)/OpenCV/scikit-learn

ユーザ登録一切不要で、顔写真をアップロードするだけで、その顔がジャニーズ顔かどうかを判定できるWebサービスです。継続的にご利用いただいておりましたが、現在はインフラコストの都合上停止中です。ニュースサイトGigazineでも特集されました。

紹介記事：
[AIを使って自分の顔がジャニーズ系かどうかを判定するWebサービスを作ってみた](https://qiita.com/gold-kou/items/e1a96657a63b043c4564)

GitHub：
https://github.com/gold-kou/face-audition-johnnys

### スマートスピーカーを使った雨傘備忘通知サービス
Python/Node.js/Google Home

帰宅時刻の天気が悪天候であれば毎朝自動で傘を忘れないように音声通知してくれるサービスです。

紹介記事：
[「え！？朝は雨降ってなかったのに！傘持ってきてないよ〜。」を解決するGoogleHome連携アプリを作ってみた](https://qiita.com/gold-kou/items/887c79a58ad496e417d6)

GitHub：
https://github.com/gold-kou/never-forget-umbrella

## テクニカルスキル
### プログラミング言語
Go/Java(JavaEE)/Python(Flask)/Ruby/HTML/CSS/JavaScript

### API
OpenAPI(Swagger)/gRPC

### DB
PostgreSQL/MySQL/sqlite/Redis/DynamoDB

### Public Cloud
AWS(VPC/Route53/ELB/IAM/EC2/ECS/Fargate/Lambda/API Gateway/EBS/EFS/S3/RDS/DynamoDB/ElastiCache/SQS/CloudWatch/Auto Scaling)/GCP

### IaC
CloudFormation/Ansible

### サーバ仮想化・自動化
Docker/NFV/OpenStack/KVM/Vagrant/Virtualbox/Kickstart

### Workflow
Digdag

### ML
NLP/scikit-learn

### Document
JIRA/Confluence/Markdown

### 開発手法
Scrum/ウォーターフォール

## 言語
- 日本語
  - ネイティブ
- 英語
  - 流暢ではない（今後の学習意欲高いです、継続的に勉強しています）
  - TOEIC: 790点

## 資格
- 認定スクラムマスター
- 応用情報技術者
- TOEIC790

## 長所
私の最大の長所は、勉強熱心であることです。
自ら業務やキャリアに役立つ技術トピックを見つけ、学習計画を立てて、日々勉強しています。

学習例：

- 卒業後、累計30冊以上の技術書籍の学習
- 「家事管理ソフトウェア」、「ジャニーズ顔判定できるWebサービス」、「スマートスピーカーを使った備忘通知アプリ」の3つの自作ソフトウェア開発
- Qiitaへの記事投稿
- 毎日20分以上の英語リスニング・シャドーイング
- 英単語帳学習

勉強熱心であることは、変革の激しいIT業界において、常に成長し、活躍し続けられるために必要な能力だと考えています。
この長所を活かし、たとえ未経験の技術や分野であっても迅速にキャッチアップし、業務で貢献します。

### 長所のエビデンス①自作WebサービスがニュースサイトGigazineで特集された
機械学習の技術を活用して、アップロードした顔写真がジャニーズ系の顔かどうかを判定するWebサービスをリリースし、Gigazineなどの様々なニュースサイトに取り上げていただき、リリース1週間で2万リクエストを達成しました。

https://gigazine.net/news/20180808-johnnys-face/

### 長所のエビデンス②Qiitaで良質かつ大量のアウトプット
これまでにGoやPython、機械学習、Dockerなどの約50記事を投稿し、10000以上のContributionsを獲得しております。
[Qiita](https://qiita.com/gold-kou)

## 各種リンク

- [Qiita](https://qiita.com/gold-kou)
- [stack overflow](https://stackoverflow.com/users/9048198/gold-kou)
- [LinkedIn](https://www.linkedin.com/in/koki-hatano-258a42166/)
