# Design Review Skills

面向产品交付走查的三个 Codex Skill：

- `program-design-review`：验证已开发程序的真实功能、任务闭环、异常恢复、响应式表现和设计实现一致性。
- `figma-design-review`：检查 Figma 页面、流程、原型连接、组件、变量、状态覆盖和交付质量。
- `portfolio-design-review`：检查求职作品集的项目叙事、事实证据、产品逻辑、图片质量和逐页版式。

每个 Skill 均包含：

- `SKILL.md`：使用范围、走查流程、证据规则和输出格式。
- `references/checklist.md`：针对对应对象的详细检查清单。
- `agents/openai.yaml`：Skill 的界面元数据。

## 安装

将需要的 Skill 目录复制到：

```text
~/.codex/skills/
```

重新启动或刷新 Codex 后即可使用。

## 原则

- 不把静态页面当作真实功能。
- 不把设计稿状态当作后端已实现。
- 不虚构访谈、市场数据、测试结果或上线能力。
- 每个问题都需要证据、严重度、影响和可执行建议。
