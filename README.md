# Welcome

## Catalogue

- [输入了url然后呢？](http://www.alenqi.site/2017/05/25/page-load/)
- [CORS 跨域资源共享](http://www.alenqi.site/2017/03/29/cors/)
- [Atom使用插件精选(FE)](http://www.alenqi.site/2017/03/11/atom-edit/)
- [Destructuring ES6](http://www.alenqi.site/2017/02/22/destructuring-es6/)
- [Array ES6](http://www.alenqi.site/2017/02/22/array-es6/)
- [Promise ES6](http://www.alenqi.site/2017/01/17/promise-es6/)
- [Git Command Summary](http://www.alenqi.site/2016/06/13/git-command/)
- [gulp自动化构建html静态资源路径版本号添加和替换](gulp自动化构建html静态资源路径版本号添加和替换)
- [IT 2048](http://www.alenqi.site/2016/02/04/IT2048/)

## About

- [about](http://www.alenqi.site/about/)

## Usage

I didn't publish it as a single theme folder because a few of the pages are added and modified manually, so you should manually create some extra folders in `source` for the new pages and modify the `_config.yml` if you only have the single theme folder.

So i just pushed the whole hexo project for your convenience, all pre settings and boilerplates are included, have a look and go ahead customizing your own blog!

#### 1.Init

```
git clone https://github.com/AlenQi/AlenQi.github.io.git
cd AlenQi.github.io
npm install
```

#### 2.Modify
Modify `_config.yml` file with your own info.
Especially the section:

```
deploy:
 type: git
 repo: https://github.com/AlenQi/AlenQi.github.io.git
 branch: master
```
Replace with your own repo!

#### 3.Writting/Serve/Deploy

```
hexo new post IMAPOST
hexo serve // run hexo in local environment
hexo clean && hexo deploy // hexo will push the static files automatically into the specific branch(gh-pages) of your repo!
```
