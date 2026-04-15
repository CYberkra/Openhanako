# QMD 索引 (Quality Managed Data)

> 更新时间: 2026-04-15 (从 OpenClaw 迁移)
> 数据来源: memory/2026-04-15.md

---

## GPRMax 模拟数据

### 弯曲裂缝模型 (100道)
- **ID**: bent_crack_20260401_135308
- **类型**: GPR 正演模拟
- **方向**: 左上 → 右下
- **裂缝宽度**: 5cm
- **道数**: 100道
- **网格**: dx=dy=0.005m
- **模型尺寸**: 5m × 2m
- **位置**: `D:\ClawX-Data\sim\gprmax_outcsv\bent_crack_20260401_135308\`
- **文件**:
  - bent_crack_model.png (模型图)
  - bent_crack_model.in (gprMax配置)
  - bent_crack_model1-100.out (100个原始数据)
  - bent_crack_bscan_matrix.csv (合并B-scan矩阵)
- **状态**: ✅ 已完成
- **质量**: B-scan清晰显示弯曲裂缝衍射特征，与参考图形状匹配

---

## 软件工具

### gprMax GUI 修复
- **文件**: `gprmax_gui_standalone_v3.py`
- **问题**: GUI启动后显示不全
- **修复内容**:
  - 窗口大小: 1520x960 → 1400x850
  - 左侧面板添加滚动条
  - 标签宽度: 20 → 16
  - 最小宽度: 480px
  - 窗口居中显示
- **创建文件**: `start_gui.bat`
- **状态**: ✅ 已修复

---

## UAV GPR 运动补偿报告

### v1.0 基础版
- **文件**: `uavgpr_motion_compensation_report.html`
- **内容**: UAV GPR 运动补偿技术基础调研
- **涵盖**: 位置补偿、采样间距补偿、高度补偿、姿态补偿
- **状态**: ✅ 已完成

### v2.0 深度版
- **文件**: `uavgpr_motion_compensation_v2_report.md`
- **内容**: 2024-2025年最新研究进展、开源工具链、实际案例
- **新增**:
  - 高斯过程回归姿态补偿
  - 实时处理架构
  - GPRPy/gprMax/GPR-FWI-Py 工具对比
  - 完整 Python 实现代码
- **状态**: ✅ 已完成

---

## 设计类 Skills

| Skill | 用途 | 状态 |
|-------|------|------|
| brand-guidelines | Anthropic 品牌规范 | ✅ 已安装 |
| canvas-design | 视觉艺术创作 (30+字体) | ✅ 已安装 |
| frontend-design | 前端界面设计 | ✅ 已安装 |
| theme-factory | 10个预设主题 | ✅ 已安装 |

## 索引统计

| 类别 | 数量 |
|------|------|
| GPRMax 模拟数据 | 1 |
| 软件工具修复 | 1 |
| 技术报告 | 2 |
| 设计类 Skills | 4 |

---

*自动维护中*
