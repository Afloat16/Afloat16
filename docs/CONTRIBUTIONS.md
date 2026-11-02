# Upstream contribution record

Snapshot: **2 November 2026**. Account: [Afloat16](https://github.com/Afloat16). Display dates: **Asia/Shanghai**; machine-readable timestamps retain UTC.

**96 verified merged author PRs · 26 upstream repositories · 17 latest verified top-30 contributor-list positions**

TD-MPC2 adds one separately verified authored-code adoption, for **27 upstream projects with accepted contributions**. Across the merged PRs, **39 are in 9 repositories with more than 10,000 current stars**. The five profile highlights are an editorial selection from this set.

## Verification method

- The `author:Afloat16 is:pr is:merged -user:Afloat16` search returned **94 results** with `incomplete_results=false`. An independent all-status author-PR search returned **581 unique PRs across 6 pages, ordered by creation time**; **96** had `pull_request.merged_at`. Geoopt [#258](https://github.com/geoopt/geoopt/pull/258) and [#259](https://github.com/geoopt/geoopt/pull/259) were missing from the merged-only search index. Every counted PR was checked at its direct REST endpoint for `merged=true`, author `Afloat16` and a merge timestamp. All 82 records from the previous snapshot remain in the inventory, with 14 newly verified merges. Default-branch author-commit lists were independently enumerated for all 27 accepted-contribution repositories. The result is a verified inventory at retrieval time, not a guarantee against future indexing changes.
- Only public upstream repositories are counted. Account-owned PRs, unmerged PRs and maintainer-authored integration PRs are excluded. Counts include code, tests and documentation; they do not imply 96 separate bug fixes.
- Stars come from official repository metadata and belong to the upstream projects. They are not stars earned by my own repositories and do not measure an individual contribution's quality.
- Contributor positions are **one-based positions** in GitHub's `/repos/{owner}/{repo}/contributors?per_page=100&anon=false` responses, ordered by commit contributions, including bots and excluding anonymous contributors. Pagination offsets are included when later pages are retrieved. Equal counts retain GitHub's returned order. These are not PR-count rankings, maintainer roles, lines-of-code rankings or quality assessments.
- GitHub may cache contributor data. Its email-to-account attribution also has documented limits. `—` means no verified entry in the pages retrieved, not zero commits and not a fabricated numerical rank. The snapshot records retrieval status, pages, counts and source URLs.
- The full index’s **Current author commits** column uses the independently enumerated `/commits?author=Afloat16` default-branch history, refreshed on 2 November. The total is **109 authored commits across 27 accepted-contribution repositories**: 108 in the 26 merged-PR repositories below and 1 in TD-MPC2. This can differ from contributor statistics and is not the count used to determine the contributor position. The full index retains both metrics.
- **25 of 27 contributor positions were rechecked on 2 November.** Haystack retains **#365 / 1 contribution**, and TileLang retains **#210 / 1 contribution**, from their **30 October** verification. This refresh reached Haystack's first three pages and TileLang's first page before the public API quota was exhausted; those partial responses do not establish new exact positions. Their rank links point to the unchanged historical snapshot and retain the original verification date. All **17 top-30 merged-PR projects** have current verification dates. TD-MPC2 is separately listed at current #3. The machine-readable snapshot preserves per-repository retrieval times, page offsets and source URLs.
- The homepage preserves top-30 placements first and sorts each group by current stars. The five selected merges require **current stars >10,000**, verified authorship and merged state, and an inspected production diff with a substantive correctness or state-management change. They are sorted by `merged_at`, not PR creation or last update time, and are not claimed to be the newest five consecutive PRs.
- PyTorch Metric Learning adds **3 merged author PRs and 6 authored commits**. Its aggregate PR diffs include other contributors' v3 work; the whole release or complete aggregate diff is not attributed to Afloat16. The authored commits and their associations with [#756](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/756), [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) and [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759) were checked separately.

Sources: [Contributor API documentation](https://docs.github.com/en/rest/repos/repos#list-repository-contributors) · [Author PR search](https://github.com/search?q=author%3AAfloat16%20is%3Apr%20-user%3AAfloat16&type=pullrequests) · [Current source snapshot](contributions-2026-11-02.json) · [Previous record](CONTRIBUTIONS-2026-10-30.md).

This refresh checks public metadata and the newly selected merged implementations and attribution. It does not rerun upstream test suites or enlarge the original PRs' validation claims.

## Five recent selected merges

| Merged | Upstream project · ★ | Engineering contribution | PR / merged commit |
|---|---|---|---|
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,131 ★ | Make benchmark translation-angle errors invariant to reconstruction scale. | [#4932](https://github.com/colmap/colmap/pull/4932)<br>[`27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd) |
| 2026-11-02 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,247 ★ | Preserve padded LSTM sequence lengths so token outputs stay aligned with companion features. | [#4301](https://github.com/huggingface/sentence-transformers/pull/4301)<br>[`26a0f49`](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c) |
| 2026-11-01 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,635 ★ | Preserve consistent result structure for empty, singleton and multi-image representation batches. | [#1675](https://github.com/serengil/deepface/pull/1675)<br>[`8e565c0`](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,645 ★ | Apply the established pairwise RoPE correction to VLA-JEPA's training-only world predictor. | [#4835](https://github.com/huggingface/lerobot/pull/4835)<br>[`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |
| 2026-10-22 | **[REA](https://github.com/morluto/rea)**<br>420,907 ★ | Complete short positional ZIP reads and report premature EOF as an integrity failure. | [#4414](https://github.com/morluto/rea/pull/4414)<br>[`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33) |

### COLMAP #4932

Scales finite nonzero vectors by their maximum absolute component before normalization, avoiding tiny-norm floors and overflow while preserving zero-vector behavior.

Scope: Changes benchmark pose-error evaluation, not the reconstruction solver or reconstructed-model quality. Final merged tests are geometry_test.py and utils_test.py; the PR body's original test-command path differs from the final files. This refresh did not rerun tests.

Evidence: [merged PR](https://github.com/colmap/colmap/pull/4932) · [upstream commit](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd); merge commit author: `Afloat16`.

### Sentence Transformers #4301

Passes the original padded width as total_length when unpacking packed recurrent sequences, preventing batch-dependent shortening of token_embeddings.

Scope: The final merged diff contains only the production LSTM module; preparation-time regression results should not be described as tests added in the merged patch. No GPU DataParallel or model-quality improvement is claimed.

Evidence: [merged PR](https://github.com/huggingface/sentence-transformers/pull/4301) · [upstream commit](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c); merge commit author: `Afloat16`.

### DeepFace #1675

Determines batch shape from input form rather than length; keeps scalar-image output flat, retains the outer batch dimension for list/4D inputs and returns empty batches before loading a model.

Scope: Corrects the representation API's batch structure; the singleton-batch output shape intentionally changes. The merged regression uses SFace inference; no recognition-accuracy improvement is claimed.

Evidence: [merged PR](https://github.com/serengil/deepface/pull/1675) · [upstream commit](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac); merge commit author: `Afloat16`.

### LeRobot #4835

Rotary position geometry; norm, inner-product and relative-position invariants; single-frequency broadcasting.

Scope: Correction originated in echosprint's V-JEPA 2 PR #15; not an original algorithm. The final merged diff contains the production helper and documentation, without new regression tests. This affects the training-only predictor: checkpoint outputs and losses change; no pretrained-quality or real-robot performance claim. This selection review did not rerun tests.

Evidence: [merged PR](https://github.com/huggingface/lerobot/pull/4835) · [upstream commit](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693); merge commit author: `Afloat16`.

### REA #4414

Low-level I/O correctness: accumulate partial reads with consistent buffer and file offsets, detect premature EOF, and preserve existing allocation and read-budget checks. Regressions exercise real ZIP parsing and extraction through actual file descriptors.

Scope: Archive-reader correctness, with no throughput or expanded security-boundary claim. Short reads are injected on real descriptors. Full-suite, cross-platform and forced-short-read public CLI/MCP coverage are not established by the PR; this selection review did not rerun tests.

Evidence: [merged PR](https://github.com/morluto/rea/pull/4414) · [upstream commit](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33); merge commit author: `Afloat16`.

Recent candidates retained in the full record but not highlighted:

- [tile-ai/tilelang #3357](https://github.com/tile-ai/tilelang/pull/3357): 8,885 stars is below the strict >10,000 threshold.
- [recommenders-team/recommenders #2388](https://github.com/recommenders-team/recommenders/pull/2388): Valid basic input validation; retained in the full record, with recent numerical and batch-contract fixes prioritized for the highlights.
- [morluto/rea #3919](https://github.com/morluto/rea/pull/3919): Valid client-list deduplication; retained in the full record, with recent numerical and batch-contract fixes prioritized for the highlights.
- [colmap/colmap #4931](https://github.com/colmap/colmap/pull/4931): Useful benchmark path resolution, but the final production diff is a basic two-path resolve operation; the numerical geometry fix better represents technical depth.
- [serengil/deepface #1677](https://github.com/serengil/deepface/pull/1677): Useful thin-image boundary fix; the batch-contract and numerical-gradient fixes are prioritized for this five-item technical selection.
- [serengil/deepface #1676](https://github.com/serengil/deepface/pull/1676): Corrects width/height metadata assignment; lower priority than the broader batch-contract fix.
- [KevinMusgrave/pytorch-metric-learning #758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758): Substantive NT-Xent value/gradient stability contribution, but the current 6,342 stars is below the strict >10,000 threshold.

## Complete merged-PR index

| Upstream repository | Stars | Position · checked | Contributor-list count | Current author commits | Merged PRs | Source PRs |
|---|---:|---:|---:|---:|---:|---|
| [serengil/deepface](https://github.com/serengil/deepface) | 23,635 | [#7](https://api.github.com/repos/serengil/deepface/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 21 | 21 | 21 | [#1677](https://github.com/serengil/deepface/pull/1677), [#1676](https://github.com/serengil/deepface/pull/1676), [#1675](https://github.com/serengil/deepface/pull/1675), [#1658](https://github.com/serengil/deepface/pull/1658), [#1655](https://github.com/serengil/deepface/pull/1655), [#1651](https://github.com/serengil/deepface/pull/1651), [#1653](https://github.com/serengil/deepface/pull/1653), [#1652](https://github.com/serengil/deepface/pull/1652), [#1649](https://github.com/serengil/deepface/pull/1649), [#1654](https://github.com/serengil/deepface/pull/1654), [#1648](https://github.com/serengil/deepface/pull/1648), [#1646](https://github.com/serengil/deepface/pull/1646), [#1647](https://github.com/serengil/deepface/pull/1647), [#1643](https://github.com/serengil/deepface/pull/1643), [#1644](https://github.com/serengil/deepface/pull/1644), [#1634](https://github.com/serengil/deepface/pull/1634), [#1638](https://github.com/serengil/deepface/pull/1638), [#1636](https://github.com/serengil/deepface/pull/1636), [#1633](https://github.com/serengil/deepface/pull/1633), [#1631](https://github.com/serengil/deepface/pull/1631), [#1630](https://github.com/serengil/deepface/pull/1630) |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | 19,247 | [#30](https://api.github.com/repos/huggingface/sentence-transformers/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 5 | 5 | 5 | [#4114](https://github.com/huggingface/sentence-transformers/pull/4114), [#4301](https://github.com/huggingface/sentence-transformers/pull/4301), [#4127](https://github.com/huggingface/sentence-transformers/pull/4127), [#4116](https://github.com/huggingface/sentence-transformers/pull/4116), [#4113](https://github.com/huggingface/sentence-transformers/pull/4113) |
| [lucidrains/denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) | 10,724 | [#9](https://api.github.com/repos/lucidrains/denoising-diffusion-pytorch/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 1 | 1 | 1 | [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| [KevinMusgrave/pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning) | 6,342 | [#9](https://api.github.com/repos/KevinMusgrave/pytorch-metric-learning/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 6 | 6 | 3 | [#756](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/756), [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759), [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) |
| [Eigenwise/atomic-agents](https://github.com/Eigenwise/atomic-agents) | 6,313 | [#28](https://api.github.com/repos/Eigenwise/atomic-agents/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 2 | 2 | 1 | [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| [petercorke/robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) | 3,558 | [#6](https://api.github.com/repos/petercorke/robotics-toolbox-python/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 11 | 11 | 11 | [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801), [#800](https://github.com/petercorke/robotics-toolbox-python/pull/800), [#799](https://github.com/petercorke/robotics-toolbox-python/pull/799), [#798](https://github.com/petercorke/robotics-toolbox-python/pull/798), [#797](https://github.com/petercorke/robotics-toolbox-python/pull/797), [#796](https://github.com/petercorke/robotics-toolbox-python/pull/796), [#795](https://github.com/petercorke/robotics-toolbox-python/pull/795), [#794](https://github.com/petercorke/robotics-toolbox-python/pull/794), [#793](https://github.com/petercorke/robotics-toolbox-python/pull/793), [#792](https://github.com/petercorke/robotics-toolbox-python/pull/792), [#719](https://github.com/petercorke/robotics-toolbox-python/pull/719) |
| [leggedrobotics/rsl_rl](https://github.com/leggedrobotics/rsl_rl) | 3,114 | [#5](https://api.github.com/repos/leggedrobotics/rsl_rl/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 3 | 3 | 3 | [#244](https://github.com/leggedrobotics/rsl_rl/pull/244), [#240](https://github.com/leggedrobotics/rsl_rl/pull/240), [#239](https://github.com/leggedrobotics/rsl_rl/pull/239) |
| [pypose/pypose](https://github.com/pypose/pypose) | 1,620 | [#15](https://api.github.com/repos/pypose/pypose/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 6 | 6 | 4 | [#437](https://github.com/pypose/pypose/pull/437), [#415](https://github.com/pypose/pypose/pull/415), [#416](https://github.com/pypose/pypose/pull/416), [#417](https://github.com/pypose/pypose/pull/417) |
| [Denys88/rl_games](https://github.com/Denys88/rl_games) | 1,409 | [#6](https://api.github.com/repos/Denys88/rl_games/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 4 | 4 | 4 | [#394](https://github.com/Denys88/rl_games/pull/394), [#393](https://github.com/Denys88/rl_games/pull/393), [#392](https://github.com/Denys88/rl_games/pull/392), [#384](https://github.com/Denys88/rl_games/pull/384) |
| [geoopt/geoopt](https://github.com/geoopt/geoopt) | 1,103 | [#3](https://api.github.com/repos/geoopt/geoopt/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 10 | 10 | 10 | [#254](https://github.com/geoopt/geoopt/pull/254), [#253](https://github.com/geoopt/geoopt/pull/253), [#255](https://github.com/geoopt/geoopt/pull/255), [#256](https://github.com/geoopt/geoopt/pull/256), [#258](https://github.com/geoopt/geoopt/pull/258), [#259](https://github.com/geoopt/geoopt/pull/259), [#257](https://github.com/geoopt/geoopt/pull/257), [#267](https://github.com/geoopt/geoopt/pull/267), [#266](https://github.com/geoopt/geoopt/pull/266), [#262](https://github.com/geoopt/geoopt/pull/262) |
| [Toni-SM/skrl](https://github.com/Toni-SM/skrl) | 1,101 | [#3](https://api.github.com/repos/Toni-SM/skrl/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 3 | 3 | 3 | [#469](https://github.com/Toni-SM/skrl/pull/469), [#467](https://github.com/Toni-SM/skrl/pull/467), [#475](https://github.com/Toni-SM/skrl/pull/475) |
| [dfki-ric/pytransform3d](https://github.com/dfki-ric/pytransform3d) | 707 | [#15](https://api.github.com/repos/dfki-ric/pytransform3d/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 2 | 2 | 2 | [#389](https://github.com/dfki-ric/pytransform3d/pull/389), [#383](https://github.com/dfki-ric/pytransform3d/pull/383) |
| [naver/roma](https://github.com/naver/roma) | 647 | [#2](https://api.github.com/repos/naver/roma/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 4 | 4 | 4 | [#33](https://github.com/naver/roma/pull/33), [#32](https://github.com/naver/roma/pull/32), [#30](https://github.com/naver/roma/pull/30), [#29](https://github.com/naver/roma/pull/29) |
| [lucidrains/rectified-flow-pytorch](https://github.com/lucidrains/rectified-flow-pytorch) | 490 | [#3](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 1 | 1 | 1 | [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| [neka-nat/kinpy](https://github.com/neka-nat/kinpy) | 181 | [#2](https://api.github.com/repos/neka-nat/kinpy/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 3 | 3 | 3 | [#29](https://github.com/neka-nat/kinpy/pull/29), [#28](https://github.com/neka-nat/kinpy/pull/28), [#27](https://github.com/neka-nat/kinpy/pull/27) |
| [danijar/elements](https://github.com/danijar/elements) | 73 | [#3](https://api.github.com/repos/danijar/elements/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 2 | 2 | 2 | [#18](https://github.com/danijar/elements/pull/18), [#19](https://github.com/danijar/elements/pull/19) |
| [stephane-caron/qpmpc](https://github.com/stephane-caron/qpmpc) | 56 | [#2](https://api.github.com/repos/stephane-caron/qpmpc/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 5 | 5 | 3 | [#17](https://github.com/stephane-caron/qpmpc/pull/17), [#16](https://github.com/stephane-caron/qpmpc/pull/16), [#15](https://github.com/stephane-caron/qpmpc/pull/15) |
| [morluto/rea](https://github.com/morluto/rea) | 420,907 | [#75](https://api.github.com/repos/morluto/rea/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 3 | 3 | 3 | [#4524](https://github.com/morluto/rea/pull/4524), [#4414](https://github.com/morluto/rea/pull/4414), [#3919](https://github.com/morluto/rea/pull/3919) |
| [huggingface/lerobot](https://github.com/huggingface/lerobot) | 28,645 | [#227](https://api.github.com/repositories/748713144/contributors?per_page=100&anon=false&page=3)<br><sub>2026-11-02</sub> | 1 | 1 | 1 | [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26,909 | [#365](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-30.json)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| [recommenders-team/recommenders](https://github.com/recommenders-team/recommenders) | 21,974 | [#49](https://api.github.com/repos/recommenders-team/recommenders/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 6 | 6 | 2 | [#2388](https://github.com/recommenders-team/recommenders/pull/2388), [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| [colmap/colmap](https://github.com/colmap/colmap) | 13,131 | [#55](https://api.github.com/repos/colmap/colmap/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 2 | 2 | 2 | [#4931](https://github.com/colmap/colmap/pull/4931), [#4932](https://github.com/colmap/colmap/pull/4932) |
| [kornia/kornia](https://github.com/kornia/kornia) | 11,993 | [#134](https://api.github.com/repositories/145693916/contributors?per_page=100&anon=false&page=2)<br><sub>2026-11-02</sub> | 3 | 3 | 3 | [#6451](https://github.com/kornia/kornia/pull/6451), [#5517](https://github.com/kornia/kornia/pull/5517), [#5474](https://github.com/kornia/kornia/pull/5474) |
| [tile-ai/tilelang](https://github.com/tile-ai/tilelang) | 8,885 | [#210](https://github.com/Afloat16/Afloat16/blob/main/docs/contributions-2026-10-30.json)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| [rasbt/mlxtend](https://github.com/rasbt/mlxtend) | 5,190 | [#95](https://api.github.com/repos/rasbt/mlxtend/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 1 | 1 | 1 | [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| [geomstats/geomstats](https://github.com/geomstats/geomstats) | 1,528 | [#84](https://api.github.com/repos/geomstats/geomstats/contributors?per_page=100&anon=false&page=1)<br><sub>2026-11-02</sub> | 1 | 1 | 1 | [#2131](https://github.com/geomstats/geomstats/pull/2131) |

## Changes since 30 October 2026

| Project | Verified merged author PRs | Newly verified PRs |
|---|---:|---|
| DeepFace | 18 → 21 | [#1677](https://github.com/serengil/deepface/pull/1677), [#1676](https://github.com/serengil/deepface/pull/1676), [#1675](https://github.com/serengil/deepface/pull/1675) |
| Sentence Transformers | 3 → 5 | [#4114](https://github.com/huggingface/sentence-transformers/pull/4114), [#4301](https://github.com/huggingface/sentence-transformers/pull/4301) |
| PyTorch Metric Learning | 0 → 3 | [#756](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/756), [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759), [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) |
| RL Games | 1 → 4 | [#394](https://github.com/Denys88/rl_games/pull/394), [#393](https://github.com/Denys88/rl_games/pull/393), [#392](https://github.com/Denys88/rl_games/pull/392) |
| COLMAP | 0 → 2 | [#4931](https://github.com/colmap/colmap/pull/4931), [#4932](https://github.com/colmap/colmap/pull/4932) |
| Kornia | 2 → 3 | [#6451](https://github.com/kornia/kornia/pull/6451) |

The verified inventory increased from **82 to 96 PRs**, and from **24 to 26 merged-PR repositories**. COLMAP and PyTorch Metric Learning are new entries. Default-branch authored commits across accepted-contribution repositories increased from **92 to 109**. Earlier snapshots remain available unchanged.

## Other accepted work

These changes entered upstream through maintainer integration. Their original author PRs were closed without being directly merged, so they are **excluded from the 96 merged-PR total**.

| Project / original PR | Adoption evidence | Attribution |
|---|---|---|
| TD-MPC2 [#98](https://github.com/nicklashansen/tdmpc2/pull/98) | [Implementation cherry-pick](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a); the authored commit remains in the verified default-branch history. Target-Q history and evaluation mode are preserved during model conversion. | Commit author is Afloat16. This separately adopted contribution brings the accepted-project total to 27; current stars: 995, contributor-list position [#3](https://api.github.com/repos/nicklashansen/tdmpc2/contributors?per_page=100&anon=false&page=1) / 1 commit contribution, verified 2026-11-02. |
| Robotics Toolbox [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) | Adopted by merged [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883), 22 October 2026; [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/6b85d77c01d0ececacc57cf46a1613b3e8caf09e). Circular particle-heading moments. | Maintainer-authored squash retains `Co-authored-by: Afloat <132809511+Afloat16@users.noreply.github.com>`. |
| Robotics Toolbox [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) | Adopted by merged [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805), 16 October 2026 (Asia/Shanghai); [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/97c6c0fe15038069c366e5474b3a7fb1cd215fa2). Normalized-time quintic trajectories and the Hermite alternative. | Maintainer-authored squash retains the same Afloat co-author trailer. |

Robotics Toolbox is already one of the 26 merged-PR repositories and is counted once in the 27-project total. Maintainer-authored PRs #883 and #805 are not added as Afloat16-authored merged PRs. Unmerged work, including Denoising Diffusion #390 and REA #3940, is not counted as merged.
