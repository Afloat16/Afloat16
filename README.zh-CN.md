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

截至 **2026-11-14 13:48（UTC+8）**，已核验我向 **39 个上游仓库**提交且已合并的 **881 个 PR**，涉及机器人、机器学习、几何与开发工具。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-14-1348-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-14-1348-light.svg?v=2" alt="截至 2026-11-14 13:48（UTC+8）：881 个已核验的上游合并 PR，覆盖 39 个仓库。" width="100%">
</picture>

主页贡献列表仅展示 **star 超过 1,000** 的项目；上方合并总数包含所有已核实的作者合并 PR，不设星数门槛。

### 近期精选已合并贡献

**7 个项目，每个项目一行。** 从各项目近期已合并的贡献中，按实际工程价值和回归测试精选 1–3 个代表 PR。项目按最近一项精选贡献的合并时间排序，日期使用北京时间。[技术细节与范围](docs/CONTRIBUTIONS.md#selected-merges-by-project)。

| 最近精选合并 | 上游项目 · ★ | 代表性工程贡献 | PR / 合并提交 |
|---|---|---|---|
| 2026-11-10 | **[Claude-Mem](https://github.com/thedotmack/claude-mem)**<br>116,895 ★ | 以行锁协调并发生成任务的重试与取消，在替换现有数据前拒绝不兼容的恢复快照，并在远端删除提交后有序清理副本向量。 | [#5650](https://github.com/thedotmack/claude-mem/pull/5650) · [`e7978b0`](https://github.com/thedotmack/claude-mem/commit/e7978b0fcd6880819a0df55d7d61fd1818de4af9)<br>[#5649](https://github.com/thedotmack/claude-mem/pull/5649) · [`c141e54`](https://github.com/thedotmack/claude-mem/commit/c141e5416b18070b445c5c84fb6c1c9676106ef9)<br>[#5647](https://github.com/thedotmack/claude-mem/pull/5647) · [`d58a11d`](https://github.com/thedotmack/claude-mem/commit/d58a11df4755df02881345ec47d9712e673f2ebd) |
| 2026-11-10 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>31,645 ★ | 在安装写入前拒绝不完整的 GNU tar 元数据，限制 Node SEA 元数据保留量，并从节区不完整的 ELF 中恢复动态导入与导出。 | [#1402](https://github.com/storytold/craft-anything/pull/1402) · [`2174cac`](https://github.com/storytold/craft-anything/commit/2174cac80b3616524f2062fbaa6c37d40aea34e8)<br>[#1377](https://github.com/storytold/craft-anything/pull/1377) · [`ee73141`](https://github.com/storytold/craft-anything/commit/ee73141313d66905e6e715e70f592b1f00fbc8ed)<br>[#1367](https://github.com/storytold/craft-anything/pull/1367) · [`a5ea19c`](https://github.com/storytold/craft-anything/commit/a5ea19cf10ef6d04d209f1a372e1a1c3a3bc93eb) |
| 2026-11-09 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,698 ★ | 保留完整 S3 对象键并释放响应流，校验 FTP 端点与连接清理，并复用已解码图像以支持单次读取的查询输入。 | [#1686](https://github.com/serengil/deepface/pull/1686) · [`00e4fae`](https://github.com/serengil/deepface/commit/00e4faece225737d89c32b171fa57905053eb1eb)<br>[#1685](https://github.com/serengil/deepface/pull/1685) · [`e7734e1`](https://github.com/serengil/deepface/commit/e7734e1d7cdd461a3b7ad945841409449ca31872)<br>[#1701](https://github.com/serengil/deepface/pull/1701) · [`a2d66b2`](https://github.com/serengil/deepface/commit/a2d66b2bb691ba79752aee7ae099069df5a43173) |
| 2026-11-09 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,221 ★ | 修复 Python 3 图像采集、有限重试与响应资源释放，并让平移夹角评估不受重建尺度影响。 | [#4977](https://github.com/colmap/colmap/pull/4977) · [`9f0736e`](https://github.com/colmap/colmap/commit/9f0736e90c2d7e10315ef4e4c62688d8f32fa8d4)<br>[#4932](https://github.com/colmap/colmap/pull/4932) · [`27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd) |
| 2026-11-06 | **[REA](https://github.com/morluto/rea)**<br>458,060 ★ | 保留截断诊断输出中的完整 UTF-8 字符，在迭代中断后继续处理完整 NDJSON 消息，并在有界读取完成时响应取消。 | [#8907](https://github.com/morluto/rea/pull/8907) · [`3eff806`](https://github.com/morluto/rea/commit/3eff8065e757c6e3bab96d164abfceafd340e6d1)<br>[#8909](https://github.com/morluto/rea/pull/8909) · [`a3621e5`](https://github.com/morluto/rea/commit/a3621e5e1f73755d927dd97861ab4216cabf4787)<br>[#8908](https://github.com/morluto/rea/pull/8908) · [`b153ba8`](https://github.com/morluto/rea/commit/b153ba8ddd5bf13cbc6ba74009eca290686adbca) |
| 2026-11-05 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,285 ★ | 在 CNN 卷积前排除填充 token，并在 RRF 评估中避免将未检索到的正例插入实际排名。 | [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) · [`7da542f`](https://github.com/huggingface/sentence-transformers/commit/7da542fb4ac0da773ab608e8b214e19aea7066f5)<br>[#4114](https://github.com/huggingface/sentence-transformers/pull/4114) · [`6994c94`](https://github.com/huggingface/sentence-transformers/commit/6994c94f39a3ff30f21075af1eca46d3ac5e8a8d) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,869 ★ | 将 V-JEPA 2 已有的成对 RoPE 修正应用于 VLA-JEPA 的训练期世界预测器。 | [#4835](https://github.com/huggingface/lerobot/pull/4835) · [`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |

### 最新核实的贡献榜前 30

**20 个展示中的上游项目在最新已核实的 GitHub Contributors 图榜中位列前 30**。排名均于 **2026-11-14** 读取。统一使用 **All / Commits / 默认分支 / 排除 merge commit**；各组按最近核实的 star 降序排列。

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** | 116,895 | [#3](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[331](https://github.com/thedotmack/claude-mem/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在待恢复标记清除前保留已选定的备份。[#5532](https://github.com/thedotmack/claude-mem/pull/5532) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 31,645 | [#1](https://github.com/storytold/craft-anything/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[246](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 完整解码连续的 Zstandard 帧，并对总输出统一限额。[#1340](https://github.com/storytold/craft-anything/pull/1340) |
| **[Claude SEO](https://github.com/AgriciDaniel/claude-seo)** | 29,117 | [#11](https://github.com/AgriciDaniel/claude-seo/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[3](https://github.com/AgriciDaniel/claude-seo/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 URL 规范化时保留 IPv6 地址结构，将 `none` 识别为 noindex 指令，并按单词边界匹配品牌后缀。 [#403](https://github.com/AgriciDaniel/claude-seo/pull/403) · [#404](https://github.com/AgriciDaniel/claude-seo/pull/404) · [#405](https://github.com/AgriciDaniel/claude-seo/pull/405) |
| **[DeepFace](https://github.com/serengil/deepface)** | 23,698 | [#2](https://github.com/serengil/deepface/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[48](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 NumPy 切片前裁剪人脸框，并在 HTTP 表单请求中正确解析值为 false 的选项。 [#1655](https://github.com/serengil/deepface/pull/1655) · [#1684](https://github.com/serengil/deepface/pull/1684) |
| **[OpenMausBot](https://github.com/milind-soni/OpenMausBot)** | 22,291 | [#10](https://github.com/milind-soni/OpenMausBot/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[65](https://github.com/milind-soni/OpenMausBot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在跨字节块的 CRLF 换行中保持 MCP 事件完整，并匹配请求 ID 后再缓存连接器工具列表。 [#5086](https://github.com/milind-soni/OpenMausBot/pull/5086) · [#5092](https://github.com/milind-soni/OpenMausBot/pull/5092) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,285 | [#27](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[6](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 排序梯度、FP16 量化与正确处理填充的 CNN/LSTM 编码。 [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) · [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,221 | [#25](https://github.com/colmap/colmap/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[5](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正使用相对路径时的 IMC 2024 数据集布局，并在切换子进程目录前解析基准路径。 [#4976](https://github.com/colmap/colmap/pull/4976) · [#4931](https://github.com/colmap/colmap/pull/4931) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,727 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留一维扩散中的外部条件与自条件。 [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[ThinkRail](https://github.com/JetBrains/thinkrail)** | 8,239 | [#12](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[4](https://github.com/JetBrains/thinkrail/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按 XML 根元素识别 SVG，并在截断终端输出时保留 UTF-16 代理对。 [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [#1186](https://github.com/JetBrains/thinkrail/pull/1186) |
| **[GestaltX](https://github.com/huamidev/GestaltX)** | 7,405 | [#1](https://github.com/huamidev/GestaltX/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[40](https://github.com/huamidev/GestaltX/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留 plist 的完整 64 位整数精度，并在拒绝、取消或接受后继续处理共享导入队列。 [#31](https://github.com/huamidev/GestaltX/pull/31) · [#40](https://github.com/huamidev/GestaltX/pull/40) |
| **[billion-context](https://github.com/ranxianglei/billion-context)** | 7,277 | [#3](https://github.com/ranxianglei/billion-context/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[11](https://github.com/ranxianglei/billion-context/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 客户端断连后取消闲置上游读取，保存 SSE 流时遵循背压并等待最终写入完成。 [#6051](https://github.com/ranxianglei/billion-context/pull/6051) · [#6052](https://github.com/ranxianglei/billion-context/pull/6052) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,343 | [#3](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[17](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 类别加权损失先以 FP32 归约再转回输入类型；半精度中心正则损失则保持 FP32。 [#775](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/775) · [#776](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/776) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,328 | [#8](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[10](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 加载失败时保留已有对话历史。 [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,586 | [#7](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[11](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正运动学、动力学、逆运动学与 URDF 处理。 [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,131 | [#4](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复 RND 调度进度，保持奖励历史独立并保留 rollout 尾批样本。 [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[Manifold](https://github.com/elalish/manifold)** | 2,408 | [#27](https://github.com/elalish/manifold/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[4](https://github.com/elalish/manifold/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 使静态凸包构造独立于输入的执行上下文，并保留已物化的操作数错误。 [#1905](https://github.com/elalish/manifold/pull/1905) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,621 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 最小二乘刚体配准、鲁棒核稳定性与相机参数广播。 [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,409 | [#7](https://github.com/Denys88/rl_games/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[4](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 回放批次超出容量时保留最新转移样本。 [#384](https://github.com/Denys88/rl_games/pull/384) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,104 | [#3](https://github.com/Toni-SM/skrl/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[5](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 归约 PyTorch 工作进程中非连续布局的梯度，并将 JAX 工作进程的失败状态传回启动器。 [#489](https://github.com/Toni-SM/skrl/pull/489) · [#496](https://github.com/Toni-SM/skrl/pull/496) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,103 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[15](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 修正 canonical Stiefel 切向量投影、Cayley 初始速度与线搜索导数，保持流形优化的正确性。 [#280](https://github.com/geoopt/geoopt/pull/280) · [#267](https://github.com/geoopt/geoopt/pull/267) |

### 更多已合并的上游贡献

| 项目 | 上游 ★ | 名次 · 核实日期¹ | 已合并 PR | 代表性工作 |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 458,060 | [#58](https://github.com/morluto/rea/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[6](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 补全 ZIP 短读并检测提前 EOF；在受字节限额约束的诊断输出中保留 UTF-8 码点边界。 [#4414](https://github.com/morluto/rea/pull/4414) · [#8907](https://github.com/morluto/rea/pull/8907) |
| **[vLLM](https://github.com/vllm-project/vllm)** | 96,890 | [—](https://github.com/vllm-project/vllm/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/vllm-project/vllm/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 加载非本机字节序的 NumPy 图像与视频嵌入时，保留数值及元素精度。 [#67479](https://github.com/vllm-project/vllm/pull/67479) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,869 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[2](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正 VLA-JEPA 训练期预测器的成对 RoPE 频率。 [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 27,004 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 隔离恢复执行计数，保持流水线快照可复用。 [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,992 | [#47](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[3](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在 k-core 过滤与分层划分中保留自定义输入列；#2419 合并至 `staging`。 [#2389](https://github.com/recommenders-team/recommenders/pull/2389) · [#2419](https://github.com/recommenders-team/recommenders/pull/2419) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | 15,733 | [#68](https://github.com/Unstructured-IO/unstructured/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[3](https://github.com/Unstructured-IO/unstructured/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留调用方的检测预测张量，按实际阈值计算精确率，并将空语言列表归入自动检测。 [#4702](https://github.com/Unstructured-IO/unstructured/pull/4702) · [#4703](https://github.com/Unstructured-IO/unstructured/pull/4703) · [#4704](https://github.com/Unstructured-IO/unstructured/pull/4704) |
| **[CARLA](https://github.com/carla-simulator/carla)** | 14,602 | [#61](https://github.com/carla-simulator/carla/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[5](https://github.com/carla-simulator/carla/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正文档中 4×4 位姿的坐标系变换公式，区分深度相机原始编码精度与灰度可视化精度。 [#10188](https://github.com/carla-simulator/carla/pull/10188) · [#10189](https://github.com/carla-simulator/carla/pull/10189) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,381 | [#77](https://github.com/kornia/kornia/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[7](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 以 FP32 累加加权半精度指标，并在不改变通道布局的前提下将 BF16 图像导出到 NumPy。 [#6580](https://github.com/kornia/kornia/pull/6580) · [#6582](https://github.com/kornia/kornia/pull/6582) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 8,959 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 让性能测量遵循当前 CUDA 设备选择。 [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[openMVG](https://github.com/openMVG/openMVG)** | 6,599 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/openMVG/openMVG/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按各观测视线方向判断 DLT 三角化点的深度，保留球面相机后半球的有效观测。 [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,193 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正提取出的表情符号与末尾单词的粘连。 [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,721 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正非均匀权重的 Procrustes 旋转，保留等权重拟合；原合并至 `release/angles`，现已进入默认分支 `main`。 [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,530 | [#83](https://github.com/geomstats/geomstats/graphs/contributors?all=1)<br><sub>2026-11-14</sub> | **[1](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将乘积度量的平行移动逐因子传递。 [#2131](https://github.com/geomstats/geomstats/pull/2131) |

¹ 排名依据 GitHub 官方 Contributors 图榜，并按其官方图表数据与当前前端排序规则复核，核验日期见各行；与上次快照使用相同图榜设置。更早的 REST 结果保留于完整记录，不能直接视为同一榜单的升降。`—` 表示已完整检查所显示的前 100 名，未找到 Afloat16；它不代表精确名次或零贡献。GitHub 图表计算可能存在缓存。图榜计数、默认分支作者 commit 和已合并 PR 分别统计。[完整记录、统计口径与数据](docs/CONTRIBUTIONS.md)。

### 由维护者整合进入默认分支的代码

Robotics Toolbox 也将 [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) 的粒子航向角环形统计修复整合进 [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883)，并将 [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) 的轨迹工作整合进 [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805)，保留共同作者署名。这些采纳与 881 个作者直接合并 PR 分开记录。[详情](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Craft Anything](https://github.com/storytold/craft-anything)** 通过 **11 次维护者整合**采纳了我 **101 个原始 PR** 的工作。最新的 [#1217](https://github.com/storytold/craft-anything/pull/1217) 整合了 7 个有关文件格式解析与项目启动的改动，并保留共同作者署名。此前 [#995](https://github.com/storytold/craft-anything/pull/995) 的合并提交遗漏署名，维护者在单独的文档提交 [#1012](https://github.com/storytold/craft-anything/pull/1012) 补记。[11 次整合及其来源](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[Claude-Mem](https://github.com/thedotmack/claude-mem)** 将 [#5339](https://github.com/thedotmack/claude-mem/pull/5339) 的非法输入回归案例采纳进 [#5336](https://github.com/thedotmack/claude-mem/pull/5336)，保留我的共同作者署名。被采纳的部分是拒绝测试，生产代码中的数字字符串转换由另一位 PR 作者实现。另通过 **11 个维护者整合 PR** 采纳了框架集成工作，**50 个采纳提交**保留我的作者身份，例如 [#5959](https://github.com/thedotmack/claude-mem/pull/5959) → [#6017](https://github.com/thedotmack/claude-mem/pull/6017)，以及 [#5958](https://github.com/thedotmack/claude-mem/pull/5958) → [#6024](https://github.com/thedotmack/claude-mem/pull/6024)。 这些采纳与我的 331 个直接合并 PR 分开记录。[证据](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[ThinkRail](https://github.com/JetBrains/thinkrail)** 将 [#1250](https://github.com/JetBrains/thinkrail/pull/1250) 的字面文件名忽略判断与回归案例整合进 [#1137](https://github.com/JetBrains/thinkrail/pull/1137)，保留共同作者署名。此项采纳与我的 **4 个直接合并 PR** 分开记录。[证据](docs/CONTRIBUTIONS.md#other-accepted-work)。

**[billion-context](https://github.com/ranxianglei/billion-context)** 通过维护者整合 [#6439](https://github.com/ranxianglei/billion-context/pull/6439) 采纳了我 **50 个原始 PR** 的工作，保留 **58 个与我的账户关联的作者提交**。这按 **1 次批量整合**记录；50 个来源 PR 均为关闭未直接合并，不计入上方的 **881 个作者合并 PR**。[来源与署名证据](docs/CONTRIBUTIONS.md#other-accepted-work)。

## 我的项目

为具体工程问题做的小工具。每个项目都附有使用说明，欢迎打开看看、试用，并为对你有用的项目点亮 Star。

<table>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/anti-rea-forge">Anti-REA Forge</a></strong><br><sub>原生软件保护 · v0.10.0</sub></p>
<p>以独立提供的密钥保护原生数据，生成 C++17/OpenSSL 读取代码。另含实验性的 LLVM 18 函数虚拟化与分析器验证记录。</p>
<ul>
<li>外部密钥原生数据</li>
<li>实验性 LLVM 18 方案</li>
</ul>
<p><a href="https://github.com/Afloat16/anti-rea-forge">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/AI-Memory-Book">AI-Memory-Book</a></strong><br><sub>智能体记忆 · v0.3.2</sub></p>
<p>为智能体提供共享的本地记忆，按项目成书、任务成章。主动开启受支持会话的后台采集，通过 MCP 按需召回带出处、长度受限的原文证据，延续先前工作。</p>
<ul>
<li>主动开启后台采集</li>
<li>带出处的 MCP 召回</li>
</ul>
<p><a href="https://github.com/Afloat16/AI-Memory-Book">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/modeldock">ModelDock</a></strong><br><sub>三维与 CAD · v0.2.0</sub></p>
<p>本地预览、对齐和比较网格与点云。支持超过 5 GiB 的二进制 PLY/STL 采样预览，并导出比较报告。</p>
<ul>
<li>多模型比较</li>
<li>5+ GiB 采样预览</li>
</ul>
<p><a href="https://github.com/Afloat16/modeldock">查看项目 · Star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/jev-mcp">Jev MCP</a></strong><br><sub>MCP 工具 · v0.5.0</sub></p>
<p>通过四个 MCP 工具，将 TypeSafe Jev 建议接入有限选项、路由和风险判断，并提供多款编码客户端安装器。</p>
<ul>
<li>四个 stdio 工具</li>
<li>显式有限选项</li>
</ul>
<p><a href="https://github.com/Afloat16/jev-mcp">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/bag-timeline-audit">Bag Timeline Audit</a></strong><br><sub>机器人</sub></p>
<p>检查 ROS 2 SQLite 或 MCAP 记录中的时间间隔、倒退和重复，并在确认共同时钟后比较不同话题。</p>
<ul>
<li>SQLite 与 MCAP</li>
<li>整数纳秒时间戳</li>
</ul>
<p><a href="https://github.com/Afloat16/bag-timeline-audit">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/llm-handshake">LLM Handshake</a></strong><br><sub>大模型接口 · 0.1.0</sub></p>
<p>逐项检查 OpenAI 兼容接口的流式输出、工具调用和结构化输出。先预览请求，再比较网关或模型升级前后的报告。</p>
<ul>
<li>七项专项检查</li>
<li>请求预览</li>
</ul>
<p><a href="https://github.com/Afloat16/llm-handshake">查看项目 · Star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/recontrail">ReconTrail</a></strong><br><sub>摄影测量</sub></p>
<p>检查照片质量，在 CPU 上重建稀疏三维几何，并分享可离线打开的交互报告。</p>
<ul>
<li>采集质量诊断</li>
<li>CPU 稀疏重建</li>
</ul>
<p><a href="https://github.com/Afloat16/recontrail">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/tf-route-audit">TF Route Audit</a></strong><br><sub>机器人</sub></p>
<p>检查导出的 TF 记录与原生 URDF 中的环路、断连和边冲突，并根据观测时间范围查询路径。</p>
<ul>
<li>原生 URDF 输入</li>
<li>拓扑诊断</li>
</ul>
<p><a href="https://github.com/Afloat16/tf-route-audit">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/sse-toolcall-audit">SSE Toolcall Audit</a></strong><br><sub>大模型接口</sub></p>
<p>从保存的 SSE 流中重组并行工具调用，检查结束标记、JSON 参数及与已保存最终响应的一致性。</p>
<ul>
<li>两类 API 格式</li>
<li>并行调用重组</li>
</ul>
<p><a href="https://github.com/Afloat16/sse-toolcall-audit">查看项目 · Star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/pose-convention-bridge">Pose Convention Bridge</a></strong><br><sub>三维几何</sub></p>
<p>转换 OpenCV/OpenGL 坐标轴与世界到相机、相机到世界位姿，校验刚体变换并导出 Nerfstudio 格式。</p>
<ul>
<li>COLMAP 与 TUM 输入</li>
<li>刚体变换校验</li>
</ul>
<p><a href="https://github.com/Afloat16/pose-convention-bridge">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/colmap-model-audit">COLMAP Model Audit</a></strong><br><sub>三维几何</sub></p>
<p>检查 COLMAP 文本模型的相机字段、互相引用的轨迹及视图连接图的连通性，还可核对图像路径与模型重叠。</p>
<ul>
<li>只读模型检查</li>
<li>双向轨迹校验</li>
</ul>
<p><a href="https://github.com/Afloat16/colmap-model-audit">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/tooltrace-audit">Tooltrace Audit</a></strong><br><sub>智能体工作流</sub></p>
<p>分析保存的执行轨迹，定位重叠重试、重复尝试与未匹配结果。可为自己的工具调用接入可选记录器。</p>
<ul>
<li>执行与对话轨迹</li>
<li>重试重叠检查</li>
</ul>
<p><a href="https://github.com/Afloat16/tooltrace-audit">查看项目 · Star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/research-to-fix">Research to Fix</a></strong><br><sub>研究工作流</sub></p>
<p>研究相似故障，将适用方案映射到本地代码并验证修复。连同来源和前后对照证据保存案例。</p>
<ul>
<li>来源可追溯诊断</li>
<li>本地适用性核对</li>
</ul>
<p><a href="https://github.com/Afloat16/research-to-fix">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/debate-direction">Debate Direction</a></strong><br><sub>智能体工作流</sub></p>
<p>让两个智能体提出、质疑并迭代方案，将异议、未决分歧和下一步验证保留在可审阅报告中。</p>
<ul>
<li>持续提案与质疑</li>
<li>问题台账</li>
</ul>
<p><a href="https://github.com/Afloat16/debate-direction">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/ai-dev-steward">StewardCheck</a></strong><br><sub>编码工作流 · 0.2.0 Alpha</sub></p>
<p>固定任务起点，按约定范围检查改动，并让测试记录对应其实际检查的文件状态。</p>
<ul>
<li>任务范围检查</li>
<li>工作区指纹</li>
</ul>
<p><a href="https://github.com/Afloat16/ai-dev-steward">查看项目 · Star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/agent-action-notifier">Agent Action Notifier</a></strong><br><sub>智能体工作流 · v0.2.0</sub></p>
<p>将明确的工作流事件转为排队发送的邮件或桌面通知，追踪待处理请求、重试，并在发送中断后恢复。</p>
<ul>
<li>SQLite 发件队列</li>
<li>邮件与桌面渠道</li>
</ul>
<p><a href="https://github.com/Afloat16/agent-action-notifier">查看项目 · Star →</a></p>
</td>
</tr>
</table>

我通常会先隔离症状、明确边界、补充回归测试，并让结果可检查。[六个领域工具](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md#validation-for-this-release)在记录的发布版本中有 **67 项本地测试、36 组通过的 OS/Python CI 组合**。这些是实验性诊断与转换工具，各仓库均说明适用范围。

<details>
<summary><b>全部 16 个项目：Stars 与默认分支 commits</b></summary>

截至 **2026-11-14 13:48（UTC+8）**，按 stars 降序，同星按仓库 commit 数降序排列。这里的 commits 是各仓库默认分支可达的历史提交数（含 merge commits），不是个人作者提交数。完整来源与版本见[项目记录](docs/PROJECTS.md)。

| 项目 | ★ | 默认分支 commits | 主要语言 |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [9](https://github.com/Afloat16/anti-rea-forge/stargazers) | [31](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [AI-Memory-Book](https://github.com/Afloat16/AI-Memory-Book) | [3](https://github.com/Afloat16/AI-Memory-Book/stargazers) | [504](https://github.com/Afloat16/AI-Memory-Book/commits/main/) | Python |
| [ModelDock](https://github.com/Afloat16/modeldock) | [2](https://github.com/Afloat16/modeldock/stargazers) | [6](https://github.com/Afloat16/modeldock/commits/main/) | TypeScript |
| [Jev MCP](https://github.com/Afloat16/jev-mcp) | [1](https://github.com/Afloat16/jev-mcp/stargazers) | [49](https://github.com/Afloat16/jev-mcp/commits/main/) | TypeScript |
| [StewardCheck](https://github.com/Afloat16/ai-dev-steward) | [1](https://github.com/Afloat16/ai-dev-steward/stargazers) | [11](https://github.com/Afloat16/ai-dev-steward/commits/main/) | Python |
| [Debate Direction](https://github.com/Afloat16/debate-direction) | [1](https://github.com/Afloat16/debate-direction/stargazers) | [8](https://github.com/Afloat16/debate-direction/commits/main/) | Python |
| [Research to Fix](https://github.com/Afloat16/research-to-fix) | [1](https://github.com/Afloat16/research-to-fix/stargazers) | [7](https://github.com/Afloat16/research-to-fix/commits/main/) | Python |
| [LLM Handshake](https://github.com/Afloat16/llm-handshake) | [1](https://github.com/Afloat16/llm-handshake/stargazers) | [6](https://github.com/Afloat16/llm-handshake/commits/main/) | Python |
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
