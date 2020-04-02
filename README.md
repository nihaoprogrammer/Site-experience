---

# 个人博客已转到WordPress，个人网站：[www.deozhang.com](https://www.deozhang.com)欢迎访问！

---

>以下是我通过github pages和云服务器两种方式搭建个人博客的过程.
## Github pages搭建个人博客
### 步骤
* [用 GitHub Pages + Hexo 搭建个人专属博客](https://www.jianshu.com/p/6a69297d1b88)
* [Hexo-修改Hexo主题](https://www.jianshu.com/p/33bc0a0a6e90)
* [hexo博客添加评论神器---valine](https://blog.csdn.net/qq_40265501/article/details/80019508)
* [GitHub Pages自定义域名](https://www.jianshu.com/p/f5d6dc70f918)
* [hexo博客图片问题](https://www.jianshu.com/p/c2ba9533088a)
* 推荐用Atom进行Markdowm的编写(可以实时的看到效果)[Atom - 介绍和使用方法](http://www.hangge.com/blog/cache/detail_1149.html)

## 服务器搭建个人博客
> 如果和github建站有重合的部分，这里就不在赘述。
步骤:  
* 购买云服务器[阿里云服务器](https://account.aliyun.com/login/login.htm?spm=5176.8142029.388261.7.31646d3eMcyutE&qrCodeFirst=false&oauth_callback=https%3A%2F%2Fcn.aliyun.com%2F%3Futm_content%3Dse_798307%26gclid%3DCj0KCQiAkMDiBRDNARIsACKP1FFgxEBaBs7DR9hiaw3zSzzQFxHNtndMpti-iCdZ5sA3MZxpAYQUZmkaAnoGEALw_wcB)    
>推荐用阿里的云服务器(学生可以享受学生价)
* 购买域名[腾讯云注册域名](https://dnspod.cloud.tencent.com/?from=qcloudHpProductDns)  
>腾讯域名注册比较方便   
* [centos服务器部署hexo（简版）](https://blog.csdn.net/tian330726/article/details/80791388)     
```
1. pwd查看hexo的全路径（如： /usr/hexo/public）  
2. 修改Nginx配置文件时只需修改文中强调的部分  
3. server_name可以修改为localhost  
4. nginx卸载     yum remove nginx     
```
