<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Lemmy

[![集成程度](https://apps.yunohost.org/badge/integration/lemmy)](https://ci-apps.yunohost.org/ci/apps/lemmy/)
![工作状态](https://apps.yunohost.org/badge/state/lemmy)
![维护状态](https://apps.yunohost.org/badge/maintained/lemmy)

[![使用 YunoHost 安装 Lemmy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lemmy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Lemmy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Lemmy is similar to sites like Reddit, Lobste.rs, or Hacker News: you subscribe to forums you're interested in, post links and discussions, then vote, and comment on them. Behind the scenes, it is very different; anyone can easily run a server, and all these servers are federated (think email), and connected to the same universe, called the Fediverse.


**分发版本：** 0.19.8~ynh1

**演示：** <https://lemmy.ml/>

## 截图

![Lemmy 的截图](./doc/screenshots/screenshot1.webp)

## 文档与资源

- 官方应用网站： <https://join-lemmy.org/>
- 官方管理文档： <https://join-lemmy.org/docs/en/>
- 上游应用代码库： <https://github.com/LemmyNet/lemmy>
- YunoHost 商店： <https://apps.yunohost.org/app/lemmy>
- 报告 bug： <https://github.com/YunoHost-Apps/lemmy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
或
sudo yunohost app upgrade lemmy -u https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
