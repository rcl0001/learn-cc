---
task_id: "AUTO-GENERATE"
task_type: "monitored_research|monitored_development|monitored_design"
status: "recording|completed|failed|cancelled"
monitoring_mode: true
recording_start: "YYYY-MM-DDTHH:MM:SS+08:00"
recording_end: "YYYY-MM-DDTHH:MM:SS+08:00"
trigger_command: "/task [任务描述]"
estimated_duration: "30m"
actual_duration: "45m"
tools_used: []
sources_accessed: []
data_points_collected: 0
success_metrics:
  - "research_completed: true|false"
  - "key_insights_extracted: true|false"
  - "actionable_conclusions: true|false"
tags:
  - "monitored"
  - "research"
priority: "high|medium|low"
---

# 监控模式任务日志

## 任务概述
- **触发命令**: `[触发命令]`
- **开始时间**: [开始时间]
- **监控状态**: 🟢 记录中 | 🟡 暂停 | 🔴 已结束
- **日志文件**: [文件路径]

## 实时记录区
*以下内容在任务执行过程中实时更新*

### 会话记录

#### 用户请求 [HH:MM:SS]
```
[用户输入内容]
```

#### AI思考过程 [HH:MM:SS]
```
[AI的思考、决策、计划]
```

#### 工具调用 [HH:MM:SS]
- **工具**: [工具名称]
- **目的**: [调用目的]
- **参数**: 
  ```yaml
  [参数详情]
  ```
- **结果摘要**: [关键结果摘要]
- **原始参考**: [结果文件引用或片段]

#### 信息提取 [HH:MM:SS]
- **来源**: [信息来源]
- **关键信息**: [提取的重要信息]
- **相关性**: [与任务的相关性]

#### 用户反馈 [HH:MM:SS]
```
[用户反馈或进一步请求]
```

### 工具调用链（自动汇总）
| 序号 | 时间 | 工具 | 目的 | 关键结果 | 状态 |
|------|------|------|------|----------|------|
| 1 | HH:MM:SS | [工具] | [目的] | [结果] | ✅/❌ |

### 信息收集汇总
#### 来源1: [来源描述]
- [信息点1]
- [信息点2]

#### 来源2: [来源描述]
- [信息点1]
- [信息点2]

## 任务总结区
*任务结束时填充*

### 执行摘要
- **总工具调用**: [数量] 次
- **信息源访问**: [数量] 个  
- **数据点收集**: [数量] 个
- **关键发现**: [数量] 个

### 研究成果
1. **[主要发现1]**
   - 支持证据: [证据]
   - 重要性: [重要性说明]

2. **[主要发现2]**
   - 支持证据: [证据]
   - 重要性: [重要性说明]

### 结论与建议
1. **[结论1]**
2. **[建议1]**

### 经验教训
1. **有效方法**: [成功的工作方法]
2. **待改进**: [需要改进的方面]
3. **工具使用**: [工具使用经验]

### 后续行动
- [ ] [行动1]
- [ ] [行动2]

## 原始数据区（可选）
*保留原始记录用于深度分析*

### 完整对话记录
```
[完整的对话历史]
```

### 工具调用原始记录
```yaml
- tool: [工具名]
  timestamp: "HH:MM:SS"
  params: [参数]
  result_summary: [结果摘要]
```

### 访问的资源列表
- [资源1: 类型 - 描述]
- [资源2: 类型 - 描述]

## 关联链接
- **相关任务**: [任务ID]
- **参考文档**: [文档路径]
- **产出物**: [创建的文件/代码]
- **知识链接**: [相关知识点]

---
*日志创建时间: YYYY-MM-DD HH:MM:SS*
*最后更新: YYYY-MM-DD HH:MM:SS*
*监控模式: 🟢 激活中*