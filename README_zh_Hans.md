<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 FacePrivacy

[![集成程度](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![工作状态](https://apps.yunohost.org/badge/state/faceprivacy)
![维护状态](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![使用 YunoHost 安装 FacePrivacy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 FacePrivacy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**分发版本：** 2025.03.13~ynh1

**演示：** <https://faceprivacy.forge.apps.education.fr/app/>

## 截图

![FacePrivacy 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://faceprivacy.forge.apps.education.fr/app/>
- 上游应用代码库： <https://forge.apps.education.fr/faceprivacy/app>
- YunoHost 商店： <https://apps.yunohost.org/app/faceprivacy>
- 报告 bug： <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
或
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
