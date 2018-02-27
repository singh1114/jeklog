---
author: Ranvir Singh
comments: true
date: 2018-02-26 18:28:54.213846
layout: post
title: Static sites versus complicated database sites
slug: static-sites-versus-complicated-database-sites
---
We are back again after some suspension caused by a severe&nbsp;error in the backend of our web app. A lot of stuff is built in the time we were down. All of that is in the testing&nbsp;environment and is being tested. Soon we are going to launch the stuff in the production itself. This includes allowing the static site, GitHub page's blogger to attach a custom domain name to your GitHub pages blog and fetching of old blogs into the JekLog web app. The suspension in the JeKLog services was caused due to some error in the apache configuration. Even before some error occurred and halted the services of GitHub static site provider-JekLog, I convinced myself that I will not use Apache and move toward more recent [Nginx](http://blog.ranvirsingh.me/how-to-install-nginx-in-ubuntu/). After a lot of effort, I was able to move all of the stuff from the old server to the new one.

<img alt="GitHub pages blog" src="https://i.imgur.com/Ay7WoeR.jpg" style="height:576px; width:960px"/>

According to me running our services on Nginx rather than Apache is a big and positive news for the future of this product. We are constantly trying to build new and cool stuff. At the same time, you guys can always request for new things from our side. We will work as hard as we can to make it work and create the things that you want us to create. In this post, we are going to discuss the differences between the&nbsp;complicated database based blogs and the static site generators that we are trying to build at JekLog. JekLog allows you to log in using the GitHub account and within few steps, it helps you to create a blog of your own.&nbsp;

[In my last post,](http://blog.jeklog.com/how-to-create-a-free-blog-using-github-pages-and-jekyll-with-jeklog/)&nbsp;I discussed various things that are important in creating a good blog. If you really want that your views should reach the audience without any distraction, you should always be using some static site generator. Jekyll and Hugo are the two most famous of all static site generators. Along with the content, you also need some domain name. Here at JekLog, we help you to host the files on GitHub itself, so that, you don't have to worry about the domain name. If you have some other domain name you can always add that to your blog. The service that you want to use is known as CNAME. We have written the code but it is in the test environment.

We don't have to deny the fact that from last few decades WordPress has been used everywhere. Even today, people have a strict demand to create a WordPress blog. They completely deny the fact that all they want to provide is the content. Nothing less nothing more.&nbsp; In last few decades, People have been trying to complicate the situation by creating a lot of CPU intensive website using PHP. Database intensive tasks used to make the user experience worse. A good example of this system was the earlier version of the Facebook web app.&nbsp;

>  
> __With static site generators, you can always move from bad user experience to Ultimate user experience.&nbsp;__
> 

&nbsp;The problem with these complex websites is that it brings a lot of headaches with it. With database website, you always have a chance of someone snicking into your website and taking away all of your data. Also, that amount of complexities makes it hard to load the website. We at [JekLog](http://jeklog.com)&nbsp;are trying to solve this problem by allowing you to create the blog in no more than few seconds. You don't need to have any programming experience for creating your blog.

If you came this far reading this post, you can always turn to the other side and start creating your first static site blog. [Read this blog post for the help.](http://blog.jeklog.com/how-to-create-a-free-blog-using-github-pages-and-jekyll-with-jeklog/)&nbsp;I would be grateful if you can share this post with your friends. ok