# v2ray_json_generator

 v2ray_json_generator 的web app，可以迅速生成服务端和客户端的配置文件。特点就是一个html文件就搞定，比x-ui轻量很多，适合高级玩法，不受x-ui拘束
 
 使用 tailwind + vue2 技术。
 
 本app优点：1.完全本地；2： 在右侧输入信息后，左侧json框同步更新，适合学习json配置
 
 目前还包含 tailwind和 vue2的 js文件；如果想要单html文件也不难，把链接换成cdn的链接即可，缺点就是加载慢一点，因为并不是完全本地文件了。
 
 
 ![p1](p1.jpg)
 ![p1](p2.jpg)
 ![p1](p3.jpg)

## 与 x-ui等面板的对比

x-ui确实挺方便，但是我是一个高级玩家，我不想让它来替我安装 xray/v2ray等，我要自己安排安装位置、服务配置；
我还要用nginx前置，这些 x-ui都比较难办，不够灵活；

x-ui生成的json文件根本不会给你看，你始终不了解v2ray配置的json文件如何书写，这对于学习的进步是一个阻碍；

本app 一步一步带你编写正确的json文件，不怕漏标点符号，不怕写错。

还有就是，x-ui必须一致开着，留了一个网页后门，容易被攻击，不够隐蔽；

## 交流
交流电报群： https://t.me/shadowrocket_unofficial
