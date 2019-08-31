---
date: 2019-07-23 18:26:40
layout: post
title: Birds can fly, but this you knew already
subtitle: Lorem ipsum dolor sit amet, consectetur adipisicing elit.
description: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559825145/theme16_o0seet.jpg
optimized_image: https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559825145/theme16_o0seet.jpg
category: work
tags:
  - work
  - tips
author: thiagorossener
---
昨晚自己捣腾了一下网站，结果把原来的网站源码给误删了，经过一天的时间，又恢复了，换了主题。可惜我的第一篇文章已经找不到了，怎么办？我想还是大致的重新写一下吧。

我想这次写详细一点，把我具体的步骤都写下来，如果你看完的话，你应该能自己建一个和我类似或者比我更好的一个网站。OK！闲话不多说。

首先大家都知道，需要域名、服务器和源码。域名申请可以有很多网站，就像上次我说的付费的你也可以考虑，根据后缀名的不同，价格不同，如果你想要稳定点或者选择更多一些的域名，我推荐namecheap这个网站，在上面可以购买.me .cc .com等等的后缀，当然都是一级域名了。如果你不想要付费的，我推荐freenom.com这个知名度很高的域名申请站了，这个站也可以申请一级域名，到期再续就可以了，国内可以上。

域名搞定后，下一步是服务器。服务器也有很多，国内的服务器依然是需要备案、审核、实名认证等等一大堆复杂的手续，还是要选择国外的，至少我是这么想的。推荐的网站是qvqyun.cn 和 infinityfree.net，这两个我都用过，第一个是很便宜的，第二个完全免费当然也可以升级付费用户，这个网站如果你没有域名的话，它会给你免费建个域名，那就是二级域名了，域名的托管什么的它都包了，哈哈，比较全面的一个，如果你不想要二级域名也可以填自己的一级域名。选择自己需要的服务器就好了。

服务器搞定了，下一步就是整合了，如果你会Linux系统的话自己可以编写网站代码，当然大部分人还是不会的，那么就考虑免费开源的网站代码吧。有zblog，WordPress等，我用的是WordPress，每个代码用的PHP版本都不同，你要注意一下。好，继续！ 域名是需要解析的，也就是说那些英文字母的网址是需要解析成ip地址，然后在根据ip再传输的，所以，你如果自己申请了一个一级域名的话，要在域名服务器那填好DNS指向，指向哪里呢？当然是指向你的服务器ip了，你申请好的服务器都有ip的，infinityfree这个网站特殊点，有域名服务器的地址，也就是说把你申请的域名服务器地址改成它给你的地址就行了。

解析好域名后，就要在服务器上部署网站代码，一般的服务器的FTP目录下都有个wwwroot目录，也就是/wwwroot 在这个目录下上传网站源码，不要在根目录下哦。源码在WordPress网站上直接可以下载，再用FTP上传工具上传，工具我用的是filezilla，连上FTP服务器上传就可以了。

传好后，在浏览器上输入你的网址，这时如果没有什么问题的话会出现安装数据库的提示窗口。下一步是安装数据库，在服务器上找到数据库管理，新建数据库，建好后会给你用户名密码，再到浏览器窗口，点击下一步填好数据库的名字，下一步就OK了。

都建好后，登录，这就是你的网址后台了，在这就可以写文章，发图片，改主题什么的就可以了。

补充完了，其实如果想更完善的话，还可以再加个SSL，有时间精力的话可以看看。就到这吧。








