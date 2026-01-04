# {{capabilityName}} 当前能力

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: {{version}}  
**状态**: {{status}}

## 概述

本文档描述了 {{capabilityName}} 的当前能力状态，包括能力定义、当前实现、能力成熟度评估和关键指标。

## 能力定义

### 能力描述

{{capabilityDescription}}

### 能力范围

{{capabilityScope}}

### 能力边界

{{capabilityBoundaries}}

## 当前实现

### 业务能力

{{currentBusinessCapability}}

### 应用能力

{{currentApplicationCapability}}

### 数据能力

{{currentDataCapability}}

### 技术能力

{{currentTechnologyCapability}}

## 能力成熟度评估

### 成熟度等级

| 维度 | 当前等级 | 评分 | 说明 |
|------|---------|------|------|
| 业务成熟度 | {{businessMaturityLevel}} | {{businessMaturityScore}} | {{businessMaturityNote}} |
| 应用成熟度 | {{applicationMaturityLevel}} | {{applicationMaturityScore}} | {{applicationMaturityNote}} |
| 数据成熟度 | {{dataMaturityLevel}} | {{dataMaturityScore}} | {{dataMaturityNote}} |
| 技术成熟度 | {{technologyMaturityLevel}} | {{technologyMaturityScore}} | {{technologyMaturityNote}} |
| **综合成熟度** | **{{overallMaturityLevel}}** | **{{overallMaturityScore}}** | **{{overallMaturityNote}}** |

### 成熟度雷达图

```mermaid
quadrantChart
    title 能力成熟度评估
    x-axis 低 --> 高
    y-axis 低 --> 高
    quadrant-1 优势能力
    quadrant-2 战略能力
    quadrant-3 待提升能力
    quadrant-4 支撑能力
    业务成熟度: [{{businessMaturityScore}}, {{businessMaturityScore}}]
    应用成熟度: [{{applicationMaturityScore}}, {{applicationMaturityScore}}]
    数据成熟度: [{{dataMaturityScore}}, {{dataMaturityScore}}]
    技术成熟度: [{{technologyMaturityScore}}, {{technologyMaturityScore}}]
```

## 关键指标

### 性能指标

| 指标名称 | 当前值 | 目标值 | 单位 | 说明 |
|---------|--------|--------|------|------|
| {{metric1}} | {{value1}} | {{target1}} | {{unit1}} | {{note1}} |
| {{metric2}} | {{value2}} | {{target2}} | {{unit2}} | {{note2}} |

### 质量指标

| 指标名称 | 当前值 | 目标值 | 单位 | 说明 |
|---------|--------|--------|------|------|
| {{qualityMetric1}} | {{qualityValue1}} | {{qualityTarget1}} | {{qualityUnit1}} | {{qualityNote1}} |
| {{qualityMetric2}} | {{qualityValue2}} | {{qualityTarget2}} | {{qualityUnit2}} | {{qualityNote2}} |

## 当前架构视图

```mermaid
graph TB
    A[{{capabilityName}}] --> B[业务层]
    A --> C[应用层]
    A --> D[数据层]
    A --> E[技术层]
    
    B --> B1[当前业务能力]
    C --> C1[当前应用能力]
    D --> D1[当前数据能力]
    E --> E1[当前技术能力]
    
    style A fill:#4a90e2,color:#fff
    style B fill:#50c878,color:#fff
    style C fill:#ff6b6b,color:#fff
    style D fill:#ffa500,color:#fff
    style E fill:#9b59b6,color:#fff
```

## 能力差距分析

### 主要差距

{{capabilityGaps}}

### 改进机会

{{improvementOpportunities}}

## 相关项目

| 项目名称 | 项目状态 | 对能力的贡献 | 关联度 |
|---------|---------|------------|--------|
| {{project1}} | {{status1}} | {{contribution1}} | {{relevance1}} |
| {{project2}} | {{status2}} | {{contribution2}} | {{relevance2}} |

## 相关文档

- [[目标能力]]
- [[能力增量]]
- [[相关领域架构]]

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

