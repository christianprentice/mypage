---
title: "プリンティス 太朗 — インフラエンジニア"
---

# プリンティス 太朗
**インフラエンジニア — Linux / Ansible / Kubernetes** · 福岡

## 職務要約
オンプレミス仮想化基盤（VMware vSphere / RHEL）の運用保守に従事する
インフラエンジニアです。資料の乏しい環境でも既存システムを自律的に解析し、
スクリプトや IaC で定常作業を自動化してきました。前職では自作 GAS ツールで
1 日約 1 時間の工数削減を実現。個人環境では Ansible によるプロビジョニング、
GitOps による構成管理、systemd を活用した運用自動化を実践しています。

## 職務経歴

### ALH株式会社 — インフラエンジニア（2026年4月〜現在）
電力系・仮想化基盤（物理約15台 / 仮想約400台）の運用保守。
- vSphere / RHEL / Solaris / Windows 環境の運用保守。
- 引き継ぎ資料がほぼない中で、ミドルウェアのメジャーアップデート
  （ESET 等）に伴う影響調査を自走して完遂。
- ログ蓄積基盤の設計支援：rsyslog の MariaDB 出力設定（ストレージ容量設計
  を含む）および DB 設計。
- 定例データ更新作業を PowerShell スクリプトで自動化。
- dnf 自動アップデートや systemd タイマーを活用した運用自動化を立案。

### アデコ株式会社 — メンバー（2022年2月〜2025年11月）
- **LLM 安全性評価**：リリース前モデルおよびデプロイ済み AI サービスの
  安全性・応答精度テスト、エスカレーション内容のフィードバック。
- **業務自動化**：GAS で入力テンプレート化・送信履歴記録スクリプトを自主開発し、
  1 日約 1 時間の工数削減を達成。
- **コンテンツ審査・市場調査**：動画コンテンツの審査（SLA 保持）、
  英語でのトレンド調査報告書を作成し海外顧客へ提出。

### 株式会社フィールズジャパン — プログラマー（2020年6月〜9月）
WordPress / Linux による EC サイト保守運用。運用マニュアルが存在しなかったため、
プラグイン・更新手順書を新規作成し、引き継ぎ時間を約 8 時間から約 1 時間に短縮。

### その他
小売店舗運営、製造ライン等。詳細はお問い合わせください。

## 個人開発

### [workstation-bootstrap-ansible](https://codeberg.org/christianprentice/workstation-bootstrap-ansible)
最小構成の RHEL 系 Linux から個人ワークステーションを立ち上げる Ansible
ロール集。システムパッケージ、Rust / Go ツールチェイン、chezmoi 管理の
dotfiles、ファームウェア更新＋リブートまでを冪等・タグ分割実行で自動化。
実務でも追求している「手作業ゼロ」の思想そのままのプロジェクトです。

その他の実験（自作 Fedora イメージ、KVM スナップショット管理、Zig / Rust）は
[Codeberg プロフィール](https://codeberg.org/christianprentice/)をご覧ください。

## 資格
CKAD · KCNA · KCSA · LFCS · LFCA · RHCSA · Red Hat OpenShift ×2 ·
Red Hat Cloud-native Developer · AWS Cloud Practitioner · AWS AI Practitioner ·
Terraform Associate (004) · Git SC102 · 実用英語技能検定 準1級

資格の詳細：[Credly](https://www.credly.com/users/christiantaroprentice/badges/credly)

## 言語・リンク
- 日本語（母語） · 英語（ビジネス — フリーランス翻訳者として約4年の実務経験）
- コード： [Codeberg](https://codeberg.org/christianprentice/)
- 資格： [Credly](https://www.credly.com/users/christiantaroprentice/badges/credly)
