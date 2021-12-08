# 环境搭建
## nodejs

## npm

## 获取源码
```
git clone $http_url
```

## 安装依赖
```
npm install
```

## 安装主题
```
git clone https://github.com/HCLonely/hexo-theme-webstack themes/webstack
```

## 本地预览
```
hexo g
hexo server
```

## 修改目录
`/source/_data/webstack.yml`内修改menu即可，
具体请查看[webstack说明](https://github.com/HCLonely/hexo-theme-webstack)

## 新增文章和url
具体请查看[webstack说明](https://github.com/HCLonely/hexo-theme-webstack)
### 新增aboutpage
```
hexo new page about
```
###
Edit `source/about/index.md` and add `type:'about'`

### 写文章请参考
1. [](https://hexo.io/zh-cn/docs/writing)


## 发布
### 安装依赖
```
npm install hexo-deployer-git --save
```

```
hexo g -d
```


# 参考文献
1. [hexo史上最全搭建教程](https://blog.csdn.net/sinat_37781304/article/details/82729029/)
2. [hexo-theme-webstack](https://github.com/HCLonely/hexo-theme-webstack)
3. [hexo文档](https://hexo.io/zh-cn/docs/themes.html)
4. [font-awesome](http://code.zoomla.cn/boot/font.html)

# todo
1. [add i18n](https://github.com/hexojs/hexo-i18n)
2. [add label](https://hexo.io/zh-cn/docs/tag-plugins)