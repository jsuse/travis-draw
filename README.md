# 这是什么？
青岛流量挂机抽奖的另一种实现方式，源码来自[利用宝塔面板搭建【青岛流量抽奖网站】](https://onstart.top/%E5%BB%BA%E7%AB%99/41.html)，这里只是使用了TravisCI来触发其核心代码'run.php'。

# 如何食用？
Fork本项目，并在你的Travis账户上设置变量和定时。

## 设置变量
`PHONE_NUM`: 你的联通手机号码

## 设置定时'Cron Jobs'
间隔`INTERVAL`: `Daily `

选项`option`: `Do not run if there has been a build in the last 24h`

致谢：

[利用宝塔面板搭建【青岛流量抽奖网站】](https://onstart.top/%E5%BB%BA%E7%AB%99/41.html)

License

MIT