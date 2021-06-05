# github图床(利用picGo + github +  jsDelivr)

## 前言

**Q：为什么要使用图床呢？什么是图床？**

A：写博客文章时，图片的上传和存放是一个问题，有的朋友可能会把图片放到和博客同一个仓库当中，使用相对路径来引用，这样后期维护起来会比较麻烦。还有的朋友会在不同的平台发布同一篇文章，这样一来每个平台都要上传图片，为了解决这些问题，比较推荐的做法是把图片统一上传到一个在线的第三方静态资源库中，我们把这个资源库称为图床，其返回一个图片的URL，使用`markdown+图片url`的方式写作文章，一次编写，到处使用~

**Q：图床的选择**

A：推荐使用GitHub作为图床，特点是免费、稳定，有一个小缺点是国内访问速度慢，不过没关系，可以使用`jsDelivr`免费CDN加速。

**Q：jsDelivr是什么？**

A：`jsDelivr`是国外的一家优秀的公共 CDN 服务提供商，该平台是首个「打通中国大陆与海外的免费CDN服务」，无须担心中国防火墙问题而影响使用。官网：<http://www.jsdelivr.com/>

## 步骤

1. github创建存储图片资源的仓库image
2. vscode下载插件vs-picgo
3. 配置github

![20210606000138](https://cdn.jsdelivr.net/gh/wu529778790/image/blog/20210606000138.png)

4. 配置文档
 
 https://picgo.github.io/PicGo-Doc/zh/guide/config.html#github%E5%9B%BE%E5%BA%8A

![20210606000309](https://cdn.jsdelivr.net/gh/wu529778790/image/blog/20210606000309.png)
