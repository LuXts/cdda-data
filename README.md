# cdda-data

CDDA 游戏数据镜像，数据由 GitHub Actions 自动从 [LYHGLYTX/Cataclysm-Cleanwater-Bomb](https://github.com/LYHGLYTX/Cataclysm-Cleanwater-Bomb) 拉取并更新。

## 使用

数据通过 `raw.githubusercontent.com` 提供：

```
https://raw.githubusercontent.com/LuXts/cdda-data/main/data/latest/all.json
```

## 数据格式

```json
{
  "build_number": "版本号",
  "release": { },
  "data": [ /* 所有游戏对象 */ ],
  "mods": { /* mod 信息 */ }
}
```
