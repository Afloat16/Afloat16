<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-animated-dark.svg?v=1">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-animated-light.svg?v=1" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

研究工具与上游工程 · Python · TypeScript · C/C++

**[我的项目 ↓](#我的项目)** · [开源贡献](#开源贡献) · [English](README.md)

</div>

## 开源贡献

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-compact-dark.svg?v=6">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-compact-light.svg?v=6" alt="截至 2026-11-19：1,297 个已核验作者合并 PR，52 个上游仓库，超过 1,000 星且有直接合并 PR 的上游中，26 个已核验 Top-30 排名。" width="100%">
</picture>

更新于 **2026-11-19** · 上游列表仅展示 **超过 1,000 星**的项目 · 合并总数包含全部已核验的作者合并 PR。[核验记录](docs/CONTRIBUTIONS.md)。

### 精选已合并贡献

代表工作按各仓库完整已合并历史中的技术含量与实际作用选择。

| 合并日期¹ | 上游项目 · ★ | 代表性工程改进 | PR |
|---|---|---|---|
| 2026-11-17 | **[ECC](https://github.com/affaan-m/ECC)**<br>306,825 ★ | 通过异步提供方队列、取消安全的许可移交和工作线程执行，保持智能体推理响应。 | [#3911](https://github.com/affaan-m/ECC/pull/3911) |
| 2026-11-12 | **[Claude-Mem](https://github.com/thedotmack/claude-mem)**<br>118,306 ★ | 将目标映射改为有界、可恢复且逐批核验证据的流程，并以数据库行锁串行化生成任务的重试与取消。 | [#6001](https://github.com/thedotmack/claude-mem/pull/6001) · [#5650](https://github.com/thedotmack/claude-mem/pull/5650) |
| 2026-11-06 | **[REA](https://github.com/morluto/rea)**<br>468,913 ★ | 在迭代中断后继续投递已缓冲的 NDJSON 响应，并补全 ZIP 定位读取中的短读。 | [#4414](https://github.com/morluto/rea/pull/4414) · [#8909](https://github.com/morluto/rea/pull/8909) |
| 2026-11-05 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,290 ★ | 恢复严重错序样本的排序损失梯度，并避免填充内容污染 CNN 句向量。 | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) |
| 2026-11-03 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>37,658 ★ | 以持久化内容指纹终止无进展重建，并通过类型化、有界且可取消的重试恢复 API/CLI 构建回合。 | [#552](https://github.com/storytold/craft-anything/pull/552) · [#557](https://github.com/storytold/craft-anything/pull/557) |
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,254 ★ | 消除重建尺度对平移角度基准评测的影响，覆盖极小和极大坐标量级。 | [#4932](https://github.com/colmap/colmap/pull/4932) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,978 ★ | 将 V-JEPA 2 的成对 RoPE 修正应用于 VLA-JEPA 训练预测器，恢复范数与相对位置内积不变量。 | [#4835](https://github.com/huggingface/lerobot/pull/4835) |

¹ 每行日期为该项目所选 PR 中的最近合并日。[实现范围与合并提交](docs/CONTRIBUTIONS.md#selected-merges-by-project)。

### 最新核实的贡献榜前 30

**已核验的 26 个 Top-30 项目。** ² GitHub Contributors：**All / Commits / 默认分支**，核验日期 **2026-11-19**；按星数排序。[排名证据](docs/CONTRIBUTIONS.md#verification-method)。

| 项目 | 上游 ★ | 排名² | 已合并 PR | 代表性工程改进 |
|---|---:|---:|---:|---|
| **[ECC](https://github.com/affaan-m/ECC)** | 306,825 | [#22](https://github.com/affaan-m/ECC/graphs/contributors?all=1) | **[13](https://github.com/affaan-m/ECC/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 通过异步提供方队列、取消安全的许可移交和工作线程执行，保持智能体推理响应。 [#3911](https://github.com/affaan-m/ECC/pull/3911) |
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** | 118,306 | [#3](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1) | **[389](https://github.com/thedotmack/claude-mem/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将目标映射改为有界、可恢复且逐批核验证据的流程，并以数据库行锁串行化生成任务的重试与取消。 [#6001](https://github.com/thedotmack/claude-mem/pull/6001) · [#5650](https://github.com/thedotmack/claude-mem/pull/5650) |
| **[MiniMind](https://github.com/jingyaogong/minimind)** | 66,586 | [#3](https://github.com/jingyaogong/minimind/graphs/contributors?all=1) | **[5](https://github.com/jingyaogong/minimind/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 以 FP32 累加 LoRA 权重更新后再舍入为 FP16，并让贪心解码不受采样温度和过滤器影响。 [#919](https://github.com/jingyaogong/minimind/pull/919) · [#912](https://github.com/jingyaogong/minimind/pull/912) |
| **[reverse-skill](https://github.com/zhaoxuya520/reverse-skill)** | 44,911 | [#8](https://github.com/zhaoxuya520/reverse-skill/graphs/contributors?all=1) | **[1](https://github.com/zhaoxuya520/reverse-skill/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在整合写入前验证案例图身份、引用和本地证据，阻止歧义或无效知识图。 [#181](https://github.com/zhaoxuya520/reverse-skill/pull/181) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 37,658 | [#2](https://github.com/storytold/craft-anything/graphs/contributors?all=1) | **[247](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 以持久化内容指纹终止无进展重建，并通过类型化、有界且可取消的重试恢复 API/CLI 构建回合。 [#552](https://github.com/storytold/craft-anything/pull/552) · [#557](https://github.com/storytold/craft-anything/pull/557) |
| **[Claude SEO](https://github.com/AgriciDaniel/claude-seo)** | 30,770 | [#3](https://github.com/AgriciDaniel/claude-seo/graphs/contributors?all=1) | **[32](https://github.com/AgriciDaniel/claude-seo/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 仅比较同一实测数据范围的 Core Web Vitals，并避免抓取失败被误报为低风险。 [#427](https://github.com/AgriciDaniel/claude-seo/pull/427) · [#431](https://github.com/AgriciDaniel/claude-seo/pull/431) |
| **[OpenMausBot](https://github.com/milind-soni/OpenMausBot)** | 25,566 | [#8](https://github.com/milind-soni/OpenMausBot/graphs/contributors?all=1) | **[123](https://github.com/milind-soni/OpenMausBot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 分离 MCP 事件流与单次请求的取消生命周期，并区分反向请求和响应，保持共享传输正确性。 [#5392](https://github.com/milind-soni/OpenMausBot/pull/5392) · [#5393](https://github.com/milind-soni/OpenMausBot/pull/5393) |
| **[DeepFace](https://github.com/serengil/deepface)** | 23,714 | [#2](https://github.com/serengil/deepface/graphs/contributors?all=1) | **[61](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 统一 Milvus 与 DeepFace 距离语义，并串行化共享原生检测器调用，避免并发请求混淆推理结果。 [#1634](https://github.com/serengil/deepface/pull/1634) · [#1756](https://github.com/serengil/deepface/pull/1756) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,254 | [#27](https://github.com/colmap/colmap/graphs/contributors?all=1) | **[5](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 消除重建尺度对平移角度基准评测的影响，覆盖极小和极大坐标量级。 [#4932](https://github.com/colmap/colmap/pull/4932) |
| **[Edge0](https://github.com/Edge0-AI/Edge0)** | 12,054 | [#6](https://github.com/Edge0-AI/Edge0/graphs/contributors?all=1) | **[12](https://github.com/Edge0-AI/Edge0/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将 safetensors 直接读入最终缓冲区，并按请求数量限制 top-logprob 候选存储，减少多余分配。 [#171](https://github.com/Edge0-AI/Edge0/pull/171) · [#183](https://github.com/Edge0-AI/Edge0/pull/183) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,724 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1) | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在一维扩散训练、DDPM 与 DDIM 采样中一致传递外部条件和自条件。 [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[GestaltX](https://github.com/huami1314/GestaltX)** | 8,450 | [#1](https://github.com/huami1314/GestaltX/graphs/contributors?all=1) | **[40](https://github.com/huami1314/GestaltX/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 从匹配的系统缓存代际恢复设备原值，并在备份或写入前拒绝改变设备身份的修改。 [#65](https://github.com/huami1314/GestaltX/pull/65) · [#67](https://github.com/huami1314/GestaltX/pull/67) |
| **[ThinkRail](https://github.com/JetBrains/thinkrail)** | 8,357 | [#14](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1) | **[4](https://github.com/JetBrains/thinkrail/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 按结构解析 XML 根节点与终端控制序列，避免 SVG 误分类，并保留控制序列取消或替换后的 notebook 正文。 [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [#1258](https://github.com/JetBrains/thinkrail/pull/1258) |
| **[billion-context](https://github.com/ranxianglei/billion-context)** | 7,909 | [#2](https://github.com/ranxianglei/billion-context/graphs/contributors?all=1) | **[78](https://github.com/ranxianglei/billion-context/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 线性扫描压缩 SSE 帧，并批量读取消息正文，消除重复流扫描和逐消息数据库查询。 [#6579](https://github.com/ranxianglei/billion-context/pull/6579) · [#6733](https://github.com/ranxianglei/billion-context/pull/6733) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,343 | [#3](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1) | **[17](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 稳定 NT-Xent 的分数平移数值行为，并安全计算混合精度 VICReg 统计量，保留训练梯度。 [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) · [#785](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/785) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,341 | [#4](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1) | **[65](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在验证与工具传输中保留递归 MCP schema、保留字段名和显式允许的对象扩展。 [#389](https://github.com/Eigenwise/atomic-agents/pull/389) |
| **[NVIDIA SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator)** | 3,948 | [#6](https://github.com/NVIDIA/SkillEvaluator/graphs/contributors?all=1) | **[9](https://github.com/NVIDIA/SkillEvaluator/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 以迭代遍历处理深层合法表达式，并在评测预算计算前拒绝歧义费率输入。 [#760](https://github.com/NVIDIA/SkillEvaluator/pull/760) · [#749](https://github.com/NVIDIA/SkillEvaluator/pull/749) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,592 | [#6](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1) | **[22](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正操作空间科氏动力学，以及 Python/原生逆运动学使用的任意轴半转姿态残差。 [#793](https://github.com/petercorke/robotics-toolbox-python/pull/793) · [#796](https://github.com/petercorke/robotics-toolbox-python/pull/796) |
| **[SoduWork](https://github.com/mdiri-ai/SoduWork)** | 3,567 | [#19](https://github.com/mdiri-ai/SoduWork/graphs/contributors?all=1) | **[1](https://github.com/mdiri-ai/SoduWork/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 识别被注释分隔的 CSS 导入，让网站交付保留后续样式表与图片依赖。 [#457](https://github.com/mdiri-ai/SoduWork/pull/457) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,149 | [#4](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1) | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保留循环与前馈 minibatch 的全部 rollout 样本，并从 PPO 检查点一致恢复 RND 探索调度。 [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[Manifold](https://github.com/elalish/manifold)** | 2,424 | [#11](https://github.com/elalish/manifold/graphs/contributors?all=1) | **[18](https://github.com/elalish/manifold/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正旋转角度约简，并跳过未请求的曲率通道，在保留几何结果的同时减少多余计算。 [#1948](https://github.com/elalish/manifold/pull/1948) · [#1981](https://github.com/elalish/manifold/pull/1981) |
| **[Agentes Chat](https://github.com/agentes-chat/agentes-chat)** | 1,731 | [#9](https://github.com/agentes-chat/agentes-chat/graphs/contributors?all=1) | **[5](https://github.com/agentes-chat/agentes-chat/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在向量映射到文本前验证 embedding 结果身份，并在归档导入前拒绝不一致 ZIP 元数据。 [#336](https://github.com/agentes-chat/agentes-chat/pull/336) · [#354](https://github.com/agentes-chat/agentes-chat/pull/354) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,620 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1) | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 通过仅修正最弱奇异方向去除反射，恢复 SVD 刚体配准的最小二乘最优解。 [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,410 | [#5](https://github.com/Denys88/rl_games/graphs/contributors?all=1) | **[22](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在超容量批次中保留最新 replay 数据，并让优先采样覆盖全部有效槽位。 [#384](https://github.com/Denys88/rl_games/pull/384) · [#393](https://github.com/Denys88/rl_games/pull/393) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,105 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1) | **[15](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | 修正 canonical Stiefel 投影及 Cayley 曲线导数，使流形优化保持切向动量与一致的线搜索斜率。 [#280](https://github.com/geoopt/geoopt/pull/280) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,104 | [#3](https://github.com/Toni-SM/skrl/graphs/contributors?all=1) | **[5](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 修正高斯策略方差和 TRPO KL 散度，恢复预期采样尺度、似然和信赖域判断。 [#467](https://github.com/Toni-SM/skrl/pull/467) · [#469](https://github.com/Toni-SM/skrl/pull/469) |

### 更多已合并的上游贡献

| 项目 | 上游 ★ | 排名² | 已合并 PR | 代表性工程改进 |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 468,913 | [#70](https://github.com/morluto/rea/graphs/contributors?all=1) | **[6](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在迭代中断后继续投递已缓冲的 NDJSON 响应，并补全 ZIP 定位读取中的短读。 [#4414](https://github.com/morluto/rea/pull/4414) · [#8909](https://github.com/morluto/rea/pull/8909) |
| **[vLLM](https://github.com/vllm-project/vllm)** | 97,199 | [—](https://github.com/vllm-project/vllm/graphs/contributors?all=1) | **[1](https://github.com/vllm-project/vllm/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在张量转换前规范 NumPy embedding 字节序，保留图像与视频输入的数值和精度。 [#67479](https://github.com/vllm-project/vllm/pull/67479) |
| **[Open Code Review](https://github.com/alibaba/open-code-review)** | 54,263 | [#73](https://github.com/alibaba/open-code-review/graphs/contributors?all=1) | **[2](https://github.com/alibaba/open-code-review/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 分离发现的身份字段，避免分隔符碰撞把新增或已解决的问题误判为持续问题。 [#1955](https://github.com/alibaba/open-code-review/pull/1955) |
| **[Qwen Code](https://github.com/QwenLM/qwen-code)** | 30,775 | [#49](https://github.com/QwenLM/qwen-code/graphs/contributors?all=1) | **[29](https://github.com/QwenLM/qwen-code/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 共享不可变 transcript 页面并返回关联原请求的回调错误，改善 Java 会话重放效率与控制协议可靠性。 [#17113](https://github.com/QwenLM/qwen-code/pull/17113) · [#17115](https://github.com/QwenLM/qwen-code/pull/17115) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,978 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1) | **[2](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将 V-JEPA 2 的成对 RoPE 修正应用于 VLA-JEPA 训练预测器，恢复范数与相对位置内积不变量。 [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 27,050 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1) | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 隔离运行中的可变访问计数与已保存状态，使 pipeline 检查点可重复用于恢复执行。 [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 22,004 | [#47](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1) | **[3](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 分层切分时完整保留用户数据列，并在迭代 k-core 过滤中始终遵循自定义用户和物品标识列。 [#2419](https://github.com/recommenders-team/recommenders/pull/2419) · [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,290 | [#32](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1) | **[6](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复严重错序样本的排序损失梯度，并避免填充内容污染 CNN 句向量。 [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | 15,766 | [#36](https://github.com/Unstructured-IO/unstructured/graphs/contributors?all=1) | **[9](https://github.com/Unstructured-IO/unstructured/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 使密集 XY-cut 投影计算随框数与轴长线性增长，并消除分块接纳过程中的重复表格扫描。 [#4748](https://github.com/Unstructured-IO/unstructured/pull/4748) · [#4744](https://github.com/Unstructured-IO/unstructured/pull/4744) |
| **[CARLA](https://github.com/carla-simulator/carla)** | 14,648 | [#62](https://github.com/carla-simulator/carla/graphs/contributors?all=1) | **[5](https://github.com/carla-simulator/carla/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 让 CARLA 纹理工具支持 RGB/RGBA 输入与部分材质更新。 [#10194](https://github.com/carla-simulator/carla/pull/10194) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,395 | [#78](https://github.com/kornia/kornia/graphs/contributors?all=1) | **[7](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 稳定小根四次方程求解与平行线面求交导数，保留有效根和有限几何梯度。 [#5474](https://github.com/kornia/kornia/pull/5474) · [#5517](https://github.com/kornia/kornia/pull/5517) |
| **[Betaflight](https://github.com/betaflight/betaflight)** | 11,807 | [—](https://github.com/betaflight/betaflight/graphs/contributors?all=1) | **[1](https://github.com/betaflight/betaflight/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 正确保留 S-record 载荷，并在生成可刷写 DfuSe 镜像前验证长度、校验和和地址范围。 [#15983](https://github.com/betaflight/betaflight/pull/15983) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 9,004 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1) | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 未显式指定设备时，让基准测试的缓存清理缓冲区分配在当前 CUDA 设备上。 [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[openMVG](https://github.com/openMVG/openMVG)** | 6,603 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1) | **[1](https://github.com/openMVG/openMVG/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 恢复依观测视线判断的三角化正深度约束，使球面相机保留前后半球的有效观测。 [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,195 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1) | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在文本分词器中保留单词与表情的独立 token，避免首个提取表情粘连到最后一个单词。 [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,728 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1) | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 将对应点权重应用于 Procrustes 协方差，修正非均匀权重下的旋转并保留等权拟合。 [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,531 | [#54](https://github.com/geomstats/geomstats/graphs/contributors?all=1) | **[3](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 保持对称矩阵重建的自动微分能力，并正确保留逐点 Jacobian/Hessian 的批次维度。 [#2235](https://github.com/geomstats/geomstats/pull/2235) · [#2238](https://github.com/geomstats/geomstats/pull/2238) |
| **[Awesome MCP Servers](https://github.com/TensorBlock/awesome-mcp-servers)** | 1,101 | [—](https://github.com/TensorBlock/awesome-mcp-servers/graphs/contributors?all=1) | **[1](https://github.com/TensorBlock/awesome-mcp-servers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | 在记忆服务器目录登记 AI-Memory-Book，补齐安装命令、stdio 传输与客户端元数据。 [#6055](https://github.com/TensorBlock/awesome-mcp-servers/pull/6055) |

² 排名采用相同图表设置，各仓库核验日期见证据。`—` 表示上次核验时未出现在完整展示的前 100 名中。图表排名与合并 PR 数分别统计。

### 由维护者整合进入默认分支的代码

<details>
<summary><b>维护者整合与 cherry-pick · 已核验作者归属</b></summary>

采纳的源提交与作者直接合并 PR 分开记录。[完整采纳记录与范围](docs/CONTRIBUTIONS.md#other-accepted-work)。

| 项目 · ★ | 采纳范围 / 来源 |
|---|---|
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** · 3,592 ★ | 粒子航向的圆周估计与轨迹实现。 [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883) · [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** · 37,658 ★ | 101 个源 PR 通过 11 次维护者整合被采纳。 [#1217](https://github.com/storytold/craft-anything/pull/1217) |
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** · 118,306 ★ | 17 次维护者重新托管保留 62 个作者提交。 [#6017](https://github.com/thedotmack/claude-mem/pull/6017) · [#6296](https://github.com/thedotmack/claude-mem/pull/6296) |
| **[billion-context](https://github.com/ranxianglei/billion-context)** · 7,909 ★ | 通过源提交逐项核验归属的批量整合。 [#6439](https://github.com/ranxianglei/billion-context/pull/6439) · [#7101](https://github.com/ranxianglei/billion-context/pull/7101) |
| **[OpenMausBot](https://github.com/milind-soni/OpenMausBot)** · 25,566 ★ | 维护者整合中另行记录的 1 个作者源提交。 [#6021](https://github.com/milind-soni/OpenMausBot/pull/6021) |
| **[TD-MPC2](https://github.com/nicklashansen/tdmpc2)** · 1,006 ★ | 在转换时保留目标 Q 历史与评估模式。 [`332f19e`](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a) |

</details>

## 我的项目

为具体工程问题做的小工具。每个项目都附有使用说明，欢迎打开看看、试用，并为对你有用的项目点亮 Star。

<table>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/anti-rea-forge">Anti-REA Forge</a></strong><br><sub>原生软件保护 · v1.4.0</sub></p>
<p>以独立提供的密钥保护原生数据，生成 C++17/OpenSSL 读取代码。另含实验性的 LLVM 18 函数虚拟化与分析器验证记录。</p>
<ul>
<li>外部密钥原生数据</li>
<li>实验性 LLVM 18 方案</li>
</ul>
<p><a href="https://github.com/Afloat16/anti-rea-forge">查看项目 · Star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/AI-Memory-Book">AI-Memory-Book</a></strong><br><sub>智能体记忆 · v0.13.0</sub></p>
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

截至 **2026-11-19**，按 stars 降序，同星按仓库 commit 数降序排列。这里的 commits 是各仓库默认分支可达的历史提交数（含 merge commits），不是个人作者提交数。完整来源与版本见[项目记录](docs/PROJECTS.md)。

| 项目 | ★ | 默认分支 commits | 主要语言 |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [9](https://github.com/Afloat16/anti-rea-forge/stargazers) | [40](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [AI-Memory-Book](https://github.com/Afloat16/AI-Memory-Book) | [3](https://github.com/Afloat16/AI-Memory-Book/stargazers) | [1,025](https://github.com/Afloat16/AI-Memory-Book/commits/main/) | Python |
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


