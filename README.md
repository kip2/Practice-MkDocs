# Practice-MkDocs
Mkdocs Practice Repository

# Try Access!

https://kip2.github.io/Practice-MkDocs/

---

# 使い方

## インストール

MkDocsをローカル環境にインストールする

```shell
pip install mkdocs
```

## 新しいプロジェクトの作成

次のコマンドで新しいプロジェクトを作成する

```shell
mkdocs new [project-name]
```

## ローカル環境で試す

以下のコマンドでサーバーを立てる

```shell
mkdocs serve
```

ブラウザで下記のアドレスにアクセスする

http://localhost:8000

## ビルド

以下のコマンドでビルドすることで、staticなサイトを立ち上げられる

```shell
mkdocs build
```

## カスタマイズ

テーマのインストールを行う

以下では一例としてmaterialテーマのインストールを行なっている

```shell
pip install mkdocs-material
```

mkdocs.ymlにテーマを設定

```yml
theme:
    name: 'material'
```

## デプロイ

Github Pagesなどにデプロイする

以下では一例としてGithub Pagesへのデプロイ方法について記述している

### 設定の方法

mkdocs.ymlに以下の設定を追加

```yml
site_name: [サイト名]
repo_url: [GitHubのリポジトリのURL]
```

### Githubへのデプロイ

```shell
mkdocs gh-deploy
```

### アクセス

URLは以下のものになる

https://[user-name].github.io/[repository-name]



