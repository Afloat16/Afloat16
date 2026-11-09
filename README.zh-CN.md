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

截至 **2026-11-09 20:33（UTC+8）**，已核验我向 **33 个上游仓库**提交且已合并的 **231 个 PR**，涉及机器人、机器学习、几何与开发工具。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-09-2033-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-09-2033-light.svg?v=2" alt="截至 2026-11-09 20:33（UTC+8）：231 个已核验的上游合并 PR，覆盖 33 个仓库。" width="100%">
</picture>

主页贡献列表仅展示 **star 不少于 1,000** 的项目；上方合并总数包含所有已核实的作者合并 PR，不设星数门槛。

### 近期精选已合并贡献

**6 个项目，每个项目一行。** 每个项目最多选 3 个由我提交、近 7 天内获上游合并的 PR，按解决的问题、实际合入的代码和回归测试筛选。项目按最近一项精选贡献的合并时间排序，日期使用北京时间。[技术细节与范围](docs/CONTRIBUTIONS.md#selected-merges-by-project)。

| 最近精选合并 | 上游项目 · ★ | 代表性工程贡献 | PR / 合并提交 |
|---|---|---|---|
| 2026-11-09 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>23,755 ★ | 在统一输出上限内解码连续的 Zstandard 帧，识别确实拒绝转账的 EVM 分发逻辑，并按文件系统声明的边界恢复数据。 | [#1340](https://github.com/storytold/craft-anything/pull/1340) · [`25a8f17`](https://github.com/storytold/craft-anything/commit/25a8f179f8b6b7730bc138fa8633180323c5d11c)<br>[#1323](https://github.com/storytold/craft-anything/pull/1323) · [`3f7b9a3`](https://github.com/storytold/craft-anything/commit/3f7b9a36158f7f732254051c0cc2df7832aec8d3)<br>[#1246](https://github.com/storytold/craft-anything/pull/1246) · [`b9a3525`](https://github.com/storytold/craft-anything/commit/b9a352542b640a78eaf3b63abf0409e8b399079c) |
| 2026-11-09 | **[Claude-Mem](https://github.com/thedotmack/claude-mem)**<br>115,178 ★ | 备份轮换时保留已选的恢复点，区分短哈希碰撞的文件版本，并保证重试的 PostgreSQL 写入幂等。 | [#5532](https://github.com/thedotmack/claude-mem/pull/5532) · [`5ce4b19`](https://github.com/thedotmack/claude-mem/commit/5ce4b19e00f40e7023b75a9dee8e49467f998852)<br>[#5536](https://github.com/thedotmack/claude-mem/pull/5536) · [`e15d466`](https://github.com/thedotmack/claude-mem/commit/e15d46675bde9059d591baea2a95400b94034d57)<br>[#5538](https://github.com/thedotmack/claude-mem/pull/5538) · [`5047f2b`](https://github.com/thedotmack/claude-mem/commit/5047f2b0f213eb42a738b4a2721cd310a92d0e67) |
| 2026-11-08 | **[skrl](https://github.com/Toni-SM/skrl)**<br>1,105 ★ | 在多进程间正确归约非连续 PyTorch 梯度，并将 JAX 工作进程的失败状态传回启动器。 | [#489](https://github.com/Toni-SM/skrl/pull/489) · [`0c4d777`](https://github.com/Toni-SM/skrl/commit/0c4d7771f88b21070457afd03e558bbee17c4ec5)<br>[#496](https://github.com/Toni-SM/skrl/pull/496) · [`34a926b`](https://github.com/Toni-SM/skrl/commit/34a926be7486ada0a06df274a5aaca6930136e54) |
| 2026-11-07 | **[openMVG](https://github.com/openMVG/openMVG)**<br>6,593 ★ | 沿各自的观测射线判断深度，使球面相机三角测量能保留后半球的有效三维点。 | [#2445](https://github.com/openMVG/openMVG/pull/2445) · [`5f84739`](https://github.com/openMVG/openMVG/commit/5f84739844e8bc6aba243128498ff44910f60b66) |
| 2026-11-07 | **[Kornia](https://github.com/kornia/kornia)**<br>12,361 ★ | 将增强流水线注册为 PyTorch 子模块，使状态可随检查点保存和恢复，并用 FP32 累积半精度指标。 | [#6449](https://github.com/kornia/kornia/pull/6449) · [`b985896`](https://github.com/kornia/kornia/commit/b985896b72bf82eb98ae4bef573487bc922ebbc3)<br>[#6580](https://github.com/kornia/kornia/pull/6580) · [`1c52e60`](https://github.com/kornia/kornia/commit/1c52e60146fbd1ff53dc4611600a06b53919d4e8) |
| 2026-11-05 | **[Geoopt](https://github.com/geoopt/geoopt)**<br>1,104 ★ | 修正典范 Stiefel 流形的切空间投影和 Wolfe 线搜索导数，并让欧氏范数与距离沿全部流形维度计算。 | [#280](https://github.com/geoopt/geoopt/pull/280) · [`c9f86dd`](https://github.com/geoopt/geoopt/commit/c9f86dd03d0a51d329f3a51f004f5380843680c6)<br>[#278](https://github.com/geoopt/geoopt/pull/278) · [`d2121d5`](https://github.com/geoopt/geoopt/commit/d2121d557d4d212894349475c2d46c0cd7834ae4) |

### 最新核实的贡献榜前 30

**15 个展示中的上游项目在本次核实的 GitHub Contributors 图榜中位列前 30**。排名均于 **2026-11-09** 读取，统一使用 **All / Commits / 默认分支 / 排除 merge commit**；各组按最近核实的 star 降序排列。

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** | 115,178 | [#16](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[15](https://github.com/thedotmack/claude-mem/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在待恢复标记清除前保留已选定的备份。[#5532](https://github.com/thedotmack/claude-mem/pull/5532) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 23,755 | [#2](https://github.com/storytold/craft-anything/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[86](https://github.com/storytold/craft-anything/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 完整解码连续的 Zstandard 帧，并对总输出统一限额。[#1340](https://github.com/storytold/craft-anything/pull/1340) |
| **[DeepFace](https://github.com/serengil/deepface)** | 23,662 | [#4](https://github.com/serengil/deepface/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[25](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 NumPy 切片前裁剪人脸框，并在 HTTP 表单请求中正确解析值为 false 的选项。 [#1655](https://github.com/serengil/deepface/pull/1655) · [#1684](https://github.com/serengil/deepface/pull/1684) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,269 | [#28](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[6](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 排序梯度、FP16 量化与正确处理填充的 CNN/LSTM 编码。 [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) · [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,183 | [#28](https://github.com/colmap/colmap/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[5](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正使用相对路径时的 IMC 2024 数据集布局，并在切换子进程目录前解析基准路径。 [#4976](https://github.com/colmap/colmap/pull/4976) · [#4931](https://github.com/colmap/colmap/pull/4931) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,724 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留一维扩散中的外部条件与自条件。 [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[ThinkRail](https://github.com/JetBrains/thinkrail)** | 8,030 | [#14](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[3](https://github.com/JetBrains/thinkrail/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按 XML 根元素识别 SVG，并在截断终端输出时保留 UTF-16 代理对。 [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [#1186](https://github.com/JetBrains/thinkrail/pull/1186) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,342 | [#5](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[8](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 类别加权损失先以 FP32 归约再转回输入类型；半精度中心正则损失则保持 FP32。 [#775](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/775) · [#776](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/776) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,321 | [#23](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 加载失败时保留已有对话历史。 [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,570 | [#7](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[11](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正运动学、动力学、逆运动学与 URDF 处理。 [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,124 | [#4](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复 RND 调度进度，保持奖励历史独立并保留 rollout 尾批样本。 [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,621 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 最小二乘刚体配准、鲁棒核稳定性与相机参数广播。 [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,411 | [#7](https://github.com/Denys88/rl_games/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[4](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 回放批次超出容量时保留最新转移样本。 [#384](https://github.com/Denys88/rl_games/pull/384) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,105 | [#3](https://github.com/Toni-SM/skrl/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[5](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 归约 PyTorch 工作进程中非连续布局的梯度，并将 JAX 工作进程的失败状态传回启动器。 [#489](https://github.com/Toni-SM/skrl/pull/489) · [#496](https://github.com/Toni-SM/skrl/pull/496) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,104 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[13](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 修正 canonical Stiefel 切向量投影、Cayley 初始速度与线搜索导数，保持流形优化的正确性。 [#280](https://github.com/geoopt/geoopt/pull/280) · [#267](https://github.com/geoopt/geoopt/pull/267) |

### 更多已合并的上游贡献

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 445,495 | [#59](https://github.com/morluto/rea/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[6](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 补全 ZIP 短读并检测提前 EOF；在受字节限额约束的诊断输出中保留 UTF-8 码点边界。 [#4414](https://github.com/morluto/rea/pull/4414) · [#8907](https://github.com/morluto/rea/pull/8907) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,772 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正 VLA-JEPA 训练期预测器的成对 RoPE 频率。 [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 26,951 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 隔离恢复执行计数，保持流水线快照可复用。 [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,984 | [#46](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[3](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 k-core 过滤与分层划分中保留自定义输入列；#2419 合并至 `staging`。 [#2389](https://github.com/recommenders-team/recommenders/pull/2389) · [#2419](https://github.com/recommenders-team/recommenders/pull/2419) |
| **[CARLA](https://github.com/carla-simulator/carla)** | 14,581 | [#81](https://github.com/carla-simulator/carla/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[3](https://github.com/carla-simulator/carla/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正文档中 4×4 位姿的坐标系变换公式，区分深度相机原始编码精度与灰度可视化精度。 [#10188](https://github.com/carla-simulator/carla/pull/10188) · [#10189](https://github.com/carla-simulator/carla/pull/10189) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,361 | [#85](https://github.com/kornia/kornia/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[6](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 以 FP32 累加加权半精度指标，并在不改变通道布局的前提下将 BF16 图像导出到 NumPy。 [#6580](https://github.com/kornia/kornia/pull/6580) · [#6582](https://github.com/kornia/kornia/pull/6582) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 8,933 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 让性能测量遵循当前 CUDA 设备选择。 [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[openMVG](https://github.com/openMVG/openMVG)** | 6,593 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/openMVG/openMVG/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按各观测视线方向判断 DLT 三角化点的深度，保留球面相机后半球的有效观测。 [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,192 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正提取出的表情符号与末尾单词的粘连。 [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,719 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正非均匀权重的 Procrustes 旋转，保留等权重拟合；合并至 `release/angles`。 [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Manifold](https://github.com/elalish/manifold)** | 2,400 | [#76](https://github.com/elalish/manifold/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/elalish/manifold/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 使静态凸包构造独立于输入的执行上下文，并保留已物化的操作数错误。 [#1905](https://github.com/elalish/manifold/pull/1905) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,529 | [#83](https://github.com/geomstats/geomstats/graphs/contributors?all=1)<br><sub>2026-11-09</sub> | **[1](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将乘积度量的平行移动逐因子传递。 [#2131](https://github.com/geomstats/geomstats/pull/2131) |

¹ 排名使用 **2026-11-09** 从 GitHub 官方 Contributors 图榜直接读取的名次，与上次快照使用相同图榜设置。更早的 REST 结果保留于完整记录，不能直接视为同一榜单的升降。`—` 表示已完整检查所显示的前 100 名，未找到 Afloat16；它不代表精确名次或零贡献。GitHub 图表计算可能存在缓存。图榜计数、默认分支作者 commit 和已合并 PR 分别统计。[完整记录、统计口径与数据](docs/CONTRIBUTIONS.md)。

### 由维护者整合进入默认分支的代码

Robotics Toolbox 也将 [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) 的粒子航向角环形统计修复整合进 [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883)，并将 [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) 的轨迹工作整合进 [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805)，保留共同作者署名。这些采纳与 231 个作者直接合并 PR 分开记录。[详情](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Craft Anything](https://github.com/storytold/craft-anything)** 通过 **11 次维护者整合**采纳了我 **101 个原始 PR** 的工作。最新的 [#1217](https://github.com/storytold/craft-anything/pull/1217) 整合了 7 个有关文件格式解析与项目启动的改动，并保留共同作者署名。此前 [#995](https://github.com/storytold/craft-anything/pull/995) 的合并提交遗漏署名，维护者在单独的文档提交 [#1012](https://github.com/storytold/craft-anything/pull/1012) 补记。[11 次整合及其来源](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Claude-Mem](https://github.com/thedotmack/claude-mem)** 将 [#5339](https://github.com/thedotmack/claude-mem/pull/5339) 的非法输入回归案例采纳进 [#5336](https://github.com/thedotmack/claude-mem/pull/5336)，保留我的共同作者署名。被采纳的部分是拒绝测试，生产代码中的数字字符串转换由另一位 PR 作者实现；此项与我的 15 个直接合并 PR 分开记录。[证据](docs/CONTRIBUTIONS.md#other-accepted-work)。

## 我的项目

**[Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge)** · **MIT · 0.8.0**<br>
原生应用只嵌入公开的 SHA-256 校验值，256 位解锁令牌由签发方单独交付。仓库提供可复现的 Ghidra 提取与重放实验。[项目故事](https://github.com/Afloat16/anti-rea-forge/blob/main/docs/community/PROJECT_STORY.md) · [参与讨论](https://github.com/Afloat16/anti-rea-forge/issues/1)。

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

截至 **2026-11-09 20:24（UTC+8）**，按 stars 降序，同星按仓库 commit 数降序排列。这里的 commits 是各仓库默认分支可达的历史提交数（含 merge commits），不是个人作者提交数。完整来源与版本见[项目记录](docs/PROJECTS.md)。

| 项目 | ★ | 默认分支 commits | 主要语言 |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [6](https://github.com/Afloat16/anti-rea-forge/stargazers) | [28](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
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
