# 独立商品图工坊在线更新

此仓库用于发布独立商品图工坊 Windows x64 便携版更新。

## 当前版本

- 版本：2.1.1
- 软件包：`IndependentProductStudio_Windows_x64_v2.1.1.zip`
- SHA-256：`3c1c58475206dcd02ab74e947c7218de544d59568fef3774f839f40ab7209448`
- 安装方式：完整解压后双击 `IndependentProductStudio.exe`

## v2.1.1 更新内容

- 强化真实生活背景提示词，改善背景比例、材质、透视和自然细节。
- 真实性质检新增假背景识别，严重错误会自动重新生图。
- 默认使用 high 生图质量，并提高 JPEG 输出品质。
- 新增自然清晰增强，在不改变图片尺寸的情况下轻微提升细节。
- 保留 v2.1.0 的流畅兼容、拍摄视角旋转、自定义背景提示词和 1500 个背景场景。

## 软件内更新地址

```text
https://raw.githubusercontent.com/97tg7kt8ws-pixel/VT-st/main/version.json
```

软件会检查版本、下载 Release 中的 ZIP、验证文件大小与 SHA-256，然后自动替换并重启。更新失败时会恢复旧版本。

> 本次 Release 标签实际为 `v2.1.0`，附件及软件内部版本为 `v2.1.1`，因此更新清单使用实际可下载的 Release 路径。

## 发布顺序

发布新版本时，先创建对应版本的 GitHub Release 并上传 ZIP，确认可以下载后，最后更新仓库根目录的 `version.json`。
