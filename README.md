# Shelves ~ 本棚共有SNS ~

ポートフォリオとして作成したWebサービスのローカル開発用リポジトリ

Webサービスの公開URLは[こちら](http://http://34.80.186.97/)

## 主に使っている技術
- Django
- Vue.js
- Docker
- CircleCI
- Spinnaker
- GCP

## 実装した主な機能
- ユーザーのCRUD(djangoのdefaultパッケージであるAbstractBaseUserを使用)
- 投稿のCRUD(djangoのdefaultパッケージであるgenericを使用)
- GoogleBooksAPIを用いた書籍情報の取得（axiosでAPIから情報を取得）
- おすすめユーザー推薦機能（ピアソン相関係数を用いた簡単なユーザー推薦）

## テストユーザー
以下のユーザーネームとパスワードでテストユーザーとしてログインすることができます。

username: toby  
passward: testuser