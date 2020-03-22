@[TOC](【前端技术】在github创建个人主页或技术博客)
闲在家里，打算出一个前端系列的技术博客，讲一下自己学习网站搭建、HTML、CSS、Javascript、Django等的学习经历。
对于新手来说，在github搭建免费的个人主页，不失为一个很好的练手方法，以下将记录我在很久以前在github搭建个人博客的经历。
# 1、注册github账号
GitHub是一个面向开源及私有软件项目的托管平台，因为只支持git 作为唯一的版本库格式进行托管，故名GitHub。
Github官网：[https://github.com/](https://github.com/)
这里不过多描述如何注册github账号，但是建议注册账号的时候，账号名最好使用简单易记的英文小写字母，最好是自己的姓名拼音。
# 2、创建个人主页专属仓库
登录github，进入个人的Repositories，如下图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020031322343997.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70)点击绿色的[New]按钮，新建一个Repositories，需要注意的是，这个仓库有固定的命名格式```username.github.io```，这里**username就是你注册的github账号名**，例如我的github账号是scutcyr，那么我创建的个人主页专属仓库名就是```scutcyr.github.io```。
【参考】我的个人主页专属仓库：[https://github.com/scutcyr/scutcyr.github.io](https://github.com/scutcyr/scutcyr.github.io)
# 3、了解主页框架css代码并下载
有很多关于在github搭建个人主页的博客，但是
大部分都是基于markdown的。本文主要是针对希望使用html、css、javascript学习搭建网站的同学。因此，为了让大家快速体验使用html、css、javascript搭建网站的乐趣，建议大家先直接利用现成的css文件和html模板，如下图所示，文件见链接: [https://github.com/scutcyr/build_your_homepage/tree/master/css](https://github.com/scutcyr/build_your_homepage/tree/master/css)。
你可以从这里快速下载：[https://github.com/scutcyr/build_your_homepage/archive/master.zip](https://github.com/scutcyr/build_your_homepage/archive/master.zip)，解压后，可以看到一个[css](https://github.com/scutcyr/build_your_homepage/tree/master/css)文件夹，以及一个[index.html](https://github.com/scutcyr/build_your_homepage/blob/master/index.html)模板。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200313230654425.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70)

# 3、修改index.html文件
这里假设你通过[https://github.com/scutcyr/build_your_homepage/archive/master.zip](https://github.com/scutcyr/build_your_homepage/archive/master.zip)下载了模板代码。解压后，如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200322165441159.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70#pic_center)解压后，是一个[build_your_homepage](https://github.com/scutcyr/build_your_homepage)文件夹，在里面，包含一个[css](https://github.com/scutcyr/build_your_homepage/tree/master/css)文件夹以及一个[index.html](https://github.com/scutcyr/build_your_homepage/blob/master/index.html)模板。    
你只需要使用[sublimetext](http://www.sublimetext.com/)或者[VSCode](https://code.visualstudio.com/)打开[index.html](https://github.com/scutcyr/build_your_homepage/blob/master/index.html)文件修改。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200322171300210.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70#pic_center)
# 4、把修改好的index.html文件连同css文件夹上传到你的```username.github.io```
登录github，进入你的```username.github.io```仓库根目录下，点击```Upload files```按钮，如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200322171715397.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70#pic_center)
适当缩小浏览器页面，然后把[css](https://github.com/scutcyr/build_your_homepage/tree/master/css)文件夹以及修改好的[index.html](https://github.com/scutcyr/build_your_homepage/blob/master/index.html)拖到上传页面，如下图所示
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200322172004303.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70#pic_center)上传文件完毕后，点击网页下方的绿色按钮```Commit changes```。

# 5、检验你的成果
打开链接https://username.github.io，查看你的主页是否成功显示！这里可能需要等一两分钟，或者适当刷新页面！
以下是我修改好的个人主页，详情：[http://yirongchen.com/](http://www.yirongchen.com/)
![在这里插入图片描述](https://img-blog.csdnimg.cn/202003221723232.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3MjAxMjQz,size_16,color_FFFFFF,t_70#pic_center)




【作者简介】[陈艺荣](http://yirongchen.com/)，男，目前在[华南理工大学电子与信息学院广东省人体数据科学工程技术研究中心](http://www.scut.edu.cn/ee/)攻读博士，担任IEEE Access、IEEE Photonics Journal的审稿人。两次获得美国大学生数学建模竞赛(MCM)一等奖，获得2017年全国大学生数学建模竞赛(广东赛区)一等奖、2018年广东省大学生电子设计竞赛一等奖等科技竞赛奖项，主持一项2017-2019年国家级大学生创新训练项目获得优秀结题，参与两项广东大学生科技创新培育专项资金、一项2018-2019年国家级大学生创新训练项目获得良好结题，发表SCI论文4篇，授权实用新型专利8项，受理发明专利13项。
[我的主页](http://yirongchen.com/)
[我的Github](https://github.com/scutcyr)   
[我的CSDN博客](https://blog.csdn.net/m0_37201243)    
[我的Linkedin](https://www.linkedin.com/in/chenyirong/) 

