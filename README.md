# rails-to-vuejs

## 環境構築

### #rubyのインストール

### #bundlerのインストール
1. gemからbundlerのインストールする
    ```sh
    gem install bundler
    ```
1. Gemfileの作成
    ```sh
    bundle init
    ```
1. GemfileにインストールするGemを入力
    ```sh
    gem "rails"
    ```
### #Ruby On Rails の環境構築
1. railsのインストール
    ```sh
    # pathを指定してインストール。下記は「vendor/bundler」の場合
    bundle install --path vendor/bundler
    ```
1. rails app の作成
    ```sh
    bundle exec rails new .
    ```
1. railsが動作するかを確認
    ```sh
    bundle exec rails s
    ```