#Hexo Theme: glove

##glove
glove is a theme for hexo


[DEMO](http://gyyzyp.com)

##Prepare
```
npm install --save hexo-renderer-jade
npm install --save hexo-renderer-stylus
```
##Install

```
cd your-hexo-blog
git clone git@github.com:gaoyangxiaozhu/glove-theme.git themes/glove
```
##Enable
Modify your hexo _config.yml, set theme to glove

##Update
```
cd theme/glove
git pull
```
##Config
All config options can be found in themes/glove/_config.yml.

##Languages
Modify language option in hexo/_config.yml

- English: default
- 简体中文：zh-CN

>  ####Menu
```
menu:
  Home: /
  Archives: /archives
  About: /about
```

##Avatar

```
imglogo:
   enable: false             ## display image logo true/false.
   src:  ## `.svg` and `.png` are recommended,please put image into the theme folder `/glove/source/img`.
  favicon: img/myFavicon.ico   ## size:32px*32px,`.ico` is recommended,please put image into the theme folder `/glove/source/img`.
```
==Widgets

```
widgets:
- recentPosts
- category
- tag
- tagcloud
- archive
- links

##provide six widgets:
## recentPosts: recent file posts
## categories: all categories
## tag: all tags
## tagcloud: show all tags in special ways
## archieves: all your posts
## links: your friends links
```

##Info

```
github: ##eg: 'git_name' will be 'http://github.com/git_name'
weibo: ##eg: 'weibo_name' will be 'http://weibo.com/weibo_name'
facebook: ##eg: 'facebook_name' will be 'http://facebook.com/facebook_name'
```

##Comment
+ duoshuo

````
####duoshuo comments
duoshuo:
  enable: false  ## duoshuo.com
  short_name: ## duoshuo short name.
```

##Analytics
+ google
+ baidu

```
google_analytics:
  enable: false
  id:   ## e.g. UA-1766729-8 your google analytics ID.
  site: ## e.g. yangjian.me your google analytics site or set the value as auto.

baidu_analytics: false
```


##Share
+ jiathis

#### jiathis
jiathis:
  enable: false ## if you use jiathis as your share tool,the built-in share tool won't be display.

