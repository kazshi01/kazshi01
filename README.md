<!-- 1. GitHub usernameを変更 -->
<div align="right">
  <img src="https://komarev.com/ghpvc/?username=username" />
</div>


<!-- 2. プロフィールや連絡先を変更 -->
# <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> Profile

- 🏫 立教大学 理学部 化学科卒
- 🌱 エンジニア歴3年弱（`2022/11 - 2025/9`）
- 🌈 `SRE`・`DevOps`・`DataOps`を中心に、クラウドインフラ領域を専門としています
<br>

<!-- 3. 好きな技術スタックに変更 -->
<!-- ライトモート：theme=light, ダークモート：theme=dark -->
<!-- アイコンの選択肢一覧：https://arc.net/l/quote/zizyykfh -->
# ⭐️ Skills
<img alt="my skills" src="https://skillicons.dev/icons?theme=dark&perline=7&i=aws,gcp,terraform,k8s,go,ts," />

# 🏆 Certifications

 
```
AWS認定資格: SAP, DOP, SCS, MLS, SAA, DEA, CLF (7資格)

その他: LPIC1
```

# 💼 Experience & Expertise

 
```
得意分野: AWS, GCP,  SRE, DevOps

得意技術: ECS, EKS, Terraform, CI/CD

得意業務: インフラのコード化、自動化、業務改善、アジャイル開発
```
<br> 

# 📊 Projects

※ 直近 4 つの💫案件は同じ会社内での SRE 支援案件で、一部並行して参画中

<br>

## 💫 大手メーカーのデータ分析基盤構築支援 (2025/7 - 2025/9 : 3ヶ月) : DataOps

`課題`: Terraform module の再利用性が低く、新規環境構築時の効率的な展開ができない
     
`チーム`: 6人

`インブラ`: BigQuery, Dataform, Cloud Composer, Terraform, SQL, Looker Studio, Vertex AI, PagerDuty

`開発`: Python

`業務`: クライアントとの要件調整、データ基盤改善、AWS 設計レビュー

#### `成果`

データ基盤の Terraform module の改修により、汎用的に使用できるように改善

AWS アーキテクチャに関する知見をメンバーと共有し、設計レビューの品質向上を支援


<br>

## 💫 データ連携システムのインフラ運用・監視・保守 (2025/4 - 2025/9 : 6ヶ月) : SRE

`課題`: 定期的なアップデート作業が後回しになり、最新バージョンへの追従ができていない
     
`チーム`: 3人

`インフラ`: GKE, Cloud SQL, Helmfile, Terraform, Datadog, Cloud Logging, GitHub Actions

`開発`: Go

`業務`: GKE・Cloud SQL アップグレード対応、その他基盤改善・保守

#### `成果`

helm コマンドを使用した diff & deploy workflow の作成

renovate による日々のアップデートにより常に最新バージョンでの運用を実現

Argo Workflows のスケジュールエラーを検知するアラートの実装方法の検討と導入

<br>

## 💫 FinTech 企業での SRE 支援 (2025/4 - 2025/6 : 3ヶ月) : SRE

`課題`: 大量の誤検知アラートにより、本来対応すべきアラートが埋もれ、適切な監視・対応ができていない
     
`チーム`: 6人

`インフラ`: EKS, Control Tower, Terraform, Datadog, Argo CD, GitHub Actions

`業務`: k8s 周りの環境整備、監視周りの整備

#### `成果` 

誤検知アラートの解消、必須アラートの追加

散在していた環境の統合・整備を実施

属人化タスクの標準化・チーム全体への知識共有を推進

<br>

## 💫 大手 Sler POC 環境のマルチアカウント化の導入支援 (2024/11 - 2025/3 : 5ヶ月) : SRE

`課題`: マルチアカウント化の推進における障壁の解消、開発とインフラチーム間の連携不足
     
`チーム`: 3人

`インフラ`: EKS, API Gateway, Lambda, Cognito, Control Tower, Terraform, GitLab CI, SAM

`開発`: Vue.js, Java

`業務`: マルチアカウント運用とサーバレスアーキテクチャ構築

#### `成果`

開発チームと連携し、インフラの構築やアプリのデバッグを支援

リリースを効率化するため、CICD パイプラインの構築を実施

PMO の技術理解度に合わせた説明資料の作成

技術的な課題を業務影響の観点で整理し、非技術者にも理解しやすい形で報告

<br>

--------------------------------------------------------------------

<br>

## ✰ 大手 EC サイトのクラウド移行推進業務 (2024/1 - 2024/10 : 10ヶ月) : CCoE ※ フリーに転向

`課題`: 100 以上のオンプレミス環境の AWS 移行促進

`チーム`: 8人

`インフラ`: ECS, Control Tower, Transit Gateway, Terraform, New Relic, Backlog, GitHub Actions

`開発`: React, Go

`業務`: マルチアカウントの運用管理・改善、New Relic 導入ガイドライン策定、クラウド移行設計レビュー

#### `成果`

NAT Gateway から 集約 VPC Endpoint への切り替えによるコスト削減を実施

各メンバーの調査資料にタグ付けを行い、散在していた資料へのアクセス性を向上
      
タスク管理ボードの改善により、埋もれがちな簡易タスクの可視化と処理促進を図った

チーム全体でのプロジェクト優先度共有 MTG を実施し、並行作業数の最適化を推進

<br>
 
## ✰ 大手ゲーム会社の基幹システムサーバのリプレイス (2023/4 - 2023/12 : 9ヶ月) : DevOps

`課題`: レガシー社内システムサーバーの開発環境の整備、及びサーバーのリプレイス

`チーム`: 7人

`インフラ`: EKS, EC2, Helm, Jenkins, Terraform, Jira, Confluence

`開発`: Java, Maven, Junit

`業務`: EC2 から EKS へのサーバー移行、E2E テスト設計構築、CICD パイプライン改善

#### `成果` 

複数サーバー移行の共通フローをドキュメント化し、メンバーの作業効率化を支援

個別設定より一括設定が効率的な箇所を特定し、チーム全体での実施を提案・推進

積極的な質問・相談により他メンバーの発言を促し、チーム内コミュニケーションの活性化を実現

<br>
 
## ✰ 国家公務員向け保険基幹オンプレシステムのクラウド移行検討 (2022/11 - 2023/3 : 6ヶ月 )

`課題`: ガバメントクラウドに則したクラウド移行の実現可能調査

`チーム`: 6人

`インフラ`: ECS, EC2, Systems Manager

`業務`: ガバメントクラウド要件に基づく移行提案

#### `成果`

サブリーダーとして、タスクの切り出しや進捗管理を担当

オンプレミス構成の知見不足を補うため、担当者との MTG 設定により知識共有を促進
