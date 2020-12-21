# lita-wiki

[![Build Status](https://travis-ci.org/risid/lita-wiki.png?branch=master)](https://travis-ci.org/risid/lita-wiki)
[![Coverage Status](https://coveralls.io/repos/risid/lita-wiki/badge.png)](https://coveralls.io/r/risid/lita-wiki)

该插件支持了所有有开放API的mediawiki系统，填写你需要的wiki地址，就可以让lita帮你搜索wiki！

## 安装

将lita-wiki加入到你Lita项目的Gemfile中

``` ruby
gem "lita-wiki"
```

## 配置
在你的lita_config.rb中添加你的wiki地址，比如`https://zh.wikipedia.org/`

``` ruby
  config.handlers.wiki.wiki_url = "https://zh.wikipedia.org/"
```

## Usage

``` ruby
> lita, wiki Ruby
```
