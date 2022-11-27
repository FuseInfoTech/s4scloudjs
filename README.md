# S4S Cloud
This repository contains public S4S Cloud JavaScript libraries.

You will need an S4S Cloud service to connect to.
https://fuseit.com/products/s4s-cloud-connector/

## s4scloud.min.js
This is the main client library. To include on your website:
```
<script>(function(s4s,c,l,o,u,d){l[c]=l[c]||{};d=document.createElement('script');d.onload=function(){l[c].init(o,u);};d.src=s4s;document.head.appendChild(d);})('https://cdn.jsdelivr.net/gh/FuseInfoTech/s4scloudjs@0.1.0.22332/s4scloud.min.js', 'S4SCloud', window, '<service_url>', '<shared_key>');</script>
```