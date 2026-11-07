<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-light.svg?v=2" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

**我的研究主要围绕机器人、大模型和三维重建。**

我开发可复现的研究工具，开展原生软件保护实验，并为相关开源库贡献具体修复。

Python · TypeScript · C/C++ · 可复现实验 · 上游工程

[我的项目](#我的项目) · [开源贡献](#开源贡献) · [English](README.md)

</div>

## 开源贡献

截至 **2026-11-07 22:37（UTC+8）**，已核验我向 **32 个上游仓库**提交且已合并的 **154 个 PR**，涉及机器人、机器学习、几何与开发工具。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-07-2237-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-07-2237-light.svg?v=2" alt="截至 2026-11-07 22:37（UTC+8）：154 个已核验的上游合并 PR，覆盖 32 个仓库。" width="100%">
</picture>

主页贡献列表仅展示 **star 不少于 1,000** 的项目；上方合并总数包含所有已核实的作者合并 PR，不设星数门槛。

### 近期精选已合并贡献

**6 个项目，每个项目一行**，精选体现程序分析、构建状态管理、数值正确性与数据处理能力的互补贡献。每个 PR 均已核实由 Afloat16 提交且被上游合并；项目按其最近一条精选贡献的合并时间排序，日期使用 Asia/Shanghai。[技术细节与范围](docs/CONTRIBUTIONS.md#selected-merges-by-project)。

| 最近精选合并 | 上游项目 · ★ | 代表性工程贡献 | PR / 合并提交 |
|---|---|---|---|
| 2026-11-06 | **[REA](https://github.com/morluto/rea)**<br>439,835 ★ | 补全 ZIP 短读并检测提前 EOF；在受字节限额约束的诊断输出中保留 UTF-8 码点边界。 | [#4414](https://github.com/morluto/rea/pull/4414) · [`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33)<br>[#8907](https://github.com/morluto/rea/pull/8907) · [`3eff806`](https://github.com/morluto/rea/commit/3eff8065e757c6e3bab96d164abfceafd340e6d1) |
| 2026-11-04 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>19,725 ★ | 持久化跨运行重建进度；修正二进制解析边界与损坏文件恢复；按语义绑定恢复压缩 esbuild 模块依赖。 | [#557](https://github.com/storytold/craft-anything/pull/557) · [`48759fb`](https://github.com/storytold/craft-anything/commit/48759fb5fccde45405c2db29d162ac55edbc6562)<br>[#766](https://github.com/storytold/craft-anything/pull/766) · [`eab6a0f`](https://github.com/storytold/craft-anything/commit/eab6a0f01bf9fc3a36798d322e4442e169394dfc)<br>[#438](https://github.com/storytold/craft-anything/pull/438) · [`89bcd06`](https://github.com/storytold/craft-anything/commit/89bcd061905de0f43e1dab161535fa4439ceb622) |
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,173 ★ | 通过数值稳健的向量归一化，使基准评估中的平移方向角误差不受重建尺度影响。 | [#4932](https://github.com/colmap/colmap/pull/4932) · [`27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd) |
| 2026-11-02 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,266 ★ | 保留排序损失梯度，稳定 FP16 标量量化，并保持 LSTM 填充输出与 token 特征对齐。 | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [`abd266f`](https://github.com/huggingface/sentence-transformers/commit/abd266f29c7135e7ab9ccd3a41dfa74456b40c20)<br>[#4113](https://github.com/huggingface/sentence-transformers/pull/4113) · [`847abf6`](https://github.com/huggingface/sentence-transformers/commit/847abf6e6f2187159d699c0001af2bb1f65e1f18)<br>[#4301](https://github.com/huggingface/sentence-transformers/pull/4301) · [`26a0f49`](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c) |
| 2026-11-01 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,655 ★ | 统一 Milvus 与 DeepFace 的距离语义，完整读取图库，并保持空、单图和多图批次的返回结构。 | [#1634](https://github.com/serengil/deepface/pull/1634) · [`bf5ed73`](https://github.com/serengil/deepface/commit/bf5ed7339a0d430cbd214e4923ee6a694f808dec)<br>[#1649](https://github.com/serengil/deepface/pull/1649) · [`5696e33`](https://github.com/serengil/deepface/commit/5696e3313ffdf6d51cd67f38a9da88ccd58ebb5e)<br>[#1675](https://github.com/serengil/deepface/pull/1675) · [`8e565c0`](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,731 ★ | 将 V-JEPA 2 已有的成对 RoPE 修正应用于 VLA-JEPA 训练期世界预测器。 | [#4835](https://github.com/huggingface/lerobot/pull/4835) · [`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |

### 最新核实的贡献榜前 30

**13 个展示中的上游项目在本次核实的 GitHub Contributors 图榜中位列前 30**。排名均于 **2026-11-07** 读取，统一使用 **All / Commits / 默认分支 / 排除 merge commit**；各组按最近核实的 star 降序排列。

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[DeepFace](https://github.com/serengil/deepface)** | 23,655 | [#4](https://github.com/serengil/deepface/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[24](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正人脸裁剪边界、归一化与向量检索行为。 [#1655](https://github.com/serengil/deepface/pull/1655) · [#1658](https://github.com/serengil/deepface/pull/1658) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 19,725 | [#2](https://github.com/storytold/craft-anything/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[34](https://github.com/storytold/craft-anything/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将 Unity 六种浮点纹理布局导出为 8 位 PNG，并将被拒绝的 pcapng 包计入扫描预算。 [#1088](https://github.com/storytold/craft-anything/pull/1088) · [#1091](https://github.com/storytold/craft-anything/pull/1091) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,266 | [#28](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[6](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 排序梯度、FP16 量化与正确处理填充的 CNN/LSTM 编码。 [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) · [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,723 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留一维扩散中的外部条件与自条件。 [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[ThinkRail](https://github.com/JetBrains/thinkrail)** | 7,893 | [#17](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[3](https://github.com/JetBrains/thinkrail/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按 XML 根元素识别 SVG，并在截断终端输出时保留 UTF-16 代理对。 [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [#1186](https://github.com/JetBrains/thinkrail/pull/1186) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,342 | [#9](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[3](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | NT-Xent 损失与梯度数值稳定性，以及 HistogramLoss、PNP 的独立回归验证。 [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) · [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,320 | [#23](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 加载失败时保留已有对话历史。 [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,567 | [#7](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[11](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正运动学、动力学、逆运动学与 URDF 处理。 [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,123 | [#4](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复 RND 调度进度，保持奖励历史独立并保留 rollout 尾批样本。 [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,621 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 最小二乘刚体配准、鲁棒核稳定性与相机参数广播。 [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,411 | [#7](https://github.com/Denys88/rl_games/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[4](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 回放批次超出容量时保留最新转移样本。 [#384](https://github.com/Denys88/rl_games/pull/384) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,105 | [#4](https://github.com/Toni-SM/skrl/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[3](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正高斯策略计算，保持跨后端探索行为一致。 [#475](https://github.com/Toni-SM/skrl/pull/475) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,104 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[13](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 修正 canonical Stiefel 切向量投影、Cayley 初始速度与线搜索导数，保持流形优化的正确性。 [#280](https://github.com/geoopt/geoopt/pull/280) · [#267](https://github.com/geoopt/geoopt/pull/267) |

### 更多已合并的上游贡献

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 439,835 | [#65](https://github.com/morluto/rea/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[6](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 补全 ZIP 短读并检测提前 EOF；在受字节限额约束的诊断输出中保留 UTF-8 码点边界。 [#4414](https://github.com/morluto/rea/pull/4414) · [#8907](https://github.com/morluto/rea/pull/8907) |
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** | 114,275 | [#52](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[4](https://github.com/thedotmack/claude-mem/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保持跨分块 SSE 帧解析正确，并在翻译 README、重写链接时保留代码示例。 [#5367](https://github.com/thedotmack/claude-mem/pull/5367) · [#5458](https://github.com/thedotmack/claude-mem/pull/5458) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,731 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正 VLA-JEPA 训练期预测器的成对 RoPE 频率。 [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 26,942 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 隔离恢复执行计数，保持流水线快照可复用。 [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,981 | [#46](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[3](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 k-core 过滤与分层划分中保留自定义输入列；#2419 合并至 `staging`。 [#2389](https://github.com/recommenders-team/recommenders/pull/2389) · [#2419](https://github.com/recommenders-team/recommenders/pull/2419) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,173 | [#49](https://github.com/colmap/colmap/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[2](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 平移方向角误差的尺度不变性与基准运行路径解析。 [#4932](https://github.com/colmap/colmap/pull/4932) · [#4931](https://github.com/colmap/colmap/pull/4931) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,352 | [#85](https://github.com/kornia/kornia/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[6](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 以 FP32 累加加权半精度指标，并在不改变通道布局的前提下将 BF16 图像导出到 NumPy。 [#6580](https://github.com/kornia/kornia/pull/6580) · [#6582](https://github.com/kornia/kornia/pull/6582) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 8,924 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 让性能测量遵循当前 CUDA 设备选择。 [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[openMVG](https://github.com/openMVG/openMVG)** | 6,590 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/openMVG/openMVG/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按各观测视线方向判断 DLT 三角化点的深度，保留球面相机后半球的有效观测。 [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,191 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正提取出的表情符号与末尾单词的粘连。 [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,719 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正非均匀权重的 Procrustes 旋转，保留等权重拟合；合并至 `release/angles`。 [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Manifold](https://github.com/elalish/manifold)** | 2,395 | [—](https://github.com/elalish/manifold/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/elalish/manifold/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 使静态凸包构造独立于输入的执行上下文，并保留已物化的操作数错误。 [#1905](https://github.com/elalish/manifold/pull/1905) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,529 | [#83](https://github.com/geomstats/geomstats/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | **[1](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将乘积度量的平行移动逐因子传递。 [#2131](https://github.com/geomstats/geomstats/pull/2131) |

¹ 排名使用 **2026-11-07** 从 GitHub 官方 Contributors 图榜直接读取的名次，与上次快照使用相同图榜设置。更早的 REST 结果保留于完整记录，不能直接视为同一榜单的升降。`—` 表示已完整检查所显示的前 100 名，未找到 Afloat16；它不代表精确名次或零贡献。GitHub 图表计算可能存在缓存。图榜计数、默认分支作者 commit 和已合并 PR 分别统计。[完整记录、统计口径与数据](docs/CONTRIBUTIONS.md)。

### 由维护者整合进入默认分支的代码

Robotics Toolbox 也将 [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) 的粒子航向角环形统计修复整合进 [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883)，并将 [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) 的轨迹工作整合进 [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805)，保留共同作者署名。这些采纳与 154 个作者直接合并 PR 分开记录。[详情](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Craft Anything](https://github.com/storytold/craft-anything)** 通过 **10 次维护者整合**采纳了我 **94 个原始 PR** 的工作。最新的 [#986](https://github.com/storytold/craft-anything/pull/986) 整合了 32 个解析器修复 PR，[#995](https://github.com/storytold/craft-anything/pull/995) 采纳了原子写入与 HTTP 回放的两个提案。后者的合并提交遗漏共同作者署名，维护者随后在单独的文档提交 [#1012](https://github.com/storytold/craft-anything/pull/1012) 补记，不额外计为一次代码采纳。[10 次整合及其来源](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Claude-Mem](https://github.com/thedotmack/claude-mem)** 将 [#5339](https://github.com/thedotmack/claude-mem/pull/5339) 的非法输入回归案例采纳进 [#5336](https://github.com/thedotmack/claude-mem/pull/5336)，保留我的共同作者署名。被采纳的部分是拒绝测试，生产代码中的数字字符串转换由另一位 PR 作者实现；此项与我的四个直接合并 PR 分开记录。[证据](docs/CONTRIBUTIONS.md#other-accepted-work)。

## 我的项目

**[Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge)** · **MIT · 0.6.0 Alpha**<br>
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

截至 **2026-11-07 22:37（UTC+8）**，按 stars 降序，同星按仓库 commit 数降序排列。这里的 commits 是各仓库默认分支可达的历史提交数（含 merge commits），不是个人作者提交数。完整来源与版本见[项目记录](docs/PROJECTS.md)。

| 项目 | ★ | 默认分支 commits | 主要语言 |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [4](https://github.com/Afloat16/anti-rea-forge/stargazers) | [19](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [Jev MCP](https://github.com/Afloat16/jev-mcp) | [1](https://github.com/Afloat16/jev-mcp/stargazers) | [49](https://github.com/Afloat16/jev-mcp/commits/main/) | TypeScript |
| [StewardCheck](https://github.com/Afloat16/ai-dev-steward) | [1](https://github.com/Afloat16/ai-dev-steward/stargazers) | [11](https://github.com/Afloat16/ai-dev-steward/commits/main/) | Python |
| [Debate Direction](https://github.com/Afloat16/debate-direction) | [1](https://github.com/Afloat16/debate-direction/stargazers) | [8](https://github.com/Afloat16/debate-direction/commits/main/) | Python |
| [Research to Fix](https://github.com/Afloat16/research-to-fix) | [1](https://github.com/Afloat16/research-to-fix/stargazers) | [7](https://github.com/Afloat16/research-to-fix/commits/main/) | Python |
| [LLM Handshake](https://github.com/Afloat16/llm-handshake) | [1](https://github.com/Afloat16/llm-handshake/stargazers) | [6](https://github.com/Afloat16/llm-handshake/commits/main/) | Python |
| [ModelDock](https://github.com/Afloat16/modeldock) | [1](https://github.com/Afloat16/modeldock/stargazers) | [6](https://github.com/Afloat16/modeldock/commits/main/) | TypeScript |
| [Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit) | [1](https://github.com/Afloat16/bag-timeline-audit/stargazers) | [5](https://github.com/Afloat16/bag-timeline-audit/commits/main/) | Python |
| [ReconTrail](https://github.com/Afloat16/recontrail) | [1](https://github.com/Afloat16/recontrail/stargazers) | [5](https://github.com/Afloat16/recontrail/commits/main/) | Python |
| [SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit) | [1](https://github.com/Afloat16/sse-toolcall-audit/stargazers) | [5](https://github.com/Afloat16/sse-toolcall-audit/commits/main/) | Python |
| [TF Route Audit](https://github.com/Afloat16/tf-route-audit) | [1](https://github.com/Afloat16/tf-route-audit/stargazers) | [5](https://github.com/Afloat16/tf-route-audit/commits/main/) | Python |
| [Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit) | [1](https://github.com/Afloat16/tooltrace-audit/stargazers) | [5](https://github.com/Afloat16/tooltrace-audit/commits/main/) | Python |
| [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier) | [0](https://github.com/Afloat16/agent-action-notifier/stargazers) | [6](https://github.com/Afloat16/agent-action-notifier/commits/main/) | Python |
| [COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit) | [0](https://github.com/Afloat16/colmap-model-audit/stargazers) | [4](https://github.com/Afloat16/colmap-model-audit/commits/main/) | Python |
| [Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge) | [0](https://github.com/Afloat16/pose-convention-bridge/stargazers) | [4](https://github.com/Afloat16/pose-convention-bridge/commits/main/) | Python |

</details>

---

[项目指南](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.zh-CN.md) · [需求研究](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md) · [项目数据](docs/PROJECTS.md) · [贡献记录](docs/CONTRIBUTIONS.md)
