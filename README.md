[English](README_en.md)

# WindowsMailAndCalendarRepacked

## 简介

**Windows 邮件和日历** 重打包版客户端，修改了版本号与签名，不会自动更新。

-  只对原版软件进行了简单地重新打包及修改版本号与签名以避免自动更新，未修改或增加除版本号之外的任何程序代码，请放心使用

> [!IMPORTANT]
> 所有内容资源 _(包括但不限于应用、音频、图片等)_ 版权归 Microsoft 所有。  
> 本软件仅学习交流使用，请勿用于用于商业用途。如有侵权，请发 Issue 提出。  
> 使用此应用即代表您同意 [Microsoft 软件许可条款](https://go.microsoft.com/fwlink/?LinkID=524989)及 [Microsoft 隐私政策](https://go.microsoft.com/fwlink/?LinkID=521839)。

## 下载

点击下载：[16005.14326.21464.0](Release/windows-mail-and-calendar-repacked-16005-14326-21464-0.appxbundle)

## 安装

由于 Windows 只允许安装来自**微软商店**或者**企业开发者**的 appx/msix 软件包，所以我们需要先安装**自签名证书**来伪装成企业开发者，才能安装第三方软件包。

1. 下载 [证书文件](Release/windows-mail-and-calendar-repacked.cer)，然后直接打开。
2. 点击 `安装证书`，将会进入"证书导入向导"
3. "存储位置"选 `本地计算机`，下一步（需要同意管理员权限请求）
4. 选择 `将所有的证书都放入下列存储`，点击 `浏览`，选择 `受信任的根证书颁发机构`，确定，下一步，继续完成证书导入。
5. 下载 `appxbundle` 软件包，双击打开安装。

> [!NOTE]
> 某些杀毒软件可能会将证书安装工具误报为病毒，  
> 您可能需要暂时关闭杀毒软件或者添加白名单才能使用。  
> *本项目及配套工具不包含任何病毒及恶意操作，欢迎找茬。*

## 已知问题及解决方法

#### 安装时appx时提示“无法安装相关项”

通常情况下，Windows 的“应用安装程序”会自动下载并补全缺失的依赖软件包。但在少数系统环境中，亦或与微软服务器的网络连接不太顺畅时，安装时还是会提示“无法安装相关项”。请参阅此问题的[详细解决方法](Dependencies.md)

## 特别鸣谢

#### [Windows 邮件和日历](https://apps.microsoft.com/detail/9WZDNCRFHVQM) & [Microsoft Developers](https://developer.microsoft.com/zh-cn)

毫无疑问地得排在第一位。

#### [exp-3/CloudMusic.UWP-Repacked](https://github.com/exp-3/CloudMusic.UWP-Repacked)

为本项目提供了 README 的大部分内容，以及部分常见问题的解决方法。

#### [Microsoft Developers](https://developer.microsoft.com/zh-cn/) & [Appx_Re-Sign](https://github.com/Empyreal96/Appx_Re-Sign)

提供了编辑 Appx 所需的工具和参考资料。

#### [GitHub Copilot](https://github.com/features/copilot)

将中文文本翻译成英文。