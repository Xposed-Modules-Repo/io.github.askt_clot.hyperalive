# HyperAlive

HyperAlive 是一个面向小米 HyperOS 4 的 LSPosed 模块，将魅族 Alive 壁纸的息屏、锁屏和桌面三态转场移植到小米设备。
[项目源码](https://github.com/Askt-clot/HyperAlive)

## 功能

- 提供启航、留光、星月、轻启、山脉、银河六种照片息屏样式，可拖动预览或通过水平、垂直滑块调整位置。
- 内置 36 款动态壁纸。使用照片壁纸时，锁屏和桌面可以分别选择图片和纹理。
- 支持魅族风格的息屏和锁屏时钟，可调整样式、字重、大小和颜色，也可显示农历和电量。

## 安装与使用

已在小米 17 Pro Max 上实测，其他机型和系统版本待验证。APK 的最低安装要求为 Android 10（API 29），系统联动需要 LSPosed。

1. 下载安装 HyperAlive，在 LSPosed 管理器中启用模块并设置下方推荐作用域。
2. 打开 HyperAlive，选择照片或动态壁纸，再按应用内提示设置壁纸。
3. 使用「备份并应用」或恢复原壁纸时，请授予 HyperAlive Root 权限。

### 推荐作用域

- 系统框架 (`android`)
- System UI (`com.android.systemui`)
- System UI 插件 (`miui.systemui.plugin`)
- 息屏与锁屏 (`com.miui.aod`)
- 主题壁纸 (`com.android.thememanager`)

从旧包名 `com.hyperalive.aod` 或 `com.qihang.aod` 迁移时，请先在 LSPosed 中停用旧模块，再启用新模块并重新设置作用域。旧应用的私有设置需要在新应用中重新配置。

## 源码与致谢

源码、更新日志和问题反馈见项目仓库。HyperAlive 的原创代码采用 MIT 许可，随项目分发的第三方素材按各自条款处理。[源码](https://github.com/Askt-clot/HyperAlive) · [版本下载](https://github.com/Askt-clot/HyperAlive/releases) · [问题反馈](https://github.com/Askt-clot/HyperAlive/issues) · [资产与许可说明](https://github.com/Askt-clot/HyperAlive/blob/main/THIRD_PARTY_NOTICES.md)

感谢 OpenAlive 作者 **下北沢最速傳說** 和项目贡献者。HyperAlive 移植了部分 OpenAlive 代码，并参考了其照片息屏样式、三态转场和壁纸纹理的实现。[OpenAlive](https://github.com/Maga-King/OpenAlive)
