# 阅万物 OmniView · 安卓更新发布

这里用于分发「阅万物 OmniView」安卓正式 APK 和版本更新清单，源码继续保存在独立的私有仓库。

- [正式版本安装包 Releases](https://github.com/jiej05/OmniView-Android-Updates/releases)
- [更新清单 update.json](https://raw.githubusercontent.com/jiej05/OmniView-Android-Updates/main/update.json)（首次正式发布后才存在）

## 发布状态

正式签名版 v1.4.0 **尚未发布**。首次发布需要在私有源码仓库的 GitHub Actions Secrets 中设置 `OMNIVIEW_KEYSTORE_B64`、`OMNIVIEW_KEYSTORE_PASSWORD` 和 `OMNIVIEW_UPDATES_TOKEN`，然后在 Actions 手动运行工作流并勾选 `publish_release`。

本仓库只应存放公众可以获取的 APK、校验信息和版本说明。请不要提交任何签名密钥、密码或 Token。

> 安装时安卓系统会进行安装包签名检查。已安装的 Debug 版与正式签名版可能无法直接覆盖安装，需要先备份数据再切换。
