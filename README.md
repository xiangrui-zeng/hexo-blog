#Hexo-Theme-Huxblog

###[Demo &rarr;](https://xiangrui-zeng.github.io)


![](http://huangxuan.me/img/blog-desktop.jpg)

## Usage

##### 1.Init

```
git clone https://github.com/xiangrui-zeng/hexo-blog.git
cd hexo-blog
npm install
```

##### 2.Modify
Modify `_config.yml` file with your own info.
Especially the section:

```
deploy:
  type: git
  repo: https://github.com/xiangrui-zeng/xiangrui-zeng.github.io.git
  branch: master
```
Replace with your own repo!

##### 3.Writting/Serve/Deploy

```
hexo new post IMAPOST
hexo serve // run hexo in local environment
hexo clean && hexo deploy // hexo will push the static files automatically into the specifig branch(gh-pages) of your repo!
```
