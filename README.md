# AmetrineVault — サポートサイト / Support site

[AmetrineVault](https://maya27aokisawada.github.io/AmetrineVault-publish/) の公開情報（使用要件・利用規約・プライバシーポリシー）と、不具合の報告・要望の窓口です。アプリのソースコードはここにはありません。

Public information for [AmetrineVault](https://maya27aokisawada.github.io/AmetrineVault-publish/en/) (system requirements, EULA, privacy policy) and the place to report bugs and request features. The app's source code is not in this repository.

| | 日本語 | English |
|---|---|---|
| 使用要件 / Requirements | [requirements](https://maya27aokisawada.github.io/AmetrineVault-publish/requirements/) | [requirements](https://maya27aokisawada.github.io/AmetrineVault-publish/en/requirements/) |
| 利用規約 / EULA | [eula](https://maya27aokisawada.github.io/AmetrineVault-publish/eula/) | [eula](https://maya27aokisawada.github.io/AmetrineVault-publish/en/eula/) |
| プライバシー / Privacy | [privacy](https://maya27aokisawada.github.io/AmetrineVault-publish/privacy/) | [privacy](https://maya27aokisawada.github.io/AmetrineVault-publish/en/privacy/) |
| サポート / Support | [support](https://maya27aokisawada.github.io/AmetrineVault-publish/support/) | [support](https://maya27aokisawada.github.io/AmetrineVault-publish/en/support/) |

## 不具合・要望 / Bugs and requests

[Issues](https://github.com/maya27AokiSawada/AmetrineVault-publish/issues/new/choose) からテンプレートを選んでください。Issue は公開されるので、個人情報・サーバーの情報・ノートの内容は書かないでください。

Choose a template from [Issues](https://github.com/maya27AokiSawada/AmetrineVault-publish/issues/new/choose). Issues are public, so do not include personal information, server details or note content.

## サイトの更新（管理者向け）

Jekyll で、`main` ブランチの直下を GitHub Pages が公開する。文書に差し込む値（提供者名・問い合わせ先・施行日）は `_config.yml` にまとめてある。

- 内容はアプリの実装に合わせて書いている（送る情報: Firebase のメール・ライセンス、Sentry の伏字にしたクラッシュレポート / オフラインの猶予 30 日 / 対応 OS）。アプリ側を変えたら文書も直す。
- ローカルで確認: `bundle install` → `bundle exec jekyll serve --baseurl ""`
