# HeCaiYun

和彩云自动打卡签到

搬运自[xuthus5/HeCaiYun](https://github.com/xuthus5/HeCaiYun)，改为github action版本

需要自行在`.github/workflows/main.yml`添加定时任务

## Secret

**`Settings`->`Secrets`->`New repository secret`，添加以下Secret：**
- `COOKIE`：抓包Cookie
- `REFERER`：抓包referer
- `PUSHPLUS_TOKEN`：PushPlus Token
- `LUCK_DRAW`：是否开启自动幸运抽奖. `true`:开启; 不填/其他:不开启. (首次免费, 第二次5积分/次) 不建议开启 否则会导致多次执行时消耗积分
