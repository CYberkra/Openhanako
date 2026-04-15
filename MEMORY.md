# MEMORY

## 迁移记录
- 2026-04-15: 从 OpenClaw/ClawX 迁移核心配置到 Hanako
- 继承设定：小白人格、称呼宝宝、SOUL.md 核心规则、QMD 项目索引
- 2026-04-15: 接管 D:\ClawX-Data 工作空间

## Skills
- [OpenCode Runner](skills/opencode-runner/SKILL.md) - AI 编程助手调用工具
- [Storage Manager](skills/storage-manager/SKILL.md) - D盘存储管理、归档、备份工具
- [Ontology](skills/ontology/SKILL.md) - 结构化知识图谱
- [Grep Vercel](skills/grep-vercel/SKILL.md) - GitHub 代码搜索工具
- [Baiiy Screen Control](skills/baiiy-screen-control/SKILL.md) - 屏幕控制工具（Turix + pyautogui）

## Topics
- [QMD](topics/qmd.md)

## D:\ClawX-Data 工作空间总览

### 目录结构（按用途）

| 目录 | 用途 | 关键内容 |
|------|------|---------|
| `code/` | GPR GUI 主流程代码快照 | `GPR_GUI_main_YYYY-MM-DD/` 系列版本 |
| `sim/gprmax/inputs/` | gprMax 仿真输入文件 | `custom_realistic_bscan_2D.in`, `custom_uavgpr_bscan_2D.in` |
| `sim/gprmax/outputs/` | 仿真原始输出 (.out/.h5) | 原始 gprMax 输出 |
| `sim/gprmax/processed/` | 仿真处理结果 (csv/png) | dewow、agc、背景抑制对比图、autotune 结果 |
| `sim/gprmax/gui_ready/` | GUI 可直接加载的数据 | `custom_realistic_bscan_2D_Ez_gui.csv` 等 |
| `sim/gprmax_outcsv/` | 批量正演模拟结果 | 4 个模型批次（2026-04-03） |
| `reports/` | 报告、PPT、每日汇总 | 23 份 `gh_daily_summary`、组会 PPT、技术报告 |
| `datasets/raw/` | 原始数据归档 | 当前为空 |
| `datasets/processed/` | 处理后数据归档 | 当前为空 |
| `exports/images/` | 图片/截图/对比图 | GUI 截图、窗口截图 |
| `exports/slides/` | 幻灯片/演讲页面 | Slidev demo 文件 |
| `deliverables/` | 正式交付物 | 当前为空 |
| `backups/` | 完整备份 | `ClawX-Full-Backup-20260329/` |
| `archive/2026-03/` | 历史归档 | 按月归档的旧文件 |
| `skills/` | 自定义 skills 代码 | `baiiy-screen-control/`, `storage-manager/`, `turix/` 等 |
| `tools/` | 工具脚本 | `baiiy_screen_controller.py`, `turix_server.py` 等 |
| `ontology/` | 知识图谱 schema | `gpr_entities.yaml`, `gpr_schema.yaml` |
| `tmp/` | 临时文件 | 临时数据 |

### 路径策略
- **默认产出目录**：D 盘优先，所有新产出物按 `README_PATH_POLICY.md` 写入对应子目录
- **C 盘历史文件**：保留中，后续按月归档到 `archive/YYYY-MM/`

## 项目数据位置
- GPRMax 模拟输出：`D:\ClawX-Data\sim\gprmax_outcsv\`
- 备份目录：`D:\ClawX-Data\backups\`
- 报告文件：见 QMD_INDEX.md
