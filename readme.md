## element(matrix)

matrix web client

- https://github.com/vector-im/element-web

### element + cloudflare

config.json : https://github.com/vector-im/element-web/blob/develop/docs/config.md

dist : https://github.com/vector-im/element-web/releases

まずdistファイルをdownloadします。downloadしたファイルを展開し、`config.json`を置きます。

cloudflare pagesにてrepositorieを連携し、public-root, branchを設定します。

commitすれば自動でcloudflare pagesにdeployされます。

- https://developers.cloudflare.com/pages

### element + gh-pages

```sh
$ git checkout -b gh-pages

cname : element, archlinuxjp.github.io.
```

- https://docs.github.com/ja/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
