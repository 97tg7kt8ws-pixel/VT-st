# 独立商品图工坊在线更新

此仓库用于发布独立商品图工坊 Windows x64 便携版更新。

## 当前版本

- 版本：2.0.1
- 软件包：`IndependentProductStudio_Windows_x64_v2.0.1.1.zip`
- SHA-256：`9a2175f01058866e5228a8e1f4980caab529e794281c5a895b28d0b725ef5098`
- 安装方式：完整解压后双击 `IndependentProductStudio.exe`

## v2.0.1 更新内容

- 真实生成 EXIF 新增完整国家/地区选择。
- 国家以英文名称和两位地区代码写入。
- 不写入或伪造 GPS 经纬度。
- 默认接入此 GitHub 在线更新地址。

## 软件内更新地址

```text
https://raw.githubusercontent.com/97tg7kt8ws-pixel/VT-st/main/version.json
```

软件会检查版本、下载 Release 中的 ZIP、验证文件大小与 SHA-256，然后自动替换并重启。更新失败时会恢复旧版本。

## 发布顺序

发布新版本时，先创建对应版本的 GitHub Release 并上传 ZIP，确认可以下载后，最后更新仓库根目录的 `version.json`。
