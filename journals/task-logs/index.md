# 任务日志总览

## 目录结构
```
journals/task-logs/
├── 2026/
│   ├── 04-april/
│   │   ├── index.md           # 本月索引
│   │   ├── 2026-04-06-task-001.md
│   │   └── ... (其他日志)
│   └── 05-may/               # 下个月
├── templates/                # 链接到模板目录
└── index.md                 # 本文件
```

## 年度索引

### 2026年
- [2026年4月](2026/04-april/index.md)

## 使用指南

### 1. 创建新任务日志
1. 复制模板：`cp ../../templates/task-logs/task-log-template.md 2026/MM-month/YYYY-MM-DD-task-XXX.md`
2. 编辑文件：填写任务详情
3. 更新索引：在对应月份的index.md中添加记录

### 2. 日志命名规范
- 格式：`YYYY-MM-DD-task-XXX.md`
- 示例：`2026-04-06-task-001.md`
- 编号：每天从001开始顺序编号

### 3. 日志内容要求
- 必须填写YAML Frontmatter中的task_id、task_type、status等关键字段
- 清晰记录思考链条和执行过程
- 诚实评估结果，包括失败和教训

### 4. 复盘分析
- 每周：查看当周日志，识别模式
- 每月：更新月度统计，总结经验
- 每季度：分析趋势，调整工作方法

## 模板链接
- [任务日志模板](../../templates/task-logs/task-log-template.md)

## 设计理念
1. **最小侵入性**：不改变现有工作流
2. **结构化可分析**：支持机器学习和统计分析
3. **渐进式完善**：从手动记录到智能集成
4. **知识沉淀**：将经验教训转化为可复用知识

## 相关文档
- [任务日志系统设计](../../notes/concepts/task-execution-logging-system.md)

---
*系统启动时间: 2026-04-06*