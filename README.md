# IBM-flowerss-bot


Key | Value | Type | Required
-- | -- | -- | --
IBM_MAIL | IBM Cloud 的登录邮箱 | Secrets | Yes
IBM_PWD | IBM Cloud 的登录密码 | Secrets | Yes
IBM_APP_NAME | CF 容器名（自己取一个） | Secrets | Yes
FRSS_CONFIG | 配置文件内容 [参考](https://flowerss-bot.now.sh/#/install?id=%e9%85%8d%e7%bd%ae) （IBM 容器每次重启会重置，所以不建议使用 sqlite 来作为数据库。需要另外自建 mysql 并文件夹中配置）| Secrets | Yes
