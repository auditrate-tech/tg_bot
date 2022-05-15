# tg_bot

### Deploy

[![Deploy](https://camo.githubusercontent.com/6979881d5a96b7b18a057083bb8aeb87ba35fc279452e29034c1e1c49ade0636/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fauditrate-tech%2Ftg_bot_axs)

# 1 部署、启动

```shell
// 下载代码
git clone https://github.com/soroqer/tg_bot.git

// 进入根目录
cd tg_bot

// 编辑配置文件 
vim ./config/default.json

// 安装依赖
npm i

// 使用pm2启动
pm2 start index.js
```
