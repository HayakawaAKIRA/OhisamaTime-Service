# お日さま時間アプリのサービスサイト
Github pagesを利用しています。



## テーマ

Jekyllを利用しています。

導入手順はGithubの公式ガイダンスどおりに実施しています。
https://docs.github.com/ja/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll



## ローカル実行

Githubの公式ガイダンス通りの手順となります。

https://docs.github.com/ja/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll



``` shell
bundle install // webrickのエラーが発生する場合は、bundle add webrickを実行してください。

bundle exec jekyll serve
```



## Github Pagesへの反映

masterブランチにプッシュが実行された時点で自動で反映処理が実行されます。



## 定期的な更新

定期的な更新を実行してください。

``` shell
bundle update github-pages
```

