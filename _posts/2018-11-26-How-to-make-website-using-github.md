---
layout:    post
title:     githubを用いたウェブサイトの作り方
author:    zEttOn86
tags:      post notes github
subtitle:  github.ioを用いて，ウェブサイトを作る
category:  learning notes
---

## 始め方

#### 1. [jekyll-now](https://github.com/barryclark/jekyll-now)をクローンする

#### 2. クローンしたリポジトリ名を `YourGithubUserName.github.io` に変更する

  例えば，githubアカウントが `HOGE` の場合，以下のようになる．

  {% highlight %}
  # 変更前
  HOGE/jekyll-now

  # 変更後
  HOGE/HOGE.github.io
  {% endhighlight %}

  https://HOGE.github.io にアクセスすると，ホームページができている

#### 3. 好きなレイアウトを探す

  [Jekyll Themes](http://jekyllthemes.org/) or [jekyllthemes](https://jekyllthemes.io/) より好きなレイアウトを探す

  数式がtexで書けること，タグ付けができるものに限定した

  このテーマは[これ](http://jekyllthemes.org/themes/project-pages/)

  ダウンロードして，ローカルの `github.io` のディレクトリにコピペした

  正直，[オリジナルのリポジトリ](https://github.com/projectpages/project-pages)からフォークして，リポジトリ名を変更した方が楽な気がする

#### 4. `_config.yml` `画像` `projects` などを編集する

  コピペでは不必要なものが存在したので，以下のものを削除

  {% highlight %}
  CNAME
  404.md
  members.html
  mentions.html
  style.scss
  _sass/
  images/
  {% endhighlight %}

#### 5. 完成



### 参考文献

- [Jekyll + GitHub Pages でブログをつくってみた](https://aloerina01.github.io/blog/2016-10-02-2)

- [GitHub で Blog を作る](https://nkon.github.io/Github-pages-and-jekyll-blog/)
