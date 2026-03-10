# Obsidian Template

用于 Obsidian 的日记模板集合（程序员日记 + 周学习路线）。

## 目录结构
- `ProgrammerDiaryTemplate/Programmer_DailyNote_Template.md` 程序员日记模板
- `Scripts/getDiaryMeta.js` 日记元数据脚本（位置、天气、农历）

## 使用方式
1. 在 Obsidian 中启用 Templater 插件。
2. 将 `ProgrammerDiaryTemplate/Programmer_DailyNote_Template.md` 放入你的模板目录。
3. 将 `Scripts/getDiaryMeta.js` 放入 Templater 用户脚本目录，并在 Templater 中启用 `tp.user.getDiaryMeta`。
4. 新建日记时选择该模板即可自动填充元数据。

## 脚本配置
`Scripts/getDiaryMeta.js` 中需要配置：
- 高德地图 API Key（位置、天气）
- 聚合数据 API Key（农历）

未配置时会在模板中显示提示信息。
