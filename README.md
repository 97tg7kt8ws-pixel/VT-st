# 独立商品图工坊在线更新

此仓库用于发布独立商品图工坊 Windows x64 便携版更新。

## 当前版本

- 版本：2.0.2
- 软件包：`IndependentProductStudio_Windows_x64_v2.0.2.zip`
- SHA-256：`8bd1599c2a7e21e54f729304872f55380bb0a84a90f6e537cab5f8a6b5fdc8be`
- 安装方式：完整解压后双击 `IndependentProductStudio.exe`

## v2.0.2 更新内容

- 修复俯拍衣物错误站立：俯拍强制使用垂直 90° 相机，商品必须平铺并与台面真实接触。
- 强化重力、支撑、透视、阴影、反射和产品结构约束，减少悬空、穿插、融化、重复部件等 AI 痕迹。
- 保留商品颜色、印花、纹理、车线、标签、比例和必要支撑，避免为了换背景而改坏商品。
- 新增生成后物理真实性检查；发现严重问题会依据具体原因自动重新生成。
- 可设置物理质检重生次数，默认 2 次、最多 5 次；质检不可用时不会卡住整批任务。

## 软件内更新地址

```text
https://raw.githubusercontent.com/97tg7kt8ws-pixel/VT-st/main/version.json
```

软件会检查版本、下载 Release 中的 ZIP、验证文件大小与 SHA-256，然后自动替换并重启。更新失败时会恢复旧版本。

## 发布顺序

发布新版本时，先创建对应版本的 GitHub Release 并上传 ZIP，确认可以下载后，最后更新仓库根目录的 `version.json`。
