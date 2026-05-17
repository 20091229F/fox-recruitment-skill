# 轻资产创业招募助手 Skill

> 本项目为复星保德信人寿「轻资产创业」招募 AI 助手 Skill，
> 支持「销售潜质自测」与「公司信息浏览」双入口。

## 核心价值

**招募助手 = 智能对话 + 数据支撑 + 持续迭代**

- 12 维度精准识别高潜质人才
- 随时随地获取公司、佣金、培训、产品信息
- 持续学习最新业务动态

## 快速开始

```
① 打开网页版自测 → 访问 https://20091229F.github.io/fox-recruitment-skill/
② 体验 6+6 快速版 → questionnaire/6+6.md（6 道选择 + 6 道问答）
③ 配置 AI 助手 → 复制 recruitment.skill 内容到豆包/DeepSeek
```

## 文件结构

```
fox-protector-recruitment-skill/
├── SKILL.md                 # Skill 核心定义 + 合规使用说明
├── recruitment.skill        # AI 助手提示词（豆包/DeepSeek/元宝通用）
├── index.html              # 销售潜质自测网页（含雷达图 + 预约表单）
├── data/
│   ├── company.md           # 公司背景介绍（G2战略/股东实力/经营数据）
│   ├── commission.md        # 佣金结构说明
│   ├── training.md          # 培训体系（五类培训 + 五大生态）
│   └── products.md          # 产品体系（增额寿/养老金/健康险）
├── questionnaire/
│   └── 6+6.md            # 6+6 快速题库（12 维度 + 人生规划）
└── README.md              # 本文件
```

## 功能模块

### 在 WorkBuddy 中使用

首次使用 clone 本仓库到 `~/.workbuddy/skills/`：

```bash
cd ~/.workbuddy/skills/
git clone https://github.com/20091229F/fox-recruitment-skill.git
```

重启 WorkBuddy 后在「专家」中搜索「轻资产创业」即可使用。

### 在其他 AI 平台使用

复制 `recruitment.skill` 文件内容，粘贴到对应平台的系统提示词/角色设定区域：

- **豆包**：创建智能体 → 粘贴内容 → 发布
- **DeepSeek**：创建助手 → 粘贴到指令 → 保存
- **元宝**：创建智能体 → 粘贴到角色设定 → 完成

推荐触发词：
- "你好" / "开始" / "招募"
- "自测" / "潜质" / "测试"
- "公司" / "培训" / "佣金"
- "预约面试" / "联系"

## 联系方式

项目联系人：**fionass**（sting2009@126.com）

数据来源请参考 `data/` 目录下的各文件。

后台方案可选：
- **方案A**：本地存储（localStorage，适合个人/小团队）
- **方案B**：Google Sheets / 企业微信群机器人 API
- **方案C**：企业 CRM 系统 API 对接

## 更新日志

本 Skill 持续迭代中：
- 2026 年 5 月：新增预约面试表单、雷达图分享功能
- 2026 年 4 月：初版发布，支持 12 维度自测

---

**作者**：fionass @ WorkBuddy
**版本**：2.0
**联系**：sting2009@126.com
