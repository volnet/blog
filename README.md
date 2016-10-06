# Volnet Blog

#### [View Live Volnet Blog &rarr;](http://volnet.github.io/)

#### [View Live Hux Blog &rarr;](http://huangxuan.me)

This is created from the boilerplate [Hux Blog](https://github.com/Huxpro/huxpro.github.io)

如何运行这个blog？
---------------

1. 下载源代码（内容）

```
git clone https://github.com/volnet/volnet-jekyll.git
```

复制到`/home/parallels/jekyll/volnet-jekyll/`路径下。

2. 运行Jekyll

这里使用Docker来运行。Dockerfile见源文件夹。

```
docker run -it -p 4000:4000 -v /home/parallels/jekyll/volnet-jekyll/:/srv/jekyll volnet/myblog_jekyll
```
