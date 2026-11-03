<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/banner-2026-10-30-light.svg?v=2" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

**My research focuses on robotics, large language models, and 3D reconstruction.**

I build reproducible research tools, explore native software protection, and contribute focused upstream fixes.

Python · TypeScript · C/C++ · Reproducible experiments · Upstream engineering

[My projects](#projects-i-build) · [Upstream contributions](#open-source-contributions) · [简体中文](README.zh-CN.md)

</div>

## Open-source contributions

**116 verified merged author PRs across 28 upstream repositories**, spanning robotics, machine learning, geometry and developer tools. Snapshot: **3 November 2026 · 17:04 CST (UTC+8)**.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-03-1704-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/main/assets/stats-2026-11-03-1704-light.svg?v=2" alt="116 verified merged upstream PRs across 28 repositories. Snapshot: 3 November 2026 · 17:04 CST (UTC+8)." width="100%">
</picture>

### Recent selected merges

**Five recent, substantive code contributions**, ordered by merge time. Each links to its merged PR and upstream commit, with current project stars verified. Selection emphasizes numerical correctness, evaluation metrics, tensor alignment and API behavior. Dates use Asia/Shanghai.

| Merged | Upstream project · ★ | Engineering contribution | PR / merged commit |
|---|---|---|---|
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,139 ★ | Make benchmark translation-angle errors invariant to reconstruction scale. | [#4932](https://github.com/colmap/colmap/pull/4932)<br>[`27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd) |
| 2026-11-02 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,251 ★ | Preserve padded LSTM sequence lengths so token outputs stay aligned with companion features. | [#4301](https://github.com/huggingface/sentence-transformers/pull/4301)<br>[`26a0f49`](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c) |
| 2026-11-01 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,639 ★ | Preserve consistent result structure for empty, singleton and multi-image representation batches. | [#1675](https://github.com/serengil/deepface/pull/1675)<br>[`8e565c0`](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,658 ★ | Apply the established pairwise RoPE correction to VLA-JEPA's training-only world predictor. | [#4835](https://github.com/huggingface/lerobot/pull/4835)<br>[`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |
| 2026-10-22 | **[REA](https://github.com/morluto/rea)**<br>424,474 ★ | Complete short positional ZIP reads and report premature EOF as an integrity failure. | [#4414](https://github.com/morluto/rea/pull/4414)<br>[`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33) |

### Latest verified top-30 contributor positions

**18 upstream projects with verified top-30 positions**, all checked in this refresh. Craft Anything is now **#4†**, up from #7 in the same all-time graph. Each rank carries its verification date; groups are sorted by current stars.

| Project | Upstream ★ | Position · checked¹ | Merged PRs | Representative work |
|---|---:|---:|---:|---|
| **[DeepFace](https://github.com/serengil/deepface)** | 23,639 | [#7](https://api.github.com/repos/serengil/deepface/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[21](https://github.com/serengil/deepface/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Face-box clipping, crop boundaries, normalization and vector-search correctness. [#1655](https://github.com/serengil/deepface/pull/1655) · [#1658](https://github.com/serengil/deepface/pull/1658) |
| **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)** | 19,251 | [#30](https://api.github.com/repos/huggingface/sentence-transformers/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[5](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Ranking gradients, encoder masks and float16 quantization. [#4127](https://github.com/huggingface/sentence-transformers/pull/4127) |
| **[Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch)** | 10,724 | [#9](https://api.github.com/repos/lucidrains/denoising-diffusion-pytorch/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[1](https://github.com/lucidrains/denoising-diffusion-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve external conditioning and self-conditioning in 1D diffusion. [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| **[PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning)** | 6,343 | [#9](https://api.github.com/repos/KevinMusgrave/pytorch-metric-learning/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[3](https://github.com/KevinMusgrave/pytorch-metric-learning/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stable NT-Xent losses and gradients; independent HistogramLoss and PNP regression coverage. [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) · [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759) |
| **[Atomic Agents](https://github.com/Eigenwise/atomic-agents)** | 6,315 | [#28](https://api.github.com/repos/Eigenwise/atomic-agents/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[1](https://github.com/Eigenwise/atomic-agents/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep existing chat history intact when loading fails. [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| **[Craft Anything](https://github.com/storytold/craft-anything)** | 5,566 | [#4†](https://github.com/storytold/craft-anything/graphs/contributors?all=1)<br><sub>2026-11-03</sub> | **[19](https://github.com/storytold/craft-anything/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | ARM32 value-flow correctness and WebAssembly exported-tag signature comparison. [#436](https://github.com/storytold/craft-anything/pull/436) · [#441](https://github.com/storytold/craft-anything/pull/441) |
| **[Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python)** | 3,560 | [#6](https://api.github.com/repos/petercorke/robotics-toolbox-python/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[11](https://github.com/petercorke/robotics-toolbox-python/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Kinematics, dynamics, inverse kinematics and URDF correctness. [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801) |
| **[RSL-RL](https://github.com/leggedrobotics/rsl_rl)** | 3,115 | [#5](https://api.github.com/repos/leggedrobotics/rsl_rl/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[3](https://github.com/leggedrobotics/rsl_rl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Resume RND schedules, preserve reward history and retain rollout remainders. [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| **[PyPose](https://github.com/pypose/pypose)** | 1,620 | [#15](https://api.github.com/repos/pypose/pypose/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[4](https://github.com/pypose/pypose/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Least-squares rigid alignment, robust-kernel stability and camera broadcasting. [#437](https://github.com/pypose/pypose/pull/437) |
| **[RL Games](https://github.com/Denys88/rl_games)** | 1,409 | [#6](https://api.github.com/repos/Denys88/rl_games/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[4](https://github.com/Denys88/rl_games/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Retain the newest transitions in oversized replay batches. [#384](https://github.com/Denys88/rl_games/pull/384) |
| **[Geoopt](https://github.com/geoopt/geoopt)** | 1,103 | [#3](https://api.github.com/repos/geoopt/geoopt/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[10](docs/CONTRIBUTIONS.md#complete-merged-pr-index)** | Manifold constraints, gradient projection, optimizer state and stable geometry. [#267](https://github.com/geoopt/geoopt/pull/267) · [#254](https://github.com/geoopt/geoopt/pull/254) |
| **[skrl](https://github.com/Toni-SM/skrl)** | 1,102 | [#3](https://api.github.com/repos/Toni-SM/skrl/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[3](https://github.com/Toni-SM/skrl/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Gaussian policy math and cross-backend exploration consistency. [#475](https://github.com/Toni-SM/skrl/pull/475) |
| **[pytransform3d](https://github.com/dfki-ric/pytransform3d)** | 707 | [#15](https://api.github.com/repos/dfki-ric/pytransform3d/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[2](https://github.com/dfki-ric/pytransform3d/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Stable Lie-group Jacobians and screw-axis translation handling. [#389](https://github.com/dfki-ric/pytransform3d/pull/389) |
| **[RoMa](https://github.com/naver/roma)** | 647 | [#2](https://api.github.com/repos/naver/roma/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[4](https://github.com/naver/roma/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Quaternion broadcasting, affine shapes and reproducible sampling. [#33](https://github.com/naver/roma/pull/33) |
| **[Rectified Flow](https://github.com/lucidrains/rectified-flow-pytorch)** | 490 | [#3](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[1](https://github.com/lucidrains/rectified-flow-pytorch/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep NanoFlow inversion in normalized flow coordinates. [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| **[KinPy](https://github.com/neka-nat/kinpy)** | 181 | [#2](https://api.github.com/repos/neka-nat/kinpy/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[3](https://github.com/neka-nat/kinpy/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | World-frame Jacobians with consistent axes and link offsets. [#29](https://github.com/neka-nat/kinpy/pull/29) |
| **[Elements](https://github.com/danijar/elements)** | 73 | [#3](https://api.github.com/repos/danijar/elements/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[2](https://github.com/danijar/elements/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve hidden filenames and correct local-path operations. [#19](https://github.com/danijar/elements/pull/19) |
| **[qpmpc](https://github.com/stephane-caron/qpmpc)** | 56 | [#2](https://api.github.com/repos/stephane-caron/qpmpc/contributors?per_page=100&anon=false)<br><sub>2026-11-03</sub> | **[3](https://github.com/stephane-caron/qpmpc/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve absent constraints, objective scaling and stable pendulum discretization. [#15](https://github.com/stephane-caron/qpmpc/pull/15) · [#17](https://github.com/stephane-caron/qpmpc/pull/17) |

### More merged upstream work

| Project | Upstream ★ | Position · checked¹ | Merged PRs | Representative work |
|---|---:|---:|---:|---|
| **[REA](https://github.com/morluto/rea)** | 424,474 | [#91](https://api.github.com/repos/morluto/rea/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-03</sub> | **[3](https://github.com/morluto/rea/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Deduplicate setup clients, complete ZIP reads and validate CDP response encoding. [#4414](https://github.com/morluto/rea/pull/4414) · [#4524](https://github.com/morluto/rea/pull/4524) |
| **[LeRobot](https://github.com/huggingface/lerobot)** | 28,658 | [#227](https://api.github.com/repos/huggingface/lerobot/contributors?per_page=100&anon=false&page=3)<br><sub>2026-11-03</sub> | **[1](https://github.com/huggingface/lerobot/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct pairwise RoPE frequencies in VLA-JEPA's training-only predictor. [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| **[Haystack](https://github.com/deepset-ai/haystack)** | 26,917 | [#365](https://api.github.com/repos/deepset-ai/haystack/contributors?per_page=100&anon=false&page=4)<br><sub>2026-11-03</sub> | **[1](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Keep pipeline snapshots reusable after a resumed run. [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| **[Recommenders](https://github.com/recommenders-team/recommenders)** | 21,975 | [#49](https://api.github.com/repos/recommenders-team/recommenders/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-03</sub> | **[2](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Preserve custom columns and reject invalid top-k values. [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| **[COLMAP](https://github.com/colmap/colmap)** | 13,139 | [#55](https://api.github.com/repos/colmap/colmap/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-03</sub> | **[2](https://github.com/colmap/colmap/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Scale-invariant translation-angle evaluation and benchmark path resolution. [#4932](https://github.com/colmap/colmap/pull/4932) · [#4931](https://github.com/colmap/colmap/pull/4931) |
| **[Kornia](https://github.com/kornia/kornia)** | 12,254 | [#134](https://api.github.com/repos/kornia/kornia/contributors?per_page=100&anon=false&page=2)<br><sub>2026-11-03</sub> | **[3](https://github.com/kornia/kornia/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Finite geometry gradients and stable small-root quartics. [#5517](https://github.com/kornia/kornia/pull/5517) |
| **[TileLang](https://github.com/tile-ai/tilelang)** | 8,893 | [#210](https://api.github.com/repos/tile-ai/tilelang/contributors?per_page=100&anon=false&page=3)<br><sub>2026-11-03</sub> | **[1](https://github.com/tile-ai/tilelang/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Honor the current CUDA device in profiling. [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| **[MLxtend](https://github.com/rasbt/mlxtend)** | 5,190 | [#95](https://api.github.com/repos/rasbt/mlxtend/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-03</sub> | **[1](https://github.com/rasbt/mlxtend/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Separate extracted emoticons from the preceding final word. [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| **[Trimesh](https://github.com/mikedh/trimesh)** | 3,715 | — | **[1](https://github.com/mikedh/trimesh/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Correct nonuniform weighted Procrustes rotation while preserving equal-weight fits; merged into `release/angles`. [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| **[Geomstats](https://github.com/geomstats/geomstats)** | 1,528 | [#84](https://api.github.com/repos/geomstats/geomstats/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-03</sub> | **[1](https://github.com/geomstats/geomstats/pulls?q=is%3Apr%20author%3AAfloat16%20is%3Amerged)** | Propagate product-metric parallel transport to each factor. [#2131](https://github.com/geomstats/geomstats/pull/2131) |

¹ Unless marked †, positions follow GitHub’s commit-sorted REST contributor list, including bots and excluding anonymous contributors; ties retain API order. All 27 numerical REST positions were rechecked on 3 November 2026. † Craft Anything uses GitHub’s **all-time contributors graph for `main`, excluding merge commits**, checked in this refresh. `—` means no numerical position is available; Afloat16 was absent from the complete retrieved Trimesh contributor list. Stars and PR counts were refreshed on 3 November; PR metadata was checked directly. [Full PR record, methodology and data](docs/CONTRIBUTIONS.md).

### Code adopted into the default branch

**[TD-MPC2](https://github.com/nicklashansen/tdmpc2)** (995 ★, contributor-list position [#3](https://api.github.com/repos/nicklashansen/tdmpc2/contributors?per_page=100&anon=false)): preserve target-Q history and evaluation mode during model conversion. The implementation from [#98](https://github.com/nicklashansen/tdmpc2/pull/98) was [cherry-picked with Afloat16 authorship](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a); the original PR was closed without merging. Together with the repositories above, this makes **29 upstream projects with accepted contributions**.

Robotics Toolbox also incorporated the circular particle-heading work from [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) into [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883), and the trajectory work from [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) into [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805), retaining co-authorship. These adoptions are recorded separately from the 116 merged author PRs. [Details](docs/CONTRIBUTIONS.md#other-accepted-work).

## Projects I build

**[Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge)** · **MIT · 0.4.0 Alpha**<br>
Native release hardening with CMake-ready build integration, PE/ELF checks, guarded C++ memory and one-use request authorization. Explore runnable examples, cross-platform CI and research-guided design. [Project story](https://github.com/Afloat16/anti-rea-forge/blob/main/docs/community/PROJECT_STORY.md) · [Join the community](https://github.com/Afloat16/anti-rea-forge/issues/1).

**[ModelDock](https://github.com/Afloat16/modeldock)** · **[v0.2.0](https://github.com/Afloat16/modeldock/releases/tag/v0.2.0)**<br>
Local 3D/CAD preview with bounded 5+ GiB binary PLY/STL sampling, multi-model alignment and reference comparison. [Validation record](https://github.com/Afloat16/modeldock/blob/main/docs/validation.md).

### Robotics · LLMs · 3D reconstruction

| Robotics | Large language models | 3D reconstruction |
|---|---|---|
| **[Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit)**<br>Read-only ROS 2 SQLite/MCAP timestamp diagnostics. | **[LLM Handshake](https://github.com/Afloat16/llm-handshake)**<br>Bounded OpenAI-compatible endpoint probes and report comparisons. | **[ReconTrail](https://github.com/Afloat16/recontrail)**<br>CPU photogrammetry, sparse geometry and offline reports. |
| **[TF Route Audit](https://github.com/Afloat16/tf-route-audit)**<br>Exported TF and native URDF topology/time-window checks. | **[SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit)** and **[Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit)**<br>Saved stream and tool-execution diagnostics. | **[Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge)** and **[COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit)**<br>Explicit pose conversion and text-model preflight. |

**[Jev MCP](https://github.com/Afloat16/jev-mcp)** · [v0.5.0](https://github.com/Afloat16/jev-mcp/releases/tag/v0.5.0): a TypeScript MCP server for bounded probabilistic advice, routing and risk signals, with cross-client installers.

Research and engineering workflow: [Research to Fix](https://github.com/Afloat16/research-to-fix) · [Debate Direction](https://github.com/Afloat16/debate-direction) · [StewardCheck](https://github.com/Afloat16/ai-dev-steward/tree/main/tools/stewardcheck) · [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier).

**How I work:** isolate the symptom, understand the boundary, write a regression, and make the result inspectable. The [six domain utilities](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md#validation-for-this-release) have **67 local tests and 36 passing OS/Python CI combinations** at the recorded release. These are experimental diagnostics and conversion tools; each repository documents its limits.

<details>
<summary><b>All 15 projects: stars and default-branch commits</b></summary>

Snapshot: **3 November 2026 · 17:04 CST (UTC+8)**. Sorted by stars, then repository commit count. Commits count reachable default-branch history, including merge commits; they are not personal authored-commit counts. [Sources and versions](docs/PROJECTS.md).

| Project | ★ | Default-branch commits | Main language |
|---|---:|---:|---|
| [Anti-REA Forge](https://github.com/Afloat16/anti-rea-forge) | [3](https://github.com/Afloat16/anti-rea-forge/stargazers) | [12](https://github.com/Afloat16/anti-rea-forge/commits/main/) | Python |
| [Jev MCP](https://github.com/Afloat16/jev-mcp) | [1](https://github.com/Afloat16/jev-mcp/stargazers) | [49](https://github.com/Afloat16/jev-mcp/commits/main/) | TypeScript |
| [StewardCheck](https://github.com/Afloat16/ai-dev-steward) | [1](https://github.com/Afloat16/ai-dev-steward/stargazers) | [11](https://github.com/Afloat16/ai-dev-steward/commits/main/) | Python |
| [Debate Direction](https://github.com/Afloat16/debate-direction) | [1](https://github.com/Afloat16/debate-direction/stargazers) | [8](https://github.com/Afloat16/debate-direction/commits/main/) | Python |
| [LLM Handshake](https://github.com/Afloat16/llm-handshake) | [1](https://github.com/Afloat16/llm-handshake/stargazers) | [6](https://github.com/Afloat16/llm-handshake/commits/main/) | Python |
| [ModelDock](https://github.com/Afloat16/modeldock) | [1](https://github.com/Afloat16/modeldock/stargazers) | [6](https://github.com/Afloat16/modeldock/commits/main/) | TypeScript |
| [Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit) | [1](https://github.com/Afloat16/bag-timeline-audit/stargazers) | [5](https://github.com/Afloat16/bag-timeline-audit/commits/main/) | Python |
| [ReconTrail](https://github.com/Afloat16/recontrail) | [1](https://github.com/Afloat16/recontrail/stargazers) | [5](https://github.com/Afloat16/recontrail/commits/main/) | Python |
| [Research to Fix](https://github.com/Afloat16/research-to-fix) | [1](https://github.com/Afloat16/research-to-fix/stargazers) | [5](https://github.com/Afloat16/research-to-fix/commits/main/) | Python |
| [SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit) | [1](https://github.com/Afloat16/sse-toolcall-audit/stargazers) | [5](https://github.com/Afloat16/sse-toolcall-audit/commits/main/) | Python |
| [TF Route Audit](https://github.com/Afloat16/tf-route-audit) | [1](https://github.com/Afloat16/tf-route-audit/stargazers) | [5](https://github.com/Afloat16/tf-route-audit/commits/main/) | Python |
| [Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit) | [1](https://github.com/Afloat16/tooltrace-audit/stargazers) | [5](https://github.com/Afloat16/tooltrace-audit/commits/main/) | Python |
| [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier) | [0](https://github.com/Afloat16/agent-action-notifier/stargazers) | [6](https://github.com/Afloat16/agent-action-notifier/commits/main/) | Python |
| [COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit) | [0](https://github.com/Afloat16/colmap-model-audit/stargazers) | [4](https://github.com/Afloat16/colmap-model-audit/commits/main/) | Python |
| [Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge) | [0](https://github.com/Afloat16/pose-convention-bridge/stargazers) | [4](https://github.com/Afloat16/pose-convention-bridge/commits/main/) | Python |

</details>

---

[Project guide](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.md) · [Demand research](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md) · [Project metrics](docs/PROJECTS.md) · [Contribution record](docs/CONTRIBUTIONS.md)

