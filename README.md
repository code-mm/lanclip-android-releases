# LanClip Android

LanClip 的公开 APK 下载与自动更新仓库。这里仅保存安装包、版本信息与校验文件，应用源码保持私有。

## 下载

请前往 [Releases](https://github.com/code-mm/lanclip-android-releases/releases) 下载最新 APK。最低 Android 8.0。预览版使用调试签名。

从 1.0.0 或需要 Token 的 1.1.0 升级时，先下载免配置新版并覆盖安装一次。新版启动后自动检查这里的版本，无需 GitHub 登录或 Token；下载安装仍需用户确认和 Android 系统授权。

## 使用

连接与 LanClip 服务相同的 Wi-Fi 或以太网，打开应用，选择发现的服务并输入服务本身的访问密码。应用复用服务网页，支持图文与文件共享。GitHub 更新与局域网服务密码互相独立。

## 更新资产

每个可更新版本包含 APK、对应 `.sha256` 校验文件和 `update.json`。清单的包名、versionCode、versionName、minSdk 和 SHA256 来自实际 APK。应用只提示更高 versionCode，下载后检查完整性、包信息和同签名。没有互联网时，局域网共享功能仍可使用。

这里只公开正常安装包和更新信息，不保存 Token、签名私钥、源码归档或开发日志。
