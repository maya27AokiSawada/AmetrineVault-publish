---
layout: default
lang: ja
title: 使用要件
description: AmetrineVault の動作環境と、同期機能を使うために必要なもの。
alt_lang: /en/requirements/
permalink: /requirements/
---

# 使用要件

<p class="meta">最終更新: {{ site.effective_date_ja }}</p>

## 対応 OS

| プラットフォーム | 要件 | 入手先 |
|---|---|---|
| Windows | Windows 10 / 11（64 ビット） | Microsoft Store |
| macOS | macOS 12 Monterey 以降（Apple シリコン・Intel） | Mac App Store |
| iPad | iPadOS 15 以降 | App Store |
| Android タブレット | Android 7.0 以降 | Google Play |
| Chromebook | Google Play ストアに対応した ChromeOS | Google Play |

- iPad・Android タブレットは**横向き**での利用を想定しています。3 つのペイン（ツリー・エディタ・アウトライン）を並べるため、スマートフォンの画面では十分に表示できない場合があります。
- Chromebook では、キーボードとマウス（タッチパッド）での操作に対応しています。タッチスクリーンは必須ではありません。

## 画面・言語

- 推奨する画面の幅: 1,280 ピクセル以上
- アプリの表示言語: 日本語

## ストレージ

- アプリ本体のほかに、編集する Markdown ファイル（Vault）と、検索用のインデックスを保存する空き容量が必要です。インデックスの大きさは、ノートの量に応じて増えます。
- Dropbox・SFTP と同期する場合は、同期するフォルダの内容を端末にも保存します（キャッシュ）。同期するフォルダと同じ程度の空き容量を用意してください。

## インターネット接続

次の場合だけインターネット接続が必要です。そのほかの機能（ノートの閲覧・編集・検索）はオフラインで使えます。

- アカウントへのログイン・新規登録・パスワードの再設定
- ライセンスの購入・確認（確認できた後は、オフラインでも最長 30 日間そのまま使えます）
- Dropbox・SFTP との同期
- クラッシュレポートの送信（設定でオフにできます）

## 有料機能（ライセンス版）を使う場合

Dropbox 連携・SFTP 連携は、ライセンス（買い切り）を購入すると使えます。購入とライセンスの確認には、{{ site.app_name }} のアカウント（メールアドレスとパスワード）が必要です。

### Dropbox 連携

- Dropbox のアカウント（無料プランでも可）
- 対応: Windows・macOS（iPad・Android は今後対応予定）

### SFTP 連携

- SSH（SFTP）で接続できるサーバーと、そのアカウント
- ログイン方式: パスワード、または秘密鍵（OpenSSH 形式・PEM 形式。パスフレーズ付きにも対応）
- 初めて接続するときは、サーバーのホストキーの指紋を確認します。サーバー管理者が示す指紋と照らし合わせてください。

## お問い合わせ

<a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>
