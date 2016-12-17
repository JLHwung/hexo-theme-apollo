![hexo-theme-apollo](https://cloud.githubusercontent.com/assets/9530963/13026956/08e76eca-d277-11e5-8bfc-2e80cea20a0d.png)

A fork of original [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo) with opinionated changes:
- formularised color system
- high-standard a11y support
- better developer experience


## 文档

- [中文文档](https://github.com/JLHwung/hexo-theme-apollo/blob/master/doc%2Fdoc-zh.md)
- [Document](https://github.com/JLHwung/hexo-theme-apollo/blob/master/doc%2Fdoc-en.md)

## 安装

[![asciicast](https://asciinema.org/a/bsvksjw0h0gro2l34z8pxpihk.png)](https://asciinema.org/a/bsvksjw0h0gro2l34z8pxpihk)

``` bash
hexo init Blog --no-install
cd Blog 
yarn
yarn add hexo-renderer-{jade,sass} hexo-generator-{archive,feed,sitemap} hexo-browsersync
git clone https://github.com/JLHwung/hexo-theme-apollo.git themes/apollo
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `apollo`:

```yaml
theme: apollo

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
cd themes/apollo 
git pull
```

## License

MIT
