# 独立商品图工坊在线更新

此仓库用于发布独立商品图工坊 Windows x64 便携版更新。

## 当前版本

- 版本：2.0.0
- 软件包：`IndependentProductStudio_Windows_x64_v2.0.0.zip`
- 安装方式：完整解压后双击 `IndependentProductStudio.exe`

## 软件内更新地址

在软件的“设置与更新”中填写：

```text
https://raw.githubusercontent.com/97tg7kt8ws-pixel/VT-st/main/version.json
```

软件会检查版本、下载 Release 中的 ZIP、验证文件大小与 SHA-256，然后自动替换并重启。更新失败时会恢复旧版本。

## 发布顺序

发布新版本时，先创建对应版本的 GitHub Release 并上传 ZIP，确认可以下载后，最后更新仓库根目录的 `version.json`。
