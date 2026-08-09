摩根地址客服【Q-——333307——】摩根地址客服【 辋芷《888yx●vip》 】
摩根地址客服【Q-——333307——】摩根地址客服【 辋芷《888yx●vip》 】

 手把手教你用Github Pages搭建个人博客：从零到部署全攻略

> 还在羡慕技术大牛拥有自己的独立博客？其实用Github免费托管就能轻松实现。本文手把手教你完整搭建流程，告别繁琐服务器配置。

你是否厌倦了在CSDN、掘金上发文章却难以积累个人品牌？Github Pages不仅完全免费，还能绑定自定义域名，最重要的是——所有代码都托管在Github上，天然适合程序员使用。今天我们就用最简洁的方式，带你完成从仓库创建到文章发布的完整闭环。

 第一步：创建博客专属仓库
登录Github后点击绿色“New repository”按钮，仓库名必须严格命名为 `你的用户名.github.io`（例如`zhangsan.github.io`）。选择Public公开模式，勾选“Add a README file”初始化仓库。

 第二步：选择博客框架（重点）
推荐两个主流方案：
1. Jekyll：Github原生支持，无需本地环境，修改即生效
2. Hexo：需本地安装Node.js，但主题丰富、生成速度快

对于新手，我们直接使用Jekyll的官方主题库，在仓库的Settings→Pages中点击“Change theme”即可一键应用。

 第三步：发布你的第一篇文章
在仓库根目录创建`_posts`文件夹，新建`2025-01-01-welcome.md`文件，文件名格式必须为“年-月-日-标题”。在文件头部添加YAML信息：
```
---
layout: post
title: "你好，Github"
---
```
保存后访问你的专属域名，第一篇博客就上线了！

 必踩的坑与解决方案
- 语法高亮失效：在`_config.yml`中添加`highlighter: rouge`
- 图片路径错误：使用`![描述]({{ site.baseurl }}/assets/图片名)`
- 本地预览失败：安装Ruby后运行`bundle exec jekyll serve`

现在，你的博客已经成功联网！如果觉得这篇文章有帮助，欢迎点赞收藏，也欢迎在评论区分享你的搭建体验，遇到问题我会逐一回复。点击关注，后续将带来“Github个人主页美化技巧”“Hexo主题深度定制”等进阶教程。

相关推荐：

https://github.com/riveraevan7367/kwrlsf/blob/main/2027%E7%A7%91%E6%8A%80%E6%B1%87%E6%80%BB%EF%BC%9A%E6%91%A9%E6%A0%B9%E5%A8%B1%E4%B9%90%E7%BD%91%E5%9D%80_%E5%BF%97%E7%8B%99%E4%BB%84%E6%80%A5%E6%BC%B3cjwpc.md

<img src="https://i.postimg.cc/wxDGmGpn/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(92).png" />

相关推荐：

https://github.com/riveraevan7367/kwrlsf/commit/6ad79ba61078010f7c2a951c322626fe8b5b1181

<img src="https://i.postimg.cc/g2g50LWJ/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(89).png" />
相关推荐：

https://github.com/rollinssteven632/yfikrm/blob/main/2027%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E6%91%A9%E6%A0%B9%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95_%E7%BD%95%E5%A1%98%E5%8E%8D%E8%9A%8A%E4%BB%84edppv.md

<img src="https://i.postimg.cc/5tGRBcjL/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(9).png" />
相关推荐：

https://github.com/rollinssteven632/yfikrm/commit/1a843d7616605b17c626c9adba76f46293962f47

<img src="https://i.postimg.cc/ncZwYGVR/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(94).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
