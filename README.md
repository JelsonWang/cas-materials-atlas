# 中国科学院材料类硕士招生全景地图与智能择校决策系统

品牌：材料碎碎念 / MSE. / MATETALKING

## 网站内容

本仓库为静态网站，`index.html` 已内嵌页面样式、交互逻辑、地图 GeoJSON、数据和 Logo，无需安装依赖或部署后端。

- 目标招生年度：2027
- 数据核查标识：2026-11-01（来自原 HTML 的数据库标记，不代表发布时重新核实）
- 内嵌研究所数据：89 条；默认展示 A 类 79 条，B 类与 C 类各 5 条
- 交互：中国地图、筛选、院所详情、收藏、比较、统计和导出

## GitHub Pages 发布

1. 登录 GitHub，在 https://github.com/new 新建公开仓库 `cas-materials-atlas`。请勾选 **Add a README file** 以创建 `main` 分支。
2. 将本目录内的 `index.html`、`.nojekyll` 和 `README.md` 上传到仓库根目录并提交（上传时按实际需要覆盖自动生成的 README）。**不要只上传 ZIP**。
3. 打开仓库 `Settings` → `Pages`，在 **Build and deployment** 选择 `Deploy from a branch`，设置分支 `main`，目录 `/ (root)`，点击 `Save`。
4. 部署完成后访问：`https://jelsonwang.github.io/cas-materials-atlas/`。请以 GitHub Pages 提供的部署状态为准。

## 数据使用提示

这是第三方信息整理工具，非中国科学院、中国科学院大学或中国科大的官方招生平台。评分、历史分数、待遇及招生计划等字段可能变化，报考前请逐项查阅官方网站与当年招生公告。原 HTML 中标注的“已核实”不等同于本次部署对每条数据进行独立验证。

## 变更说明

- GitHub Pages 入门文件命名为 `index.html`
- 修复筛选面板里 A 类院所数量显示为 41 的文本错误，使其与内嵌数据库 79 条 A 类记录一致
- 未改动招生数据、算法和地图核心逻辑