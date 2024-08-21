---
title: 
date: <% tp.date.now("YYYY-MM-DDTHH:mm:ssZ") %>
description: 
category: 
tags: 
images: 
imageAlt: 
imageCap: 
draft: true
---
<% await tp.file.move("/content/english/post/newthing") %>
<% await tp.file.rename(tp.date.now("YYMMDD-")) %>
