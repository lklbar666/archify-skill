# Archify Skill (ima 兼容版)

将任何想法、计划或代码库转化为交互式HTML图表。支持10种图表类型，输出独立可分享的HTML文件。

## 核心功能

- **10种图表类型**：Architecture / Workflow / Sequence / Data Flow / Lifecycle / ERD / Class / Tree / Timeline / Waterfall
- **独立HTML输出**：单个文件，深色/浅色主题，交互探索，导出PNG/SVG/WebM
- **代码库证据**：可扫描真实仓库，节点关联Git提交和文件行号
- **Mermaid转换**：支持从Mermaid语法转换为Archify JSON
- **一页式解释**：Explainer模式，结论先行+结构化面板
- **原子验证**：schema/layout/HTML/SVG/route检查全部通过才交付

## 安装（ima）

下载 `archify-skill.zip`，在ima中导入即可。

## 快速开始

```bash
# 诊断环境
node bin/archify.mjs doctor

# 生成演示
node bin/archify.mjs demo ./output

# 生成架构图
node bin/archify.mjs finalize architecture candidate.json output.html --quality showcase --json
```

## 原始项目

- GitHub: [tt-a1i/archify](https://github.com/tt-a1i/archify) (88k stars)
- 官网: [archify.si](https://archify.si)
- 协议: MIT

## 版本

基于 Archify v3.2.0 (2026-10-18) 打包，ima兼容版。
