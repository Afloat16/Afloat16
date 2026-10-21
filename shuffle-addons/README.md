# 拾序浏览器工具

由 [Afloat16](https://github.com/Afloat16) 独立开发的三款本地浏览器工具。基础功能永久免费，PRO 高级功能按产品分别授权，不需要原厂软件账号或云端语言服务。

| 产品 | 免费基础功能 | 当前 0.1.x PRO 权益 | 一次性价格 | 安装与隐私 |
| --- | --- | --- | --- | --- |
| 拾序城市时钟 · Shuffle World Clocks | 城市时间、指定 UTC 时刻换算、UTC 偏移对比 | 保存命名时区组合，最多10组 | 人民币 ¥12 | [安装](install/world-clocks.md) · [隐私](privacy/world-clocks.md) |
| 拾序JSON树 · Shuffle JSON Tree | 本地校验、可折叠结构、无损数字格式化预览、本地文件导入和主动读取目标页文本 | 导出格式化 JSON 文件 | 人民币 ¥18 | [安装](install/json-viewer.md) · [隐私](privacy/json-viewer.md) |
| 拾序文字检查 · Shuffle Text Check | 固定本地规则、逐项查看与手动应用建议 | 导出检查报告 | 人民币 ¥18 | [安装](install/text-checker.md) · [隐私](privacy/text-checker.md) |

高级权益为一次性购买当前 **0.1.x** 已列功能，供购买者本人在单台设备上使用。它不是订阅，不承诺终身升级、未来新增功能或云服务。三个产品的授权码不能混用。详细范围见 [使用许可](LICENSE.txt)。

## 获取与发布状态

截至2026年10月22日，三款 Firefox 扩展已提交 Mozilla Add-ons（AMO）审核；提交不等于审核批准、公开上架或取得签名。正式商店安装链接将在确认后补充。当前也不宣称已在 Edge 加载项商店上架。

目前交付包版本为 **0.1.1**。每个包只包含对应产品的 Edge 与 Firefox 文件及说明：

- [下载城市时钟](downloads/shuffle-world-clocks-0.1.1-customer.zip) · `shuffle-world-clocks-0.1.1-customer.zip`
- [下载JSON树](downloads/shuffle-json-viewer-0.1.1-customer.zip) · `shuffle-json-viewer-0.1.1-customer.zip`
- [下载文字检查](downloads/shuffle-text-checker-0.1.1-customer.zip) · `shuffle-text-checker-0.1.1-customer.zip`

本页没有设置付款链接。购买 PRO 或咨询售后，请联系 [shufflemonkey@163.com](mailto:shufflemonkey@163.com)。包内没有内置付款或自动订单发码功能，请勿把免费安装包当作已完成购买的凭证。

Edge 包可通过开发人员模式加载解压目录并保留安装；保留原解压目录，不要移动或删除。Firefox 包内文件目前**未签名，只能临时开发加载**，重启浏览器后临时安装会移除；它不是可永久安装的已签名 XPI。具体步骤见各产品安装说明。

## 本地处理与使用边界

三款工具没有运营者遥测、广告、云同步或自动网络上传。授权签名在本地验证。你主动打开 GitHub、发送邮件或另行购买时，相应客户端或网站按其规则处理这些请求；扩展不会自动附加输入内容或授权码。

- 城市时钟依赖设备时钟与浏览器时区数据库；夏令时提示是季节偏移线索，不是权威历史校时服务。
- JSON 树保留大数字和重复键；不会执行输入，也不会自动接管全部 JSON 网页。
- 文字检查仅有少量固定规则，可能误报；不是 AI、完整拼写词典、通用语法或学术审校服务。

当前版本已在隔离的 Edge 155 与 Firefox 158.0.1 环境测试基础功能及已有 PRO 动作。声明最低桌面浏览器版本为140，不代表已覆盖每个较旧版本、所有网站或全部异常场景；本批不提供 Android 或私密窗口兼容承诺。

## 授权迁移与联系

零售授权按个人单设备使用约定发放，不做硬件或安装标识强绑定。可以重新安装或迁移；迁移到其他设备前，请移除旧安装的授权，确保只在一台设备上使用。不要把授权码公开、共享或转售。

功能开发定制、购买及售后：**[shufflemonkey@163.com](mailto:shufflemonkey@163.com)**。

发布者：[Afloat16](https://github.com/Afloat16)。本文档、图标与软件为独立制作，不表示原厂授权、背书或完整复刻。
