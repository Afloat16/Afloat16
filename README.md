<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-animated-dark.svg?v=1">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-animated-light.svg?v=1" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

Research tools and upstream engineering · Python · TypeScript · C/C++

**[My projects ↓](#projects-i-build)** · [Upstream contributions](#open-source-contributions) · [简体中文](README.zh-CN.md)

</div>

## Open-source contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-compact-dark.svg?v=8">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-compact-light.svg?v=8" alt="1,391 verified merged author PRs across 53 upstream repositories; 27 verified top-30 positions among direct-merge upstreams with more than 1,000 stars. Updated 2026-11-21." width="100%">
</picture>

Updated **2026-11-21** · Upstream lists: **>1,000 stars** · Totals include all verified merged author PRs. [Evidence](docs/CONTRIBUTIONS.md).

### Selected merged contributions

Representative work is selected for technical depth and practical effect across each repository's complete merged history.

| Merged¹ | Project · ★ | Representative engineering | PRs |
|---|---|---|---|
| 2026-11-17 | **[ECC](https://github.com/affaan-m/ECC)**<br>307,865 ★ | Keep agent inference responsive with asynchronous per-provider queues, cancellation-safe permit transfer and worker-thread execution. | [#3911](https://github.com/affaan-m/ECC/pull/3911) |
| 2026-11-12 | **[Claude-Mem](https://github.com/thedotmack/claude-mem)**<br>118,652 ★ | Map goals in bounded, resumable batches with validated evidence, and serialize generation retries and cancellations under database row locks. | [#6001](https://github.com/thedotmack/claude-mem/pull/6001) · [#5650](https://github.com/thedotmack/claude-mem/pull/5650) |
| 2026-11-06 | **[REA](https://github.com/morluto/rea)**<br>471,532 ★ | Resume buffered NDJSON replies after interrupted iteration and complete partial positional ZIP reads. | [#4414](https://github.com/morluto/rea/pull/4414) · [#8909](https://github.com/morluto/rea/pull/8909) |
| 2026-11-05 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,294 ★ | Restore ranking-loss gradients for badly ordered pairs and prevent padding from contaminating CNN sentence embeddings. | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) |
| 2026-11-03 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>39,543 ★ | Stop unchanged rebuilds using persisted content fingerprints, and recover interrupted API/CLI turns through typed, bounded, cancellable retries. | [#552](https://github.com/storytold/craft-anything/pull/552) · [#557](https://github.com/storytold/craft-anything/pull/557) |
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,264 ★ | Make translation-angle benchmarks invariant to reconstruction scale, including extremely small and large coordinate magnitudes. | [#4932](https://github.com/colmap/colmap/pull/4932) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>29,002 ★ | Apply V-JEPA 2's pairwise RoPE correction to VLA-JEPA's training predictor, restoring norm and relative-position inner-product invariants. | [#4835](https://github.com/huggingface/lerobot/pull/4835) |

¹ Latest date among the selected PRs in each row. [Implementation scope and merge commits](docs/CONTRIBUTIONS.md#selected-merges-by-project).

### Latest verified top-30 contributor positions

**27 verified Top-30 projects.** ² GitHub Contributors: **All / Commits / default branch**, verification date **2026-11-21**. Sorted by stars. [Ranking evidence](docs/CONTRIBUTIONS.md#verification-method).

| Project | Upstream ★ | Position² | Merged PRs | Representative engineering |
|---|---:|---:|---:|---|
| **[ECC](https://github.com/affaan-m/ECC)** | 307,865 | [#10](https://github.com/affaan-m/ECC/graphs/contributors?all=1) | **[23](https://github.com/affaan-m/ECC/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep agent inference responsive with asynchronous per-provider queues, cancellation-safe permit transfer and worker-thread execution. [#3911](https://github.com/affaan-m/ECC/pull/3911) |
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** | 118,652 | [#3](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1) | **[389](https://github.com/thedotmack/claude-mem/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Map goals in bounded, resumable batches with validated evidence, and serialize generation retries and cancellations under database row locks. [#6001](https://github.com/thedotmack/claude-mem/pull/6001) · [#5650](https://github.com/thedotmack/claude-mem/pull/5650) |
| **[MiniMind](https://github.com/jingyaogong/minimind)** | 67,698 | [#3](https://github.com/jingyaogong/minimind/graphs/contributors?all=1) | **[5](https://github.com/jingyaogong/minimind/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Accumulate LoRA weight updates in FP32 before final FP16 rounding, and keep greedy decoding independent of sampling temperature and filters. [#919](https://github.com/jingyaogong/minimind/pull/919) · [#912](https://github.com/jingyaogong/minimind/pull/912) |
| **[reverse-skill](https://github.com/zhaoxuya520/reverse-skill)** | 44,991 | [#8](https://github.com/zhaoxuya520/reverse-skill/graphs/contributors?all=1) | **[1](https://github.com/zhaoxuya520/reverse-skill/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Validate case-graph identities, references and local evidence before consolidation writes, preventing ambiguous or invalid knowledge graphs. [#181](https://github.com/zhaoxuya520/reverse-skill/pull/181) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 39,543 | [#2](https://github.com/storytold/craft-anything/graphs/contributors?all=1) | **[250](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | Stop unchanged rebuilds using persisted content fingerprints, and recover interrupted API/CLI turns through typed, bounded, cancellable retries. [#552](https://github.com/storytold/craft-anything/pull/552) · [#557](https://github.com/storytold/craft-anything/pull/557) |
| **[Claude SEO](https://github.com/AgriciDaniel/claude-seo)** | 31,170 | [#3](https://github.com/AgriciDaniel/claude-seo/graphs/contributors?all=1) | **[32](https://github.com/AgriciDaniel/claude-seo/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Compare Core Web Vitals within matching field-data scopes and keep failed crawls from producing misleading low-risk assessments. [#427](https://github.com/AgriciDaniel/claude-seo/pull/427) · [#431](https://github.com/AgriciDaniel/claude-seo/pull/431) |
| **[OpenMausBot](https://github.com/milind-soni/OpenMausBot)** | 26,211 | [#8](https://github.com/milind-soni/OpenMausBot/graphs/contributors?all=1) | **[132](https://github.com/milind-soni/OpenMausBot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Separate MCP stream lifetime from request cancellation and distinguish reverse requests from replies, preserving shared transport correctness. [#5392](https://github.com/milind-soni/OpenMausBot/pull/5392) · [#5393](https://github.com/milind-soni/OpenMausBot/pull/5393) |
| **[DeepFace](https://github.com/serengil/deepface)** | 23,716 | [#2](https://github.com/serengil/deepface/graphs/contributors?all=1) | **[61](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct Milvus-to-DeepFace distance semantics and serialize shared native detectors to prevent cross-request inference corruption. [#1634](https://github.com/serengil/deepface/pull/1634) · [#1756](https://github.com/serengil/deepface/pull/1756) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,264 | [#27](https://github.com/colmap/colmap/graphs/contributors?all=1) | **[5](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Make translation-angle benchmarks invariant to reconstruction scale, including extremely small and large coordinate magnitudes. [#4932](https://github.com/colmap/colmap/pull/4932) |
| **[Edge0](https://github.com/Edge0-AI/Edge0)** | 12,151 | [#6](https://github.com/Edge0-AI/Edge0/graphs/contributors?all=1) | **[12](https://github.com/Edge0-AI/Edge0/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stream safetensors directly into final buffers and bound top-logprob candidate storage by requested count, reducing avoidable inference-tool allocations. [#171](https://github.com/Edge0-AI/Edge0/pull/171) · [#183](https://github.com/Edge0-AI/Edge0/pull/183) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,726 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1) | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve external conditioning and self-conditioning throughout 1D diffusion training, DDPM sampling and DDIM sampling. [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[GestaltX](https://github.com/huami1314/GestaltX)** | 8,642 | [#1](https://github.com/huami1314/GestaltX/graphs/contributors?all=1) | **[40](https://github.com/huami1314/GestaltX/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Recover original device values from matching cache generations and reject identity-changing system writes before backup or mutation. [#65](https://github.com/huami1314/GestaltX/pull/65) · [#67](https://github.com/huami1314/GestaltX/pull/67) |
| **[ThinkRail](https://github.com/JetBrains/thinkrail)** | 8,377 | [#14](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1) | **[4](https://github.com/JetBrains/thinkrail/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Parse XML roots and terminal control sequences structurally, preventing false SVG classification and preserving notebook text around cancelled or replaced controls. [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [#1258](https://github.com/JetBrains/thinkrail/pull/1258) |
| **[billion-context](https://github.com/ranxianglei/billion-context)** | 8,031 | [#2](https://github.com/ranxianglei/billion-context/graphs/contributors?all=1) | **[103](https://github.com/ranxianglei/billion-context/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Scan compaction SSE frames in linear time and batch message-body reads, removing repeated stream scans and per-message database queries. [#6579](https://github.com/ranxianglei/billion-context/pull/6579) · [#6733](https://github.com/ranxianglei/billion-context/pull/6733) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,343 | [#3](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1) | **[17](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stabilize NT-Xent against common score shifts and compute VICReg statistics safely under mixed precision, preserving training gradients. [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) · [#785](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/785) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,343 | [#4](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1) | **[65](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve recursive MCP schemas, reserved field identities and explicitly allowed object extensions through validation and tool transport. [#389](https://github.com/Eigenwise/atomic-agents/pull/389) |
| **[SoduWork](https://github.com/mdiri-ai/SoduWork)** | 5,993 | [#21](https://github.com/mdiri-ai/SoduWork/graphs/contributors?all=1) | **[1](https://github.com/mdiri-ai/SoduWork/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Recognize CSS imports separated by comments so website deliveries retain transitive stylesheet and image dependencies. [#457](https://github.com/mdiri-ai/SoduWork/pull/457) |
| **[NVIDIA SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator)** | 4,269 | [#5](https://github.com/NVIDIA/SkillEvaluator/graphs/contributors?all=1) | **[16](https://github.com/NVIDIA/SkillEvaluator/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep AST linting iterative for deep valid expressions and reject ambiguous pricing inputs before evaluation budget accounting. [#760](https://github.com/NVIDIA/SkillEvaluator/pull/760) · [#749](https://github.com/NVIDIA/SkillEvaluator/pull/749) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,593 | [#6](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1) | **[22](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct operational-space Coriolis dynamics and arbitrary-axis half-turn residuals used by Python and native inverse kinematics. [#793](https://github.com/petercorke/robotics-toolbox-python/pull/793) · [#796](https://github.com/petercorke/robotics-toolbox-python/pull/796) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,152 | [#5](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1) | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Retain every rollout sample in recurrent and feedforward minibatches, and resume RND exploration schedules consistently from PPO checkpoints. [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[Linger](https://github.com/simplexai-labs/linger)** | 2,906 | [#8](https://github.com/simplexai-labs/linger/graphs/contributors?all=1) | **[26](https://github.com/simplexai-labs/linger/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Prevent canceled installation jobs from starting, drain pending writes during shutdown, and isolate cancellation across shared region probes. [#291](https://github.com/simplexai-labs/linger/pull/291) · [#282](https://github.com/simplexai-labs/linger/pull/282) |
| **[Manifold](https://github.com/elalish/manifold)** | 2,431 | [#8](https://github.com/elalish/manifold/graphs/contributors?all=1) | **[29](https://github.com/elalish/manifold/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct rotation range reduction and skip unrequested curvature channels, preserving geometric results while eliminating unnecessary curvature computation. [#1948](https://github.com/elalish/manifold/pull/1948) · [#1981](https://github.com/elalish/manifold/pull/1981) |
| **[Agentes Chat](https://github.com/agentes-chat/agentes-chat)** | 1,852 | [#9](https://github.com/agentes-chat/agentes-chat/graphs/contributors?all=1) | **[5](https://github.com/agentes-chat/agentes-chat/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Validate embedding identities before mapping vectors to text, and reject inconsistent ZIP metadata before archive imports. [#336](https://github.com/agentes-chat/agentes-chat/pull/336) · [#354](https://github.com/agentes-chat/agentes-chat/pull/354) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,619 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1) | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Restore the least-squares optimum in SVD rigid alignment by correcting only the weakest singular direction when removing reflections. [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,409 | [#5](https://github.com/Denys88/rl_games/graphs/contributors?all=1) | **[22](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve the newest replay transitions under oversized batches and include every occupied slot in prioritized sampling. [#384](https://github.com/Denys88/rl_games/pull/384) · [#393](https://github.com/Denys88/rl_games/pull/393) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,104 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1) | **[15](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | Correct canonical Stiefel projection and Cayley curve derivatives so manifold optimization preserves tangent momentum and consistent line-search slopes. [#280](https://github.com/geoopt/geoopt/pull/280) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,103 | [#3](https://github.com/Toni-SM/skrl/graphs/contributors?all=1) | **[5](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct Gaussian policy variance and TRPO KL divergence, restoring the intended sampling scale, likelihoods and trust-region checks. [#467](https://github.com/Toni-SM/skrl/pull/467) · [#469](https://github.com/Toni-SM/skrl/pull/469) |

### More merged upstream work

| Project | Upstream ★ | Position² | Merged PRs | Representative engineering |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 471,532 | [#67](https://github.com/morluto/rea/graphs/contributors?all=1) | **[6](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Resume buffered NDJSON replies after interrupted iteration and complete partial positional ZIP reads. [#4414](https://github.com/morluto/rea/pull/4414) · [#8909](https://github.com/morluto/rea/pull/8909) |
| **[vLLM](https://github.com/vllm-project/vllm)** | 97,284 | [—](https://github.com/vllm-project/vllm/graphs/contributors?all=1) | **[1](https://github.com/vllm-project/vllm/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Normalize NumPy embedding byte order before tensor conversion, preserving multimodal values and precision across image and video inputs. [#67479](https://github.com/vllm-project/vllm/pull/67479) |
| **[Open Code Review](https://github.com/alibaba/open-code-review)** | 54,794 | [#77](https://github.com/alibaba/open-code-review/graphs/contributors?all=1) | **[2](https://github.com/alibaba/open-code-review/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep finding identity fields separate so review-session comparisons distinguish new, resolved and persisting findings without delimiter collisions. [#1955](https://github.com/alibaba/open-code-review/pull/1955) |
| **[Qwen Code](https://github.com/QwenLM/qwen-code)** | 30,821 | [#49](https://github.com/QwenLM/qwen-code/graphs/contributors?all=1) | **[29](https://github.com/QwenLM/qwen-code/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Share immutable transcript pages and return request-correlated callback errors, improving Java session replay efficiency and control-protocol reliability. [#17113](https://github.com/QwenLM/qwen-code/pull/17113) · [#17115](https://github.com/QwenLM/qwen-code/pull/17115) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 29,002 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1) | **[2](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Apply V-JEPA 2's pairwise RoPE correction to VLA-JEPA's training predictor, restoring norm and relative-position inner-product invariants. [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 27,065 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1) | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep pipeline checkpoints reusable across repeated resumes by isolating mutable visit counters from the saved execution state. [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 22,008 | [#47](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1) | **[3](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep user-provided columns intact during stratified splitting and honor custom user/item identifiers throughout iterative k-core filtering. [#2419](https://github.com/recommenders-team/recommenders/pull/2419) · [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,294 | [#35](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1) | **[6](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Restore ranking-loss gradients for badly ordered pairs and prevent padding from contaminating CNN sentence embeddings. [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [#4323](https://github.com/huggingface/sentence-transformers/pull/4323) |
| **[MuJoCo](https://github.com/google-deepmind/mujoco)** | 18,356 | [—](https://github.com/google-deepmind/mujoco/graphs/contributors?all=1) | **[1](https://github.com/google-deepmind/mujoco/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Restore quintic interpolation for system identification, with regression coverage for polynomial accuracy and endpoint clamping. [#3765](https://github.com/google-deepmind/mujoco/pull/3765) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | 15,769 | [#36](https://github.com/Unstructured-IO/unstructured/graphs/contributors?all=1) | **[9](https://github.com/Unstructured-IO/unstructured/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Make dense XY-cut projections linear in box count plus axis length, and remove repeated table scans during chunk admission. [#4748](https://github.com/Unstructured-IO/unstructured/pull/4748) · [#4744](https://github.com/Unstructured-IO/unstructured/pull/4744) |
| **[CARLA](https://github.com/carla-simulator/carla)** | 14,667 | [#59](https://github.com/carla-simulator/carla/graphs/contributors?all=1) | **[5](https://github.com/carla-simulator/carla/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Support RGB/RGBA texture inputs and partial material updates in CARLA's texture utility. [#10194](https://github.com/carla-simulator/carla/pull/10194) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,402 | [#59](https://github.com/kornia/kornia/graphs/contributors?all=1) | **[10](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stabilize small-root quartic solving and parallel line–plane derivatives, preserving usable roots and finite geometry gradients. [#5474](https://github.com/kornia/kornia/pull/5474) · [#5517](https://github.com/kornia/kornia/pull/5517) |
| **[Betaflight](https://github.com/betaflight/betaflight)** | 11,811 | [—](https://github.com/betaflight/betaflight/graphs/contributors?all=1) | **[1](https://github.com/betaflight/betaflight/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Recover S-record payloads correctly and validate lengths, checksums and address ranges before producing flashable DfuSe images. [#15983](https://github.com/betaflight/betaflight/pull/15983) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 9,011 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1) | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Allocate benchmark cache-flush buffers on the active CUDA device when no explicit device is provided. [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[openMVG](https://github.com/openMVG/openMVG)** | 6,604 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1) | **[1](https://github.com/openMVG/openMVG/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Restore bearing-aware triangulation cheirality so spherical cameras retain valid observations across both front and rear hemispheres. [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,194 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1) | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve separate word and emoticon tokens in the text tokenizer, preventing the first extracted emoticon from merging with the final word. [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,728 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1) | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Apply correspondence weights to the Procrustes covariance, correcting nonuniform-weight rotations while preserving equal-weight fits. [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,535 | [#47](https://github.com/geomstats/geomstats/graphs/contributors?all=1) | **[3](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve automatic differentiation in symmetric-matrix reconstruction and batch axes in pointwise Jacobians and Hessians. [#2235](https://github.com/geomstats/geomstats/pull/2235) · [#2238](https://github.com/geomstats/geomstats/pull/2238) |
| **[Awesome MCP Servers](https://github.com/TensorBlock/awesome-mcp-servers)** | 1,111 | [—](https://github.com/TensorBlock/awesome-mcp-servers/graphs/contributors?all=1) | **[1](https://github.com/TensorBlock/awesome-mcp-servers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Register AI-Memory-Book with installation commands, stdio transport and client metadata in the memory-server directory. [#6055](https://github.com/TensorBlock/awesome-mcp-servers/pull/6055) |

² Same graph settings; per-repository verification dates are recorded in the evidence. `—` means absent from the complete displayed top 100 at the last check. Graph positions and merged PR counts are separate metrics. 41 displayed graphs were rechecked on **2026-11-21**; the remaining 5 retain their earlier complete observations (4 dated 2026-11-19, 1 dated 2026-11-20).

### Code adopted into the default branch

<details>
<summary><b>Maintainer integrations and cherry-picks · verified attribution</b></summary>

These records track adopted source commits separately from directly merged author PRs. [Complete adoption record and scope](docs/CONTRIBUTIONS.md#other-accepted-work).

| Project · ★ | Adopted work / provenance |
|---|---|
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** · 3,593 ★ | Circular particle-heading estimates and trajectory work. [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883) · [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** · 39,543 ★ | 101 source PRs adopted through 11 maintainer integrations. [#1217](https://github.com/storytold/craft-anything/pull/1217) |
| **[Claude-Mem](https://github.com/thedotmack/claude-mem)** · 118,652 ★ | 17 maintainer rehosts preserving 62 author commits. [#6017](https://github.com/thedotmack/claude-mem/pull/6017) · [#6296](https://github.com/thedotmack/claude-mem/pull/6296) |
| **[billion-context](https://github.com/ranxianglei/billion-context)** · 8,031 ★ | Batch integrations with verified source-commit attribution. [#6439](https://github.com/ranxianglei/billion-context/pull/6439) · [#7101](https://github.com/ranxianglei/billion-context/pull/7101) |
| **[OpenMausBot](https://github.com/milind-soni/OpenMausBot)** · 26,211 ★ | One separately credited source commit in a maintainer integration. [#6021](https://github.com/milind-soni/OpenMausBot/pull/6021) |
| **[TD-MPC2](https://github.com/nicklashansen/tdmpc2)** · 1,004 ★ | Preserve target Q history and evaluation mode during conversion. [`332f19e`](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a) |

</details>

## Projects I build

Small tools for concrete engineering problems. Explore a project, try its examples, and star it if it fits your work.

<table>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/anti-rea-forge">Anti-REA Forge</a></strong><br><sub>Native protection · v1.4.0</sub></p>
<p>Seal native data with independently supplied keys and generated C++17/OpenSSL readers. Explore experimental LLVM 18 function virtualization and recorded analyzer controls.</p>
<ul>
<li>Externally keyed native data</li>
<li>Experimental LLVM 18 profiles</li>
</ul>
<p><a href="https://github.com/Afloat16/anti-rea-forge">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/AI-Memory-Book">AI-Memory-Book</a></strong><br><sub>Agent memory · v0.13.0</sub></p>
<p>Give agents shared local memory, organized as project books and task chapters. Opt in to background capture of supported conversations, then use MCP to recall bounded original evidence with source references when continuing earlier work.</p>
<ul>
<li>Opt-in background capture</li>
<li>Cited MCP recall</li>
</ul>
<p><a href="https://github.com/Afloat16/AI-Memory-Book">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/modeldock">ModelDock</a></strong><br><sub>3D &amp; CAD · v0.2.0</sub></p>
<p>Preview, align and compare meshes or point clouds locally. Explore sampled binary PLY/STL previews above 5 GiB and export comparison reports.</p>
<ul>
<li>Multi-model comparison</li>
<li>5+ GiB sampled previews</li>
</ul>
<p><a href="https://github.com/Afloat16/modeldock">Explore &amp; star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/jev-mcp">Jev MCP</a></strong><br><sub>MCP tools · v0.5.0</sub></p>
<p>Bring TypeSafe Jev advice to bounded choices, routing and risk checks through four MCP tools, with installers for multiple coding clients.</p>
<ul>
<li>Four stdio tools</li>
<li>Explicit bounded choices</li>
</ul>
<p><a href="https://github.com/Afloat16/jev-mcp">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/bag-timeline-audit">Bag Timeline Audit</a></strong><br><sub>Robotics</sub></p>
<p>Find timestamp gaps, reversals and duplicates in ROS 2 SQLite or MCAP recordings, then compare topics using an explicitly shared clock.</p>
<ul>
<li>SQLite + MCAP</li>
<li>Integer nanoseconds</li>
</ul>
<p><a href="https://github.com/Afloat16/bag-timeline-audit">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/llm-handshake">LLM Handshake</a></strong><br><sub>LLM interfaces · 0.1.0</sub></p>
<p>Probe OpenAI-compatible endpoints for streaming, tool calls and structured output. Preview exact requests and compare reports after a gateway or model upgrade.</p>
<ul>
<li>Seven focused probes</li>
<li>Request preview</li>
</ul>
<p><a href="https://github.com/Afloat16/llm-handshake">Explore &amp; star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/recontrail">ReconTrail</a></strong><br><sub>Photogrammetry</sub></p>
<p>Check photo quality, reconstruct sparse 3D geometry on a CPU, and share a self-contained interactive report that opens offline.</p>
<ul>
<li>Capture diagnostics</li>
<li>CPU sparse reconstruction</li>
</ul>
<p><a href="https://github.com/Afloat16/recontrail">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/tf-route-audit">TF Route Audit</a></strong><br><sub>Robotics</sub></p>
<p>Check exported TF records and native URDF for cycles, disconnected frames and conflicting edges. Query routes against observed time windows.</p>
<ul>
<li>Native URDF input</li>
<li>Topology diagnostics</li>
</ul>
<p><a href="https://github.com/Afloat16/tf-route-audit">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/sse-toolcall-audit">SSE Toolcall Audit</a></strong><br><sub>LLM interfaces</sub></p>
<p>Reassemble parallel tool calls from saved SSE captures and check completion markers, JSON arguments and consistency with a saved final response.</p>
<ul>
<li>Chat Completions + Responses</li>
<li>Parallel-call assembly</li>
</ul>
<p><a href="https://github.com/Afloat16/sse-toolcall-audit">Explore &amp; star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/pose-convention-bridge">Pose Convention Bridge</a></strong><br><sub>3D geometry</sub></p>
<p>Convert camera poses between OpenCV and OpenGL axes or world-to-camera and camera-to-world forms, with validated transforms and Nerfstudio export.</p>
<ul>
<li>COLMAP + TUM inputs</li>
<li>Rigid-transform checks</li>
</ul>
<p><a href="https://github.com/Afloat16/pose-convention-bridge">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/colmap-model-audit">COLMAP Model Audit</a></strong><br><sub>3D geometry</sub></p>
<p>Audit COLMAP text models for camera-field errors, broken reciprocal tracks and disconnected view graphs, with optional image-path and model-overlap checks.</p>
<ul>
<li>Read-only model checks</li>
<li>Reciprocal track validation</li>
</ul>
<p><a href="https://github.com/Afloat16/colmap-model-audit">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/tooltrace-audit">Tooltrace Audit</a></strong><br><sub>Agent workflows</sub></p>
<p>Review saved execution traces for overlapping retries, duplicate attempts and unmatched results. Add the optional recorder around your own tool calls.</p>
<ul>
<li>Execution + conversation traces</li>
<li>Retry overlap checks</li>
</ul>
<p><a href="https://github.com/Afloat16/tooltrace-audit">Explore &amp; star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/research-to-fix">Research to Fix</a></strong><br><sub>Research workflow</sub></p>
<p>Research similar failures, map relevant solutions to your code and verify the repair. Save cases with source links and before-and-after evidence.</p>
<ul>
<li>Source-backed diagnosis</li>
<li>Local applicability checks</li>
</ul>
<p><a href="https://github.com/Afloat16/research-to-fix">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/debate-direction">Debate Direction</a></strong><br><sub>Agent workflows</sub></p>
<p>Let two agents propose, challenge and revise a plan. Keep the objections, remaining disagreements and next validation steps in a reviewable report.</p>
<ul>
<li>Persistent proposer + critic</li>
<li>Issue ledger</li>
</ul>
<p><a href="https://github.com/Afloat16/debate-direction">Explore &amp; star →</a></p>
</td>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/ai-dev-steward">StewardCheck</a></strong><br><sub>Coding workflow · 0.2.0 Alpha</sub></p>
<p>Pin a task baseline, inspect edits against the agreed scope and keep test receipts tied to the files they actually checked.</p>
<ul>
<li>Task-scoped Git checks</li>
<li>Workspace fingerprints</li>
</ul>
<p><a href="https://github.com/Afloat16/ai-dev-steward">Explore &amp; star →</a></p>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<p><strong><a href="https://github.com/Afloat16/agent-action-notifier">Agent Action Notifier</a></strong><br><sub>Agent workflows · v0.2.0</sub></p>
<p>Turn explicit workflow events into queued email or desktop alerts, with pending-request tracking, retries and recovery after interrupted delivery.</p>
<ul>
<li>SQLite outbox</li>
<li>Email + desktop channels</li>
</ul>
<p><a href="https://github.com/Afloat16/agent-action-notifier">Explore &amp; star →</a></p>
</td>
</tr>
</table>

I isolate the symptom, understand the boundary, write a regression, and make the result inspectable. The [six domain utilities](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md#validation-for-this-release) have **67 local tests and 36 passing OS/Python CI combinations** at the recorded release. These are experimental diagnostics and conversion tools; each repository documents its limits.

<details>
<summary><b>All 16 projects: stars and default-branch commits</b></summary>

Snapshot: **2026-11-21**. Sorted by stars, then repository commit count. Commits count reachable default-branch history, including merge commits; they are not personal authored-commit counts. [Sources and versions](docs/PROJECTS.md).

| Project | ★ | Default-branch commits | Main language |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [9](https://github.com/Afloat16/anti-rea-forge/stargazers) | [40](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [AI-Memory-Book](https://github.com/Afloat16/AI-Memory-Book) | [4](https://github.com/Afloat16/AI-Memory-Book/stargazers) | [1,025](https://github.com/Afloat16/AI-Memory-Book/commits/main/) | Python |
| [Research to Fix](https://github.com/Afloat16/research-to-fix) | [2](https://github.com/Afloat16/research-to-fix/stargazers) | [7](https://github.com/Afloat16/research-to-fix/commits/main/) | Python |
| [ModelDock](https://github.com/Afloat16/modeldock) | [2](https://github.com/Afloat16/modeldock/stargazers) | [6](https://github.com/Afloat16/modeldock/commits/main/) | TypeScript |
| [Jev MCP](https://github.com/Afloat16/jev-mcp) | [1](https://github.com/Afloat16/jev-mcp/stargazers) | [49](https://github.com/Afloat16/jev-mcp/commits/main/) | TypeScript |
| [StewardCheck](https://github.com/Afloat16/ai-dev-steward) | [1](https://github.com/Afloat16/ai-dev-steward/stargazers) | [11](https://github.com/Afloat16/ai-dev-steward/commits/main/) | Python |
| [Debate Direction](https://github.com/Afloat16/debate-direction) | [1](https://github.com/Afloat16/debate-direction/stargazers) | [8](https://github.com/Afloat16/debate-direction/commits/main/) | Python |
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

[Project guide](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.md) · [Demand research](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md) · [Project metrics](docs/PROJECTS.md) · [Contribution record](docs/CONTRIBUTIONS.md)


