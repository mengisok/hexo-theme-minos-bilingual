## 说明

### 原主题  
[minos](https://github.com/ppoffice/hexo-theme-minos)  

### 修改后  

在右上角增加语言选择菜单（中英）。为了适配手机端，使下拉栏可以完全显示，**强烈建议保留导航栏的搜索和GitHub链接图标**  

效果见[Meng's Blog](https://mengisok.github.io/)

## 设置步骤  

1. 将hexo根目录配置文件_config.yml修改为

```
language: 
 - en
 - zh-cn

url: https://mengisok.github.io/(你的blog地址)

permalink: :title/ 
```

2. 在/source文件夹中，新建一个zh-cn文件夹，然后把除了_posts文件夹和zh-cn文件夹自身以外的其它所有文件夹复制到zh-cn文件夹中  

3. 在/source/_posts文件夹中，新建一个zh-cn文件夹，将/source/_posts文件夹中的所有.md文件复制到zh-cn文件夹中。注意，**_posts和zh-cn中的.md文件名称要对应相同，都使用英文名称**。中文标题显示可以在title里改  

## 参考  

https://blog.learn-or-die.com/zh-tw/buildABilingualBlog/  

https://dengcb.com/zh/hexo-minos-multi-language/
