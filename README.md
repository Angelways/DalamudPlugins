# Angelways Dalamud Plugins

在 Dalamud 的自定义插件仓库中添加：

```text
https://raw.githubusercontent.com/Angelways/DalamudPlugins/main/pluginmaster.json
```

每个插件的发布包位于 `plugins/<InternalName>/latest.zip`。仓库根目录的
`pluginmaster.json` 从这些发布包中的清单自动生成，可在同一个自定义插件库
中收录多个插件。

更新插件包后运行：

```powershell
python generate_pluginmaster.py
```
