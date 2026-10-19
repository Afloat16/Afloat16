<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-light.svg" alt="Afloat16 — 机器人、大模型与三维重建" width="100%">
</picture>

[English](README.md) · [简体中文](README.zh-CN.md)

**我的研究主要围绕机器人、大模型和三维重建。**

我使用 Python、TypeScript 与 C/C++ 开发可复现的工具，开展原生软件保护实验，也为相关开源库贡献具体修复。

## 开源贡献

我为机器人、机器学习、几何与开发工具提交具体修复。截至 **2026-10-19**，已核验 **21 个上游仓库中的 66 个已合并 PR**。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/contributions-2026-10-19-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/contributions-2026-10-19-light.svg" alt="66 merged upstream PRs across 21 repositories; 14 verified top-30 contributor-list positions. Snapshot: 19 October 2026." width="100%">
</picture>

**先展示已核实提交贡献榜前 30 的项目，各组内按上游星数降序排列。** 每个 merged 数量均链接至对应仓库中我的已合并 PR。项目与改动介绍沿用英文。

### 提交贡献榜前 30 的项目

| Project | Upstream ★ | Position¹ | Merged PRs | Representative work |
|---|---:|---:|---:|---|
| **[DeepFace](https://github.com/serengil/deepface)** | 23,571 | **[#10](https://api.github.com/repos/serengil/deepface/contributors?per_page=100&anon=false)** | **[17 merged](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Face-box clipping, normalization and vector-search correctness. [#1655](https://github.com/serengil/deepface/pull/1655) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,704 | **[#9](https://api.github.com/repos/lucidrains/denoising-diffusion-pytorch/contributors?per_page=100&anon=false)** | **[1 merged](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve external conditioning and self-conditioning in 1D diffusion. [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,287 | **[#28](https://api.github.com/repos/Eigenwise/atomic-agents/contributors?per_page=100&anon=false)** | **[1 merged](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep existing chat history intact when loading fails. [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,546 | **[#6](https://api.github.com/repos/petercorke/robotics-toolbox-python/contributors?per_page=100&anon=false)** | **[11 merged](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Kinematics, dynamics, inverse kinematics and URDF correctness. [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,074 | **[#6](https://api.github.com/repos/leggedrobotics/rsl_rl/contributors?per_page=100&anon=false)** | **[2 merged](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Resume RND schedules and preserve reward-history ownership. [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,616 | **[#16](https://api.github.com/repos/pypose/pypose/contributors?per_page=100&anon=false)** | **[3 merged](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Robust-kernel numerical stability and camera-axis broadcasting. [#417](https://github.com/pypose/pypose/pull/417) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,101 | **[#3](https://api.github.com/repos/Toni-SM/skrl/contributors?per_page=100&anon=false)** | **[3 merged](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Gaussian policy math and cross-backend exploration consistency. [#475](https://github.com/Toni-SM/skrl/pull/475) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,100 | **[#3](https://api.github.com/repos/geoopt/geoopt/contributors?per_page=100&anon=false)** | **[4 merged](https://github.com/geoopt/geoopt/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Manifold constraints, gradient projection and stable geometry. [#267](https://github.com/geoopt/geoopt/pull/267) |
| **[pytransform3d](https://github.com/dfki-ric/pytransform3d)** | 707 | **[#15](https://api.github.com/repos/dfki-ric/pytransform3d/contributors?per_page=100&anon=false)** | **[2 merged](https://github.com/dfki-ric/pytransform3d/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stable Lie-group Jacobians and screw-axis translation handling. [#389](https://github.com/dfki-ric/pytransform3d/pull/389) |
| **[RoMa](https://github.com/naver/roma)** | 645 | **[#2](https://api.github.com/repos/naver/roma/contributors?per_page=100&anon=false)** | **[4 merged](https://github.com/naver/roma/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Quaternion broadcasting, affine shapes and reproducible sampling. [#33](https://github.com/naver/roma/pull/33) |
| **[Rectified Flow](https://github.com/lucidrains/rectified-flow-pytorch)** | 488 | **[#3](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/contributors?per_page=100&anon=false)** | **[1 merged](https://github.com/lucidrains/rectified-flow-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep NanoFlow inversion in normalized flow coordinates. [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| **[KinPy](https://github.com/neka-nat/kinpy)** | 182 | **[#2](https://api.github.com/repos/neka-nat/kinpy/contributors?per_page=100&anon=false)** | **[3 merged](https://github.com/neka-nat/kinpy/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | World-frame Jacobians with consistent axes and link offsets. [#29](https://github.com/neka-nat/kinpy/pull/29) |
| **[Elements](https://github.com/danijar/elements)** | 73 | **[#3](https://api.github.com/repos/danijar/elements/contributors?per_page=100&anon=false)** | **[2 merged](https://github.com/danijar/elements/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve hidden filenames and correct local-path operations. [#19](https://github.com/danijar/elements/pull/19) |
| **[qpmpc](https://github.com/stephane-caron/qpmpc)** | 55 | **[#2](https://api.github.com/repos/stephane-caron/qpmpc/contributors?per_page=100&anon=false)** | **[1 merged](https://github.com/stephane-caron/qpmpc/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve absent state constraints in receding-horizon updates. [#15](https://github.com/stephane-caron/qpmpc/pull/15) |

### 更多已合并的上游贡献

| Project | Upstream ★ | Merged PRs | Representative work |
|---|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 331,627 | **[1 merged](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Deduplicate selected clients before generating setup plans. [#3919](https://github.com/morluto/rea/pull/3919) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 26,773 | **[1 merged](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep pipeline snapshots reusable after a resumed run. [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,957 | **[2 merged](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve custom columns and reject invalid top-k values. [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,192 | **[3 merged](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Ranking gradients, encoder masks and float16 quantization. [#4127](https://github.com/huggingface/sentence-transformers/pull/4127) |
| **[Kornia](https://github.com/kornia/kornia)** | 11,435 | **[2 merged](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Finite geometry gradients and stable small-root quartics. [#5517](https://github.com/kornia/kornia/pull/5517) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,187 | **[1 merged](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Separate extracted emoticons from the preceding final word. [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,525 | **[1 merged](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Propagate product-metric parallel transport to each factor. [#2131](https://github.com/geomstats/geomstats/pull/2131) |

¹ Position 是 GitHub 按提交贡献数排序后的贡献者列表位置，**不是 PR 数量排名或维护者身份**；提交数相同时沿用 GitHub 返回顺序。星数和位置均为日期快照。第二组包含未核实进入前 30 的仓库，不推测其具体排名。[全部 66 个 PR、提交数与核验方法](docs/CONTRIBUTIONS.md)。

## 我维护的项目

| 方向 | 项目与用途 |
|---|---|
| Software protection | **[Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge)** — Open research on native software protection against AI reverse engineering, with CMake/C++, PE/ELF release gates, and reproducible experiments. [Contributions welcome](https://github.com/Afloat16/anti-rea-forge/issues/1). |
| 三维重建 | [ReconTrail](https://github.com/Afloat16/recontrail)：CPU摄影测量与离线报告；[COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit)：传统文本模型预检；[Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge)：明确相机位姿约定后转换。 |
| 机器人 | [Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit)：ROS 2录包时间检查；[TF Route Audit](https://github.com/Afloat16/tf-route-audit)：导出TF/URDF拓扑和观测时间范围。 |
| 大模型 | [LLM Handshake](https://github.com/Afloat16/llm-handshake)：有界接口探测；[SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit)：保存的流式响应审计；[Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit)：真实工具尝试记录审计。 |
| 工程工作流 | [Research to Fix](https://github.com/Afloat16/research-to-fix)：调研与本地验证；[Debate Direction](https://github.com/Afloat16/debate-direction)：需求论证；[StewardCheck](https://github.com/Afloat16/ai-dev-steward/tree/main/tools/stewardcheck)：任务验收；[Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier)：等待输入时提醒。 |

[完整项目导航](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.zh-CN.md)说明安装、适用场景和边界。六个领域工具在所记录版本中合计67项本地测试、36组跨平台CI通过，均为实验性诊断或转换工具，不代表全部协议认证或上游问题已解决。
