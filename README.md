# RとRStudioのインストールガイド

## 目次
1. [はじめに](#はじめに)
2. [Rのインストール](#rのインストール)
   - [Windows](#windows用rのインストール)
   - [macOS](#macos用rのインストール)
   - [Linux](#linux用rのインストール)
3. [RStudioのインストール](#rstudioのインストール)
   - [Windows](#windows用rstudioのインストール)
   - [macOS](#macos用rstudioのインストール)
   - [Linux](#linux用rstudioのインストール)
4. [インストール後の設定](#インストール後の設定)
5. [トラブルシューティング](#トラブルシューティング)

## はじめに

RはオープンソースのTの統計解析環境です。RStudioは、Rを使いやすくするための統合開発環境（IDE）です。このガイドでは、RとRStudioを各オペレーティングシステムにインストールする方法を説明します。

## Rのインストール

### Windows用Rのインストール

1. [R公式ウェブサイト](https://cran.r-project.org/bin/windows/base/)にアクセスします。
2. "Download R-x.x.x for Windows" (xはバージョン番号) をクリックしてインストーラーをダウンロードします。
3. ダウンロードしたインストーラーを実行します。
4. インストールウィザードの指示に従ってインストールを進めます。デフォルト設定でも問題ありません。

### macOS用Rのインストール

1. [R公式ウェブサイト](https://cran.r-project.org/bin/macosx/)にアクセスします。
2. "R-x.x.x.pkg" (xはバージョン番号) をクリックしてインストーラーをダウンロードします。
3. ダウンロードしたパッケージをダブルクリックしてインストールを開始します。
4. 画面の指示に従ってインストールを進めます。

### Linux用Rのインストール

Ubuntu/Debianの場合:

```bash
sudo apt update
sudo apt install r-base
```

Fedora/CentOS/RHELの場合:

```bash
sudo dnf install R
```

## RStudioのインストール

### Windows用RStudioのインストール

1. [RStudio公式ウェブサイト](https://www.rstudio.com/products/rstudio/download/#download)にアクセスします。
2. "RStudio Desktop" の無料バージョンの "Download" ボタンをクリックします。
3. ダウンロードしたインストーラーを実行します。
4. インストールウィザードの指示に従ってインストールを進めます。

### macOS用RStudioのインストール

1. [RStudio公式ウェブサイト](https://www.rstudio.com/products/rstudio/download/#download)にアクセスします。
2. "RStudio Desktop" の無料バージョンの "Download" ボタンをクリックします。
3. ダウンロードしたDMGファイルを開き、RStudioアプリケーションをApplicationsフォルダにドラッグ＆ドロップします。

### Linux用RStudioのインストール

1. [RStudio公式ウェブサイト](https://www.rstudio.com/products/rstudio/download/#download)から、お使いのLinuxディストリビューションに合ったパッケージをダウンロードします。
2. ダウンロードしたパッケージをインストールします。

Ubuntu/Debianの場合:
```bash
sudo apt install ./rstudio-x.x.x-amd64.deb
```

Fedora/CentOS/RHELの場合:
```bash
sudo rpm -i rstudio-x.x.x-x86_64.rpm
```

## インストール後の設定

1. RStudioを起動します。
2. メニューバーから "Tools" > "Global Options" を選択します。
3. 必要に応じて設定を調整します（例：テーマ、フォント、ペイン・レイアウトなど）。

## トラブルシューティング

1. **Rが見つからない場合**: RStudioがRのインストールを自動的に検出できない場合は、"Tools" > "Global Options" > "General" で、Rのインストールパスを手動で指定してください。

2. **パッケージのインストールエラー**: 管理者権限で実行するか、個人用ライブラリを設定してください。

3. **グラフィックデバイスのエラー**: 適切なグラフィックドライバがインストールされていることを確認してください。

インストールや使用中に問題が発生した場合は、[R公式サポートフォーラム](https://community.rstudio.com/)や[Stack Overflow](https://stackoverflow.com/questions/tagged/r)で質問することをお勧めします。

---

このガイドは随時更新されます。質問や改善点がある場合は、Issueを作成してください。
