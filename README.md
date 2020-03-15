<p align="center">
<a href="https://github.com/jsuse/travis-draw"><img alt="Build Status" src="https://travis-ci.com/jsuse/travis-draw.svg?branch=master" /></a>
</p>

# 这是什么？
青岛流量挂机抽奖的另一种实现方式，源码来自[利用宝塔面板搭建【青岛流量抽奖网站】](https://onstart.top/%E5%BB%BA%E7%AB%99/41.html)，这里只是使用了TravisCI来触发其核心代码`run.php`。

# 如何食用？
Fork本项目，并在你的Travis项目上设置变量和定时,注意，需注册[百度文字识别应用](https://cloud.baidu.com/product/ocr)。

![](https://arn0-1251735137.cos.ap-guangzhou.myqcloud.com/static_files/HexoSakura.webp)
> 图片来自[利用宝塔面板搭建【青岛流量抽奖网站】](https://onstart.top/%E5%BB%BA%E7%AB%99/41.html)

## 设置变量
`PHONE_NUM`: 你的联通手机号码
`API_KEY`: 百度文字识别API KEY
`SEC_KEY`: 百度文字识别Secret Key

## 设置定时`Cron Jobs`
分支`BRANCH`: `master`

间隔`INTERVAL`: `Daily `

选项`option`: `Do not run if there has been a build in the last 24h`

## 最后,执行部署

Enjoy~

<hr>

# 致谢：

[利用宝塔面板搭建【青岛流量抽奖网站】](https://onstart.top/%E5%BB%BA%E7%AB%99/41.html)

# License

MIT
