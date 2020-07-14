# Hexo Default Theme

## 我的 [博客](https://shenxianpeng.github.io/) 代码使用的 [Hexo](https://hexo.io)

使用 Hexo 默认主题已经三年了，中间修复了很多不尽如人意的地方。如果你也喜欢这个默认主题，分享给你。

## 安装

```bash
# 下载代码，并将其命名为 blog
git clone https://github.com/shenxianpeng/hexo-theme-default.git blog 
cd blog

npm install                                 # 安装依赖
npm install -g hexo-cli                     # 安装 hexo 命令行
npm install hexo-deployer-git --save        # 安装 hexo 部署功能
```

## 常用命令

```bash
hexo server                                 # 启动本地服务，默认地址是 http://localhost:4000/
hexo new "My New Post"                      # 生成一个新的文章
hexo new page "About"                       # 生命一个新的 tab 页面叫 About
hexo clean                                  # 清理本地的缓存文件，包括 db.json 和生成的静态网页
hexo generate                               # 生成静态网页
hexo deploy                                 # 将生成的网页部署到 GitHub pages 上面

# 命名组合使用
hexo generate -deploy                       # 生成静态页面并部署
hexo g -d                                   # 以上命令的缩写
```

