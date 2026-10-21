# 安装拾序城市时钟

当前版本：**0.1.1**。基础功能永久免费，PRO 保存命名时区组合为一次性 **人民币 ¥12**，覆盖当前0.1.x已列高级权益。

[下载交付包](../downloads/shuffle-world-clocks-0.1.1-customer.zip)：`shuffle-world-clocks-0.1.1-customer.zip`。本页没有设置付款链接；购买 PRO 或咨询售后请联系 [shufflemonkey@163.com](mailto:shufflemonkey@163.com)。

## Edge 开发模式安装

1. 完整解压交付 ZIP，保留解压后的目录。
2. 在 Edge 打开 `edge://extensions`，开启“开发人员模式”。
3. 点击“加载解压缩的扩展”，选择包内 `edge/world-clocks/` 目录；该目录中直接包含 `manifest.json`。
4. 不要选择整个 ZIP、解压根目录或 `edge/` 父目录。安装后保留原目录，移动或删除会影响加载。
5. 从浏览器扩展菜单点击“拾序城市时钟”图标打开工具，可按需要将图标固定到工具栏。

这是保留解压目录的开发模式安装，不是 Edge 商店批准或上架证明。

## Firefox 临时开发加载

Firefox 版本已提交 AMO 审核，当前未保证批准或正式商店分发。交付包内 `firefox/world-clocks/` 是**未签名开发文件，不是已签名 XPI**。

1. 解压后在 Firefox 打开 `about:debugging#/runtime/this-firefox`。
2. 点击“临时载入附加组件”，选择 `firefox/world-clocks/manifest.json`。
3. 从扩展菜单点击工具图标。

重启 Firefox 后临时安装会移除。常规永久安装应等到已签名版本或正式 AMO 安装入口确认后使用；不需要为本工具关闭签名检查。

## 使用与 PRO

- 默认显示上海、伦敦和纽约时间；可添加 IANA 时区，最多12个。
- “UTC基准时刻”留空时显示当前时间；填入时按 UTC 换算。
- PRO 可保存最多10个命名时区组合。没有授权也能使用全部基础时间与偏移功能。
- 取得本产品授权后，打开“授权与升级”，粘贴授权码并点“验证并激活”。其他产品的码不能通用。

许可供购买者本人单设备使用，不做硬件或安装标识强绑定；允许重安装和迁移，迁移前移除旧安装的授权。完整范围见[使用许可](../LICENSE.txt)。

依赖本机时间与浏览器时区数据库。夏令时提示为季节偏移线索，不提供网络校时或权威历史时区服务。当前仅面向桌面版，未承诺 Android 或私密窗口支持。

[隐私说明](../privacy/world-clocks.md) · [返回产品页](../README.md)

购买、售后与功能开发定制：[shufflemonkey@163.com](mailto:shufflemonkey@163.com)。
