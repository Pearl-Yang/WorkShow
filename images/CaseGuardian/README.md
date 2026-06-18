# "检管家"案件全流程智慧化管理平台 - 图片资源

## 概述

本文件夹包含"检管家"项目文档中引用的所有图片资源，按功能模块进行分类整理。

## 文件夹结构

```
images/CaseGuardian/
├── 00-architecture/          # 平台架构与概述
│   ├── 01-policy-background.png           # 图1 政策背景
│   └── 05-flow-config-entity.png          # 图5 案件流程配置文件实体
│
├── 02-research-demand/       # 调研与需求分析
│   └── 02-field-research.png              # 图2 实地调研访谈
│
├── 03-frontend-ui/           # 前端界面展示
│   ├── 03-frontend-main.jpeg             # 图3 前端整体界面展示
│   ├── 04-frontend-components.jpeg         # 图4 前端特色组件展示
│   ├── 06-case-flow-monitor.jpeg          # 图6 办案流程监控主页面实体
│   ├── 07-flow-timeline.png               # 图7 流程详情时间轴页面实体
│   ├── 08-login-page.png                  # 图8 用户登录界面
│   └── 09-web-interface.jpeg              # 图9 网页界面
│
├── 04-backend-architecture/ # 后端架构
│   ├── 10-backend-entities.jpeg           # 图10 后端核心实体类截图
│   ├── 11-backend-service.jpeg            # 图11 后端服务层实现截图
│   ├── 12-database-schema.png             # 图12 案卡配置相关数据库表结构截图
│   └── 13-api-docs.png                   # 图13 Flask交互式API文档界面
│
├── 05-rule-engine/          # 规则引擎配置
│   ├── 14-admin-deadline-config.png       # 图14 管理员期限配置界面
│   ├── 15-case-flow-config.png            # 图15 配置办案流程界面
│   ├── 16-personal-todo.jpeg              # 图16 个人待办案件管理实体
│   ├── 17-closed-case-query.jpeg          # 图17 已结案案件查询实体
│   ├── 18-dept-case-management.png        # 图18 部门案件管理实体
│   └── 19-handler-query.png              # 图19 承办人查询实体
│
├── 06-smart-warning/         # 智能预警
│   ├── 20-four-color-warning.png          # 图20 个人端四色预警、财物统计
│   ├── 21-popup-alert.png                # 图21 弹窗提示界面
│   ├── 22-calendar-schedule.png          # 图22 工作日历处自定义日程
│   └── 23-property-warning.png           # 图23 涉案财物预警及下一步操作提示
│
├── 07-document-processing/   # 文书智能处理
│   ├── 24-case-basic-info.png             # 图24 案件基本信息新建界面
│   ├── 25-document-entry.png              # 图25 对应节点录入文书界面
│   ├── 26-document-create.png             # 图26 文书新建界面
│   ├── 27-document-edit.png              # 图27 文书制作界面
│   ├── 28-comparison-fill.png            # 图28 对照填写界面
│   ├── 29-document-compare.png           # 图29 文书对比校验界面
│   ├── 30-language-check.png             # 图30 语句准确性校验
│   ├── 31-legal-citation-check.png       # 图31 法条引用错误、内容错误校验
│   ├── 32-mandatory-warning-check.png     # 图32 强制校验与提示校验
│   └── 33-document-management.png         # 图33 文书管理界面
│
├── 08-case-card/             # 案卡自动回填
│   ├── 34-case-card-fill.png             # 图34 案卡填写界面
│   ├── 35-case-card-entity.png          # 图35 案卡智能回填相关实体类
│   └── 36-case-card-code.png            # 图36 案卡智能回填相关实体类代码截图
│
├── 09-data-dashboard/        # 数据看板
│   ├── 37-data-cockpit.png              # 图37 数据驾驶舱实体设计及实现界面
│   ├── 38-org-dashboard.png             # 图38 全院数据看板
│   ├── 39-personal-dashboard.png        # 图39 个人端数据看板及工作台概览
│   ├── 40-personal-dashboard-search.jpeg # 图40 个人端数据看板检索界面
│   └── 41-personal-case-dashboard.jpeg  # 图41 个人端案件管理看板
│
├── 10-property-management/   # 涉案财物管理
│   ├── 42-property-overview.jpeg        # 图42 涉案财物概览界面
│   ├── 43-property-stats.jpeg           # 图43 涉案财物统计
│   └── 44-payment-match.png             # 图44 到账匹配、提醒界面
│
├── 11-quality-review/        # 案件质量评查
│   ├── 45-self-review.png               # 图45 承办人自查界面
│   ├── 46-self-review-2.jpeg            # 图46 承办人自查界面
│   ├── 47-quality-overview.png          # 图47 承办人案件质量评查概览界面
│   ├── 48-dept-inspection.png           # 图48 部门负责人智能检查界面
│   ├── 49-case-management-review.png     # 图49 案件管理部门智能评查界面
│   ├── 50-assessment-stats.png          # 图50 承办人考核管理统计界面
│   ├── 51-common-problems.png           # 图51 多发问题分析汇总统计界面
│   └── 52-quality-review-api.png        # 图52 案件质量评查相关服务接口实体
│
├── 12-ai-assistant/          # AI辅助问答
│   └── 53-ai-chat.png                   # 图53 AI辅助问答界面
│
├── 13-collaborative-supervision/  # 协同办案监督
│   ├── 54-cross-dept-message.png       # 图54 跨机关消息接收界面
│   └── 55-full-process-monitor.png    # 图55 案件全流程监控界面
│
├── 14-innovation-advantage/  # 创新点与优势
│   ├── 56-requirement-framework.png    # 图56 需求对应框架
│   ├── 57-innovation-mindmap.jpeg      # 图57 平台创新点思维导图
│   └── 58-digital-prosecution-policy.png  # 图58 数字检察政策
│
└── 15-extra-screenshots/    # 额外截图（文档补充图片）
    ├── image_059.png ~ image_090.png     # 技术细节、代码实现等补充截图
    └── README.md
```

## 功能模块说明

### 1. 平台架构与概述 (00-architecture)
- 政策背景展示
- 系统整体架构设计

### 2. 调研与需求分析 (02-research-demand)
- 实地调研访谈记录
- 需求调研成果

### 3. 前端界面展示 (03-frontend-ui)
- Vue 3 + Element Plus 构建的用户界面
- 案件流程监控、时间轴等核心页面
- 用户登录与认证界面

### 4. 后端架构 (04-backend-architecture)
- Spring Boot 后端架构
- MyBatis-Plus 数据层设计
- Flask API 文档

### 5. 规则引擎配置 (05-rule-engine)
- 可视化规则配置界面
- 办案流程自定义配置
- 多角色权限管理

### 6. 智能预警 (06-smart-warning)
- 四色分级预警机制（绿/黄/橙/红）
- 弹窗消息推送
- 涉案财物处理提醒

### 7. 文书智能处理 (07-document-processing)
- 文书上传与制作
- NLP 智能校验（法条引用、语句准确性等）
- 强制校验与提示校验双模式

### 8. 案卡自动回填 (08-case-card)
- OCR + NLP 信息抽取
- 多源数据融合
- 人工校验机制

### 9. 数据看板 (09-data-dashboard)
- ECharts 可视化图表
- 多角色数据视图（院领导/部门负责人/承办人）
- 实时数据更新

### 10. 涉案财物管理 (10-property-management)
- 财物全流程追踪
- 银行账户联动
- 款项自动匹配

### 11. 案件质量评查 (11-quality-review)
- 三级评查体系（自查/检查/评查）
- AI 智能评查
- 多发问题分析

### 12. AI辅助问答 (12-ai-assistant)
- RAG 架构智能问答
- 办案流程咨询
- 法条检索辅助

### 13. 协同办案监督 (13-collaborative-supervision)
- 公检法消息互通
- 全流程可视化监控

### 14. 创新点与优势 (14-innovation-advantage)
- 平台创新点思维导图
- 需求对应框架
- 政策背景

## 技术栈

- **前端**: Vue 3.4 + Vite + Element Plus 2.4 + ECharts + Pinia
- **后端**: Spring Boot 3.1.6 + Spring Security + MyBatis-Plus
- **数据库**: MySQL 8.0 + Redis
- **AI能力**: HanLP + PaddleOCR + Neo4j + XGBoost
- **规则引擎**: SpEL/MVEL + 自研可视化配置
- **消息推送**: WebSocket + RabbitMQ

## 图片统计

- **主图数量**: 58张（文档中明确引用的图1-58）
- **额外截图**: 32张（技术细节、代码实现等）
- **总计**: 90张图片

## 更新说明

- 2026-06-19: 初始创建，完成图片分类整理
