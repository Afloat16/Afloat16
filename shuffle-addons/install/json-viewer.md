# 安装拾序JSON树

当前版本：**0.1.1**。基础功能永久免费，PRO 导出格式化 JSON 为一次性 **人民币 ¥18**，覆盖当前0.1.x已列高级权益。

[下载交付包](../downloads/shuffle-json-viewer-0.1.1-customer.zip)：`shuffle-json-viewer-0.1.1-customer.zip`。本页没有设置付款链接；购买 PRO 或咨询售后请联系 [shufflemonkey@163.com](mailto:shufflemonkey@163.com)。

## Edge 开发模式安装

1. 完整解压交付 ZIP，保留解压后的目录。
2. 在 Edge 打开 `edge://extensions`，开启“开发人员模式”。
3. 点击“加载解压缩的扩展”，选择包内 `edge/json-viewer/` 目录；该目录中直接包含 `manifest.json`。
4. 不要选择整个 ZIP、解压根目录或 `edge/` 父目录。安装后不要移动或删除加载目录。
5. 从浏览器扩展菜单点击“拾序JSON树”图标打开工具。

这是保留解压目录的开发模式安装，不是 Edge 商店批准或上架证明。

## Firefox 临时开发加载

Firefox 版本已提交 AMO 审核，当前未保证批准或正式商店分发。交付包内 `firefox/json-viewer/` 是**未签名开发文件，不是已签名 XPI**。

1. 解压后在 Firefox 打开 `about:debugging#/runtime/this-firefox`。
2. 点击“临时载入附加组件”，选择 `firefox/json-viewer/manifest.json`。
3. 从扩展菜单点击工具图标。

重启 Firefox 后临时安装会移除。常规永久安装应等到已签名版本或正式 AMO 安装入口确认后使用；不需要为本工具关闭签名检查。

## 使用与网页权限

在工具页输入 JSON 或导入不超过1 MiB的 UTF-8 JSON 文件，然后校验、折叠查看或格式化预览。大数字保留原始数字文本，重复键保留并提示；无效输入会显示错误，不执行 JavaScript。

若要读取网页：先在普通 HTTP(S) 目标网页点击本扩展图标，再点“读取目标页文本”。`activeTab`、`scripting` 仅用于这项主动操作；不会自动扫描或接管全部网页。浏览器内部页、商店页等受保护页面可能禁止读取，可改用本地文件或粘贴文本。

PRO 仅将当前格式化结果导出为文件；没有授权也能使用全部基础校验和预览。取得本产品授权后，打开“授权与升级”，粘贴授权码并点“验证并激活”。其他产品的码不能通用。

许可供购买者本人单设备使用，不做硬件或安装标识强绑定；允许重安装和迁移，迁移前移除旧安装的授权。见[使用许可](../LICENSE.txt)。导出文件由你保管和删除。当前仅面向桌面版，未承诺 Android 或私密窗口支持。

[隐私说明](../privacy/json-viewer.md) · [返回产品页](../README.md)

购买、售后与功能开发定制：[shufflemonkey@163.com](mailto:shufflemonkey@163.com)。
