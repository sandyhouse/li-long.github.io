---
layout: post
category: "Reading"
title: "使用GitHub和Jekyll搭建个人博客"
tags: ["Jekyll"]
---
<h3>1.简介</h3>
<p>
之前一直用新浪博客或者CSDN博客等作为自己的个人博客。然而，这些博客无法随心所欲的
自定制博客的内容，而只能利用系统提供的模板进行博客的创作。为了自定制博客，需要购买
或者寻找一个免费的空间，存放自己的代码，包括html,css等。作为一个屌丝程序员，自然是
不会选择使用收费空间了，毕竟仅仅为了创建一个个人博客而购买一个空间还是有些“费用高昂”的。
然而，现在可用的免费空间越来越少，至少笔者没有找到比较好用的免费空间，如果哪位亲有好
的免费空间推荐，请给笔者留言，供大家分享。
</p>
<p>
幸运地是，github为我们提供了构建免费博客的空间，虽然空间大小有限制（几百M），但是对于
我们搭建个人博客，完全足够了。本文，笔者将向大家讲述如何利用github提供的空间搭建免费的
个人博客。
</p>
<H3>2.什么是GitHub和Jekyll</h3>
<p>
<a href="https://github.com">GitHub</a>是一个代码托管工具，并利用Git管理代码版本。GitHub提供了一种功能，叫做
GitHub Pages，利用这个功能，我们可以为项目建立网站。同样的，GitHub提供了为个人或者组织建立博客的GitHub.io, 与GitHub
Pages不同，GitHub.io要求用户创建的项目名称必须与用户的注册名一致，即username.github.io。
</p>
<p>
Jekyll是一个简单的，针对博客设计的静态网站生成器。使用 GitHub 和 Jekyll，我们可以打造自己的独立博客，
你可以自由地定制网站的风格，并且这 一切都是免费的。
</p>
<p>
本博客即建立在GitHub之上，读者可以对此有大概的了解。同时，本博客提供github源代码，有兴趣的读者可以复制代码，
并对代码进行简单的修改，即可拥有自己的博客。
</p>
<p>
<a href="https://pages.github.com/">GitHub Pages</a>的主页提供了一个简单的入门指引，阅读并操作一下，会有一个直观简单的认识。
</p>
<h4>建立用户或者组织的网站</h4>
<ol>
<li>登陆GitHub并建立一个名为username.github.io的资源库，username是你的github用户名或者组织名</li>
<li>将资源库克隆到本地（参考git使用手册）</li>
<li>进入工程文件夹，并建立名为index.html的文件夹，并在里面加入"Hello World"语句</li>
<li>增加、提交并上传工程</li>
<li>至此，你已经拥有了一个简单的博客，登陆http://username.github.io，你可以看到你的博客了。当然，初次使用可能需要十几分钟
才能看到效果哦</li>
</ol>
<h4>建立项目主页</h4>
