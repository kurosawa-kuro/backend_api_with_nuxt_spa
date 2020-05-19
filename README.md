# backend_api_with_nuxt_spa

```
docker-compose up web mysql mysql-gui

cd frontend
npm run dev
```

localhost:3000


memo
```
rails apiモードでapiサーバー(localhost:3000)を作成

npx create-nuxt-app frontendでnuxtプロジェクトをrailsプロジェクト内に作成(別リポジトリで管理予定)
設定はJavascript、Npm、Axios、SPA

frontend/package.jsonを"dev": "HOST=0.0.0.0 PORT=3333 nuxt",に変更してフロントエンドのポートを変更

frontend/nuxt.config.jsを
generate: {
    dir: '../public'
  }
と追記して静的ファイルの出力先を変更する

npm run generateでrailsのpublicに生成

@nuxtjs/proxy - npmをフロントにインストール



npm run generate
```