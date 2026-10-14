<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-light.svg" alt="Afloat16 — 机器人、大模型与三维重建" width="100%">
</picture>

[English](README.md) · [简体中文](README.zh-CN.md)

**我的研究主要围绕机器人、大模型和三维重建。**

我使用Python与TypeScript开发可复现的工具，也为相关开源库贡献具体修复。

## 我维护的项目

| 方向 | 项目与用途 |
|---|---|
| 三维重建 | [ReconTrail](https://github.com/Afloat16/recontrail)：CPU摄影测量与离线报告；[COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit)：传统文本模型预检；[Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge)：明确相机位姿约定后转换。 |
| 机器人 | [Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit)：ROS 2录包时间检查；[TF Route Audit](https://github.com/Afloat16/tf-route-audit)：导出TF/URDF拓扑和观测时间范围。 |
| 大模型 | [LLM Handshake](https://github.com/Afloat16/llm-handshake)：有界接口探测；[SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit)：保存的流式响应审计；[Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit)：真实工具尝试记录审计。 |
| 工程工作流 | [Research to Fix](https://github.com/Afloat16/research-to-fix)：调研与本地验证；[Debate Direction](https://github.com/Afloat16/debate-direction)：需求论证；[StewardCheck](https://github.com/Afloat16/ai-dev-steward/tree/main/tools/stewardcheck)：任务验收；[Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier)：等待输入时提醒。 |
| MCP建议 | [Jev MCP](https://github.com/Afloat16/jev-mcp)：四个保守的只读建议工具，非官方TypeSafe Jev集成。 |

[完整项目导航](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.zh-CN.md)说明安装、适用场景和边界。六个领域工具在所记录版本中合计67项本地测试、36组跨平台CI通过，均为实验性诊断或转换工具，不代表全部协议认证或上游问题已解决。

## 精选已合并贡献

截至2026-10-14，公开记录核验到 **17个上游仓库中的41份已合并PR**。下列精选项包含代码修复及回归覆盖。

| 上游项目 | 实际贡献 | 证据 |
|---|---|---|
| [DeepFace](https://github.com/serengil/deepface) · 23,549 ★ | 检测框先裁到图像边界，补充裁剪边界回归。 | [#1655](https://github.com/serengil/deepface/pull/1655) · 已合并 |
| [Sentence Transformers](https://github.com/huggingface/sentence-transformers) · 19,171 ★ | 以weighted log-sigmoid保留排名损失梯度。 | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · 已合并 |
| [Kornia](https://github.com/kornia/kornia) · 11,424 ★ | 归一化小根四次方程尺度，修复数值阈值行为。 | [#5474](https://github.com/kornia/kornia/pull/5474) · 已合并 |
| [Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch) · 10,706 ★ | 统一1D diffusion的外部条件与self-conditioning参数传递。 | [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) · 已合并 |
| [Atomic Agents](https://github.com/Eigenwise/atomic-agents) · 6,283 ★ | 加载失败时保留已有聊天历史。 | [#292](https://github.com/Eigenwise/atomic-agents/pull/292) · 已合并 |
| [Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python) · 3,536 ★ | 保留Unicycle角速度单位与限幅语义。 | [#719](https://github.com/petercorke/robotics-toolbox-python/pull/719) · 已合并 |
| [RSL-RL](https://github.com/leggedrobotics/rsl_rl) · 3,065 ★ | 从PPO checkpoint恢复RND探索调度。 | [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · 已合并 |
| [PyPose](https://github.com/pypose/pypose) · 1,614 ★ | 用log1p保留小残差的Cauchy目标值。 | [#416](https://github.com/pypose/pypose/pull/416) · 已合并 |

Stars是上游仓库的日期快照；PR链接保留具体变更、审阅和验证限制。另见[贡献明细](docs/CONTRIBUTIONS.md)。

## 已获维护者审批的机器人贡献

以下两条贡献的当前版本已获仓库作者审批，均为**待合并**，与上方已合并成果分别展示。

| 贡献 | 改动 | 审阅状态 |
|---|---|---|
| [Robotics Toolbox #735](https://github.com/petercorke/robotics-toolbox-python/pull/735) | 用圆统计计算粒子滤波航向均值与离散程度。 | [仓库作者已审批](https://github.com/petercorke/robotics-toolbox-python/pull/735#pullrequestreview-5515511147) · 待合并 |
| [Robotics Toolbox #736](https://github.com/petercorke/robotics-toolbox-python/pull/736) | 归一化五次轨迹时间，保留边界约束。 | [仓库作者已审批](https://github.com/petercorke/robotics-toolbox-python/pull/736#pullrequestreview-5515624165) · 待合并 |
