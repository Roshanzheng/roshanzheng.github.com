---
layout: post
title: "PPTP VPN is Down"
description: ""
category: 
tags: [pptp, vpn, openvpn, linode]
---
{% include JB/setup %}

PPTP Linode 部署成功  

但是只能访问baidu，weibo.com等国内可以访问的网站。  

连whatismyip.com这样的网站都在获得响应之后莫名地没有了速度。技术拦截的迹象很明显。  

我百思不得其解。后来查了一些文章才知道，可能是中国的防火墙屏蔽了相关端口1723的通信。  


刚刚接触这些技术，不知道我的理解是不是正确。  

如果是真的，那么购买海外vps的同学不要再在pptp上浪费时间了。直接open吧。  