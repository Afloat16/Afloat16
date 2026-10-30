<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-light.svg" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

**我的研究主要围绕机器人、大模型和三维重建。**

我开发可复现的研究工具，开展原生软件保护实验，并为相关开源库贡献具体修复。

Python · TypeScript · C/C++ · 可复现实验 · 上游工程

[我的项目](#我的项目) · [开源贡献](#开源贡献) · [English](README.md)

</div>

## 开源贡献

截至 **2026-10-30**，已核验我向 **24 个上游仓库**提交且已合并的 **82 个 PR**，涉及机器人、机器学习、几何与开发工具。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-10-30-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-10-30-light.svg" alt="82 verified merged upstream PRs across 24 repositories; 5 selected recent merges, each in a project with over 10,000 stars. Snapshot: 2026-10-30." width="100%">
</picture>

### 近期精选已合并贡献 · 上游超过 10,000 ★

精选 **5 条有实质代码改动的近期合并贡献**，按合并时间倒序排列。每条均核对上游星数、作者、合并状态与 commit；筛选聚焦数值正确性、状态管理、协议解析和 I/O 完整性。日期按 Asia/Shanghai 显示。

| 合并日期 | 上游项目 · ★ | 解决的问题 | PR / 合并 commit |
|---|---|---|---|
| 2026-10-27 | **[REA](https://github.com/morluto/rea)**<br>408,869 ★ | 在 CDP 发现阶段先校验 UTF-8，避免因损坏字节被静默替换而改变目标标题和 URL。 | [#4524](https://github.com/morluto/rea/pull/4524)<br>[`095a51c`](https://github.com/morluto/rea/commit/095a51cf38d2a0dc58368f6c9482062d594f856b) |
| 2026-10-23 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,614 ★ | 统一人脸裁剪、返回区域与活体检测 ROI 的右/下边界，修复末端像素丢失和零宽高报告。 | [#1658](https://github.com/serengil/deepface/pull/1658)<br>[`72aca24`](https://github.com/serengil/deepface/commit/72aca240a862559a8a7ef6334c2c1ceb8777a71e) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,581 ★ | 将已有的成对 RoPE 修正应用到 VLA-JEPA 训练期世界预测器，恢复相邻坐标的频率配对。 | [#4835](https://github.com/huggingface/lerobot/pull/4835)<br>[`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |
| 2026-10-22 | **[REA](https://github.com/morluto/rea)**<br>408,869 ★ | 补全 ZIP 定位读取中的短读，提前遇到 EOF 时明确报告完整性错误，并保留读取预算。 | [#4414](https://github.com/morluto/rea/pull/4414)<br>[`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33) |
| 2026-10-16 | **[Haystack](https://github.com/deepset-ai/haystack)**<br>26,880 ★ | 隔离恢复执行时的访问计数，避免重试和断点执行污染原始 PipelineSnapshot。 | [#13076](https://github.com/deepset-ai/haystack/pull/13076)<br>[`34ab691`](https://github.com/deepset-ai/haystack/commit/34ab69146ed9f32688144d2b5a5ff0e81acbf372) |

### 最近一次核实的贡献榜前 30

**14 个上游项目有前 30 位的已核验证据**：其中 6 个为 10 月 30 日核实，8 个保留 10 月 23 日快照。每行标明排名核验日期；各组按当前 star 降序排列，作者 commit 数与 PR 数已于本次更新。

| 项目 | 上游 ★ | 位置 · 核验日期¹ | 作者 commits² | 已合并 PR | 代表工作 |
|---|---:|---:|---:|---:|---|
| **[DeepFace](https://github.com/serengil/deepface)** | 23,614 | [#10](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [18](https://api.github.com/repos/serengil/deepface/commits?author=Afloat16&per_page=100&page=1) | **[18](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正人脸裁剪边界、归一化与向量检索行为。 [#1655](https://github.com/serengil/deepface/pull/1655) · [#1658](https://github.com/serengil/deepface/pull/1658) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,721 | [#9](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [1](https://api.github.com/repos/lucidrains/denoising-diffusion-pytorch/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留一维扩散中的外部条件与自条件。 [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,313 | [#28](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [2](https://api.github.com/repos/Eigenwise/atomic-agents/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 加载失败时保留已有对话历史。 [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,557 | [#6](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [11](https://api.github.com/repos/petercorke/robotics-toolbox-python/commits?author=Afloat16&per_page=100&page=1) | **[11](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正运动学、动力学、逆运动学与 URDF 处理。 [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,106 | [#5](https://api.github.com/repos/leggedrobotics/rsl_rl/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [3](https://api.github.com/repos/leggedrobotics/rsl_rl/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复 RND 调度进度，保持奖励历史独立并保留 rollout 尾批样本。 [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,620 | [#15](https://api.github.com/repos/pypose/pypose/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [6](https://api.github.com/repos/pypose/pypose/commits?author=Afloat16&per_page=100&page=1) | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 最小二乘刚体配准、鲁棒核稳定性与相机参数广播。 [#437](https://github.com/pypose/pypose/pull/437) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,102 | [#3](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [10](https://api.github.com/repos/geoopt/geoopt/commits?author=Afloat16&per_page=100&page=1) | **[10](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 流形约束、梯度投影、优化器状态与几何计算稳定性。 [#267](https://github.com/geoopt/geoopt/pull/267) · [#254](https://github.com/geoopt/geoopt/pull/254) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,100 | [#3](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [3](https://api.github.com/repos/Toni-SM/skrl/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正高斯策略计算，保持跨后端探索行为一致。 [#475](https://github.com/Toni-SM/skrl/pull/475) |
| **[pytransform3d](https://github.com/dfki-ric/pytransform3d)** | 707 | [#15](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [2](https://api.github.com/repos/dfki-ric/pytransform3d/commits?author=Afloat16&per_page=100&page=1) | **[2](https://github.com/dfki-ric/pytransform3d/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 稳定李群雅可比计算并修正螺旋轴的平移处理。 [#389](https://github.com/dfki-ric/pytransform3d/pull/389) |
| **[RoMa](https://github.com/naver/roma)** | 647 | [#2](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [4](https://api.github.com/repos/naver/roma/commits?author=Afloat16&per_page=100&page=1) | **[4](https://github.com/naver/roma/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 四元数广播、仿射变换张量形状与可复现采样。 [#33](https://github.com/naver/roma/pull/33) |
| **[Rectified Flow](https://github.com/lucidrains/rectified-flow-pytorch)** | 489 | [#3](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [1](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/lucidrains/rectified-flow-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 使 NanoFlow 逆变换在归一化流坐标中计算。 [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| **[KinPy](https://github.com/neka-nat/kinpy)** | 181 | [#2](https://api.github.com/repos/neka-nat/kinpy/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [3](https://api.github.com/repos/neka-nat/kinpy/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/neka-nat/kinpy/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正世界坐标系雅可比中的轴方向与连杆偏移。 [#29](https://github.com/neka-nat/kinpy/pull/29) |
| **[Elements](https://github.com/danijar/elements)** | 73 | [#3](https://api.github.com/repos/danijar/elements/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [2](https://api.github.com/repos/danijar/elements/commits?author=Afloat16&per_page=100&page=1) | **[2](https://github.com/danijar/elements/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留隐藏文件名，修正本地路径操作。 [#19](https://github.com/danijar/elements/pull/19) |
| **[qpmpc](https://github.com/stephane-caron/qpmpc)** | 55 | [#2](https://api.github.com/repos/stephane-caron/qpmpc/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [5](https://api.github.com/repos/stephane-caron/qpmpc/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/stephane-caron/qpmpc/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保持可选约束的缺省状态，修正目标缩放与摆模型离散化。 [#15](https://github.com/stephane-caron/qpmpc/pull/15) · [#17](https://github.com/stephane-caron/qpmpc/pull/17) |

<details>
<summary><b>更多已合并的上游贡献</b></summary>

| 项目 | 上游 ★ | 位置 · 核验日期¹ | 作者 commits² | 已合并 PR | 代表工作 |
|---|---:|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 408,869 | — | [3](https://api.github.com/repos/morluto/rea/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 安装客户端去重、补全 ZIP 读取并校验 CDP 响应编码。 [#4414](https://github.com/morluto/rea/pull/4414) · [#4524](https://github.com/morluto/rea/pull/4524) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,581 | — | [1](https://api.github.com/repos/huggingface/lerobot/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正 VLA-JEPA 训练期预测器的成对 RoPE 频率。 [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 26,880 | — | [1](https://api.github.com/repos/deepset-ai/haystack/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 隔离恢复执行计数，保持流水线快照可复用。 [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,972 | [#49](https://api.github.com/repos/recommenders-team/recommenders/contributors?per_page=100&anon=false)<br><sub>2026-10-30</sub> | [6](https://api.github.com/repos/recommenders-team/recommenders/commits?author=Afloat16&per_page=100&page=1) | **[2](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留自定义列名，拒绝无效的 top-k 参数。 [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,236 | [#51](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [3](https://api.github.com/repos/huggingface/sentence-transformers/commits?author=Afloat16&per_page=100&page=1) | **[3](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正排序梯度、编码器掩码与 float16 量化。 [#4127](https://github.com/huggingface/sentence-transformers/pull/4127) |
| **[Kornia](https://github.com/kornia/kornia)** | 11,459 | — | [2](https://api.github.com/repos/kornia/kornia/commits?author=Afloat16&per_page=100&page=1) | **[2](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保持几何计算梯度有限，稳定小根四次方程求解。 [#5517](https://github.com/kornia/kornia/pull/5517) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 8,848 | — | [1](https://api.github.com/repos/tile-ai/tilelang/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 让性能测量遵循当前 CUDA 设备选择。 [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,190 | [#95](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [1](https://api.github.com/repos/rasbt/mlxtend/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正提取出的表情符号与末尾单词的粘连。 [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,528 | [#82](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-23.json)<br><sub>2026-10-23</sub> | [1](https://api.github.com/repos/geomstats/geomstats/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将乘积度量的平行移动逐因子传递。 [#2131](https://github.com/geomstats/geomstats/pull/2131) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,408 | — | [1](https://api.github.com/repos/Denys88/rl_games/commits?author=Afloat16&per_page=100&page=1) | **[1](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 回放批次超出容量时保留最新转移样本。 [#384](https://github.com/Denys88/rl_games/pull/384) |

</details>

¹ 位置来自 GitHub 按提交数排序的贡献者列表，包含 bot、排除匿名贡献者，同数沿用 API 返回顺序。部分接口限流，因此保留并标注最近一次已核实的排名；`—` 表示具体排名未核实。² 作者 commits 是本次枚举的默认分支作者提交数，与贡献者榜单计数、已合并 PR 数口径不同。Star 与作者 commit 数截至 2026-10-30；PR 已逐条核实，GitHub 搜索索引可能滞后。[完整 PR、核验方法及数据](docs/CONTRIBUTIONS.md)。

### 由维护者整合进入默认分支的代码

**[TD-MPC2](https://github.com/nicklashansen/tdmpc2)**（993 ★，贡献榜 [#3](https://api.github.com/repos/nicklashansen/tdmpc2/contributors?per_page=100&anon=false)）：修复模型转换时 target-Q 历史和评估模式的保留。[#98](https://github.com/nicklashansen/tdmpc2/pull/98) 的实现已[保留 Afloat16 作者身份 cherry-pick](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a)；原 PR 关闭但未直接合并。连同上述仓库，共有 **25 个上游项目采纳了我的代码**。

Robotics Toolbox 通过 [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883) 整合 [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) 的圆周粒子朝向工作，并通过 [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805) 整合 [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) 的轨迹改动，保留共同作者身份。这些记录与我提交且已合并的 82 个 PR 分开统计。[详情](docs/CONTRIBUTIONS.md#other-accepted-work)。

## 我的项目

**[Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge)** · **MIT · 0.4.0 Alpha**<br>
原生发布加固：CMake 集成、PE/ELF 发布检查、受保护的 C++ 敏感内存与一次性请求授权。包含可运行示例、跨平台 CI 和研究驱动的设计。[项目故事](https://github.com/Afloat16/anti-rea-forge/blob/main/docs/community/PROJECT_STORY.md) · [参与讨论](https://github.com/Afloat16/anti-rea-forge/issues/1)。

**[ModelDock](https://github.com/Afloat16/modeldock)** · **[v0.2.0](https://github.com/Afloat16/modeldock/releases/tag/v0.2.0)**<br>
本地 3D/CAD 预览，支持超过 5 GiB 的二进制 PLY/STL 有界采样、多模型对齐与参考评价。[验证记录](https://github.com/Afloat16/modeldock/blob/main/docs/validation.md)。

### 机器人 · 大模型 · 三维重建

| 机器人 | 大模型 | 三维重建 |
|---|---|---|
| **[Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit)**<br>只读 ROS 2 SQLite/MCAP 时间戳诊断。 | **[LLM Handshake](https://github.com/Afloat16/llm-handshake)**<br>有界 OpenAI 兼容端点探测与报告对比。 | **[ReconTrail](https://github.com/Afloat16/recontrail)**<br>CPU 摄影测量、稀疏重建与离线报告。 |
| **[TF Route Audit](https://github.com/Afloat16/tf-route-audit)**<br>导出 TF 的拓扑/时间窗口检查与原生 URDF 拓扑检查。 | **[SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit)** 和 **[Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit)**<br>对已保存的流式响应与工具执行轨迹进行诊断。 | **[Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge)** 和 **[COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit)**<br>显式位姿约定转换与文本模型预检查。 |

**[Jev MCP](https://github.com/Afloat16/jev-mcp)** · [v0.5.0](https://github.com/Afloat16/jev-mcp/releases/tag/v0.5.0)：提供有界概率建议、路由与风险信号的 TypeScript MCP 服务，配有多客户端安装器。

研究与工程工作流：[Research to Fix](https://github.com/Afloat16/research-to-fix) · [Debate Direction](https://github.com/Afloat16/debate-direction) · [StewardCheck](https://github.com/Afloat16/ai-dev-steward/tree/main/tools/stewardcheck) · [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier)。

**我的工作方式：**隔离症状、明确边界、补充回归测试，并让结果可检查。[六个领域工具](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md#validation-for-this-release)在记录的发布版本中有 **67 项本地测试、36 组通过的 OS/Python CI 组合**。这些是实验性诊断与转换工具，各仓库均说明适用范围。

<details>
<summary><b>全部 15 个项目：Stars 与默认分支 commits</b></summary>

截至 **2026-10-30**，按 stars 降序，同星按仓库 commit 数降序排列。这里的 commits 是各仓库默认分支可达的历史提交数（含 merge commits），不是个人作者提交数。完整来源与版本见[项目记录](docs/PROJECTS.md)。

| 项目 | ★ | 默认分支 commits | 主要语言 |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [2](https://github.com/Afloat16/anti-rea-forge/stargazers) | [12](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [Jev MCP](https://github.com/Afloat16/jev-mcp) | [1](https://github.com/Afloat16/jev-mcp/stargazers) | [49](https://github.com/Afloat16/jev-mcp/commits/main/) | TypeScript |
| [StewardCheck](https://github.com/Afloat16/ai-dev-steward) | [1](https://github.com/Afloat16/ai-dev-steward/stargazers) | [11](https://github.com/Afloat16/ai-dev-steward/commits/main/) | Python |
| [Debate Direction](https://github.com/Afloat16/debate-direction) | [1](https://github.com/Afloat16/debate-direction/stargazers) | [8](https://github.com/Afloat16/debate-direction/commits/main/) | Python |
| [LLM Handshake](https://github.com/Afloat16/llm-handshake) | [1](https://github.com/Afloat16/llm-handshake/stargazers) | [6](https://github.com/Afloat16/llm-handshake/commits/main/) | Python |
| [Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit) | [1](https://github.com/Afloat16/bag-timeline-audit/stargazers) | [5](https://github.com/Afloat16/bag-timeline-audit/commits/main/) | Python |
| [ReconTrail](https://github.com/Afloat16/recontrail) | [1](https://github.com/Afloat16/recontrail/stargazers) | [5](https://github.com/Afloat16/recontrail/commits/main/) | Python |
| [Research to Fix](https://github.com/Afloat16/research-to-fix) | [1](https://github.com/Afloat16/research-to-fix/stargazers) | [5](https://github.com/Afloat16/research-to-fix/commits/main/) | Python |
| [SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit) | [1](https://github.com/Afloat16/sse-toolcall-audit/stargazers) | [5](https://github.com/Afloat16/sse-toolcall-audit/commits/main/) | Python |
| [TF Route Audit](https://github.com/Afloat16/tf-route-audit) | [1](https://github.com/Afloat16/tf-route-audit/stargazers) | [5](https://github.com/Afloat16/tf-route-audit/commits/main/) | Python |
| [Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit) | [1](https://github.com/Afloat16/tooltrace-audit/stargazers) | [5](https://github.com/Afloat16/tooltrace-audit/commits/main/) | Python |
| [ModelDock](https://github.com/Afloat16/modeldock) | [1](https://github.com/Afloat16/modeldock/stargazers) | [4](https://github.com/Afloat16/modeldock/commits/main/) | TypeScript |
| [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier) | [0](https://github.com/Afloat16/agent-action-notifier/stargazers) | [6](https://github.com/Afloat16/agent-action-notifier/commits/main/) | Python |
| [COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit) | [0](https://github.com/Afloat16/colmap-model-audit/stargazers) | [4](https://github.com/Afloat16/colmap-model-audit/commits/main/) | Python |
| [Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge) | [0](https://github.com/Afloat16/pose-convention-bridge/stargazers) | [4](https://github.com/Afloat16/pose-convention-bridge/commits/main/) | Python |

</details>

---

[项目指南](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.zh-CN.md) · [需求研究](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md) · [项目数据](docs/PROJECTS.md) · [贡献记录](docs/CONTRIBUTIONS.md)
