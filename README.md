# note

middlemanでブログを書くためのテスト

# セットアップメモ

```
cloneなど

  % git clone git@github.com:tnobuhito/note.git
  % cd note
  % bundle install

記事のgenerate

  % middleman article post

適当に編集

  % vi source/2020-07-21-post.html.markdown

サーバ起動

  % middleman server

ブラウザでアクセス

  http://localhost:4567/

ビルド

  % bundle exec middleman build

Github Pagesにデプロイ

  % bundle exec middleman deploy

ブラウザでGithub Pagesにアクセス

  https://tnobuhito.github.io/note/
```

