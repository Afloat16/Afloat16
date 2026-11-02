# Upstream contribution record

Snapshot: **30 October 2026**. Account: [Afloat16](https://github.com/Afloat16). Display dates: **Asia/Shanghai**; machine-readable timestamps retain UTC.

**82 verified merged author PRs · 24 upstream repositories · 15 latest verified top-30 contributor-list positions**

TD-MPC2 adds one separately verified authored-code adoption, for **25 upstream projects with accepted contributions**. Across the merged PRs, **31 are in 8 repositories with more than 10,000 current stars**. The five profile highlights are an editorial selection from this set.

## Verification method

- The first `author:Afloat16 is:pr is:merged -user:Afloat16` search returned 80 results with `incomplete_results=false`. An independent all-status author-PR search returned **509 unique PRs across six pages, ordered by creation time**; **82** had `pull_request.merged_at`. Geoopt [#258](https://github.com/geoopt/geoopt/pull/258) and [#259](https://github.com/geoopt/geoopt/pull/259) were missing from the first search index. Every counted PR was then checked at its direct REST endpoint for `merged=true`, author `Afloat16` and a merge timestamp. Default-branch author-commit lists and commit-to-PR associations were cross-checked for additional omissions. The result is a verified inventory at retrieval time, not a guarantee against future indexing changes.
- Only public upstream repositories are counted. Account-owned PRs, unmerged PRs and maintainer-authored integration PRs are excluded. Counts include code, tests and documentation; they do not imply 82 separate bug fixes.
- Stars come from official repository metadata and belong to the upstream projects. They are not stars earned by my own repositories and do not measure an individual contribution's quality.
- Contributor positions are **one-based positions** in GitHub's `/repos/{owner}/{repo}/contributors?per_page=100&anon=false` responses, ordered by commit contributions, including bots and excluding anonymous contributors. Pagination offsets are included when later pages are retrieved. Equal counts retain GitHub's returned order. These are not PR-count rankings, maintainer roles, lines-of-code rankings or quality assessments.
- GitHub may cache contributor data. Its email-to-account attribution also has documented limits. `—` means no verified entry in the pages retrieved, not zero commits and not a fabricated numerical rank. The snapshot records retrieval status, pages, counts and source URLs.
- The full index’s **Current author commits** column uses the independently enumerated `/commits?author=Afloat16` default-branch history, refreshed on 30 October. This can differ from contributor statistics and is not the count used to determine the contributor position. The full index retains both metrics.
- Contributor refresh succeeded for all **25 of 25 repositories**, with **25 exact positions**. All positions were rechecked on 30 October; pagination was followed for LeRobot, Haystack, Kornia and TileLang. All **15 top-30 merged-PR projects** have current verification dates. TD-MPC2 is separately listed at #3. The machine-readable snapshot preserves per-repository retrieval times, page offsets and source URLs.
- The homepage preserves top-30 placements first and sorts each group by current stars. The five selected merges require **current stars >10,000**, verified authorship and merged state, and an inspected production diff with a substantive correctness or state-management change. They are sorted by `merged_at`, not PR creation or last update time, and are not claimed to be the newest five consecutive PRs.

Sources: [Contributor API documentation](https://docs.github.com/en/rest/repos/repos#list-repository-contributors) · [Author PR search](https://github.com/search?q=author%3AAfloat16%20is%3Apr%20-user%3AAfloat16&type=pullrequests) · [Current source snapshot](contributions-2026-10-30.json) · [Previous record](CONTRIBUTIONS-2026-10-23.md).

This refresh updates public metadata and retains the previously inspected selected-diff evidence. It does not rerun upstream test suites or enlarge the original PRs' validation claims.

## Five recent selected merges

| Merged | Upstream project · ★ | Engineering contribution | PR / merged commit |
|---|---|---|---|
| 2026-10-27 | **[REA](https://github.com/morluto/rea)**<br>409,561 ★ | Reject malformed UTF-8 before CDP discovery decodes JSON, preserving target titles and URLs. | [#4524](https://github.com/morluto/rea/pull/4524)<br>[`095a51c`](https://github.com/morluto/rea/commit/095a51cf38d2a0dc58368f6c9482062d594f856b) |
| 2026-10-23 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,613 ★ | Align face-region bounds and anti-spoofing ROIs with exclusive image-crop coordinates. | [#1658](https://github.com/serengil/deepface/pull/1658)<br>[`72aca24`](https://github.com/serengil/deepface/commit/72aca240a862559a8a7ef6334c2c1ceb8777a71e) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,587 ★ | Apply the established pairwise RoPE correction to VLA-JEPA's training-only world predictor. | [#4835](https://github.com/huggingface/lerobot/pull/4835)<br>[`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |
| 2026-10-22 | **[REA](https://github.com/morluto/rea)**<br>409,561 ★ | Complete short positional ZIP reads and report premature EOF as an integrity failure. | [#4414](https://github.com/morluto/rea/pull/4414)<br>[`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33) |
| 2026-10-16 | **[Haystack](https://github.com/deepset-ai/haystack)**<br>26,881 ★ | Isolate resumed execution counters so pipeline snapshots remain reusable after retries and breakpoints. | [#13076](https://github.com/deepset-ai/haystack/pull/13076)<br>[`34ab691`](https://github.com/deepset-ai/haystack/commit/34ab69146ed9f32688144d2b5a5ff0e81acbf372) |

### REA #4524

Protocol input integrity; complete-body validation, split multibyte input and recovery regressions.

Scope: Ordinary validation correction, not a new security capability or performance claim. Loopback tests do not establish real-browser qualification.

Evidence: [merged PR](https://github.com/morluto/rea/pull/4524) · [upstream commit](https://github.com/morluto/rea/commit/095a51cf38d2a0dc58368f6c9482062d594f856b); merge commit author: `Afloat16`.

### DeepFace #1658

Cross-path geometry contract, singleton/full-frame cases and anti-spoof ROI regression coverage.

Scope: No recognition-accuracy or anti-spoofing-quality improvement claim; broad optional model/backend suite was not run.

Evidence: [merged PR](https://github.com/serengil/deepface/pull/1658) · [upstream commit](https://github.com/serengil/deepface/commit/72aca240a862559a8a7ef6334c2c1ceb8777a71e); merge commit author: `Afloat16`.

### LeRobot #4835

Rotary position geometry; norm, inner-product and relative-position invariants; single-frequency broadcasting.

Scope: Correction originated in echosprint's V-JEPA 2 PR #15; not an original algorithm. Training-only predictor, checkpoint outputs/losses change; no pretrained-quality or real-robot performance claim.

Evidence: [merged PR](https://github.com/huggingface/lerobot/pull/4835) · [upstream commit](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693); merge commit author: `Afloat16`.

### REA #4414

Low-level I/O correctness; offset loop, truncation handling and bounded archive extraction regressions.

Scope: No general throughput or full-platform qualification claim; tests inject short reads on real descriptors.

Evidence: [merged PR](https://github.com/morluto/rea/pull/4414) · [upstream commit](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33); merge commit author: `Afloat16`.

### Haystack #13076

Checkpoint state ownership, replay determinism, downstream-failure retry and prior-snapshot isolation.

Scope: Focused pipeline checks only; no claim of full repository/integration suite validation.

Evidence: [merged PR](https://github.com/deepset-ai/haystack/pull/13076) · [upstream commit](https://github.com/deepset-ai/haystack/commit/34ab69146ed9f32688144d2b5a5ff0e81acbf372); merge commit author: `Afloat16`.

Recent candidates retained in the full record but not highlighted:

- [tile-ai/tilelang #3357](https://github.com/tile-ai/tilelang/pull/3357): 8,852 stars is below the strict >10,000 threshold.
- [recommenders-team/recommenders #2388](https://github.com/recommenders-team/recommenders/pull/2388): Valid contribution, but a basic nonpositive parameter check is less representative than checkpoint state ownership; retained in full record.
- [morluto/rea #3919](https://github.com/morluto/rea/pull/3919): Valid contribution, but straightforward client-list deduplication is less representative; retained in full record.

## Complete merged-PR index

| Upstream repository | Stars | Position · checked | Contributor-list count | Current author commits | Merged PRs | Source PRs |
|---|---:|---:|---:|---:|---:|---|
| [serengil/deepface](https://github.com/serengil/deepface) | 23,613 | [#9](https://api.github.com/repos/serengil/deepface/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 18 | 18 | 18 | [#1658](https://github.com/serengil/deepface/pull/1658), [#1655](https://github.com/serengil/deepface/pull/1655), [#1651](https://github.com/serengil/deepface/pull/1651), [#1653](https://github.com/serengil/deepface/pull/1653), [#1652](https://github.com/serengil/deepface/pull/1652), [#1649](https://github.com/serengil/deepface/pull/1649), [#1654](https://github.com/serengil/deepface/pull/1654), [#1648](https://github.com/serengil/deepface/pull/1648), [#1646](https://github.com/serengil/deepface/pull/1646), [#1647](https://github.com/serengil/deepface/pull/1647), [#1643](https://github.com/serengil/deepface/pull/1643), [#1644](https://github.com/serengil/deepface/pull/1644), [#1634](https://github.com/serengil/deepface/pull/1634), [#1638](https://github.com/serengil/deepface/pull/1638), [#1636](https://github.com/serengil/deepface/pull/1636), [#1633](https://github.com/serengil/deepface/pull/1633), [#1631](https://github.com/serengil/deepface/pull/1631), [#1630](https://github.com/serengil/deepface/pull/1630) |
| [lucidrains/denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) | 10,721 | [#9](https://api.github.com/repos/lucidrains/denoising-diffusion-pytorch/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| [Eigenwise/atomic-agents](https://github.com/Eigenwise/atomic-agents) | 6,313 | [#28](https://api.github.com/repos/Eigenwise/atomic-agents/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 2 | 2 | 1 | [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| [petercorke/robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) | 3,557 | [#6](https://api.github.com/repos/petercorke/robotics-toolbox-python/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 11 | 11 | 11 | [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801), [#800](https://github.com/petercorke/robotics-toolbox-python/pull/800), [#799](https://github.com/petercorke/robotics-toolbox-python/pull/799), [#798](https://github.com/petercorke/robotics-toolbox-python/pull/798), [#797](https://github.com/petercorke/robotics-toolbox-python/pull/797), [#796](https://github.com/petercorke/robotics-toolbox-python/pull/796), [#795](https://github.com/petercorke/robotics-toolbox-python/pull/795), [#794](https://github.com/petercorke/robotics-toolbox-python/pull/794), [#793](https://github.com/petercorke/robotics-toolbox-python/pull/793), [#792](https://github.com/petercorke/robotics-toolbox-python/pull/792), [#719](https://github.com/petercorke/robotics-toolbox-python/pull/719) |
| [leggedrobotics/rsl_rl](https://github.com/leggedrobotics/rsl_rl) | 3,106 | [#5](https://api.github.com/repos/leggedrobotics/rsl_rl/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 3 | 3 | 3 | [#244](https://github.com/leggedrobotics/rsl_rl/pull/244), [#240](https://github.com/leggedrobotics/rsl_rl/pull/240), [#239](https://github.com/leggedrobotics/rsl_rl/pull/239) |
| [pypose/pypose](https://github.com/pypose/pypose) | 1,620 | [#15](https://api.github.com/repos/pypose/pypose/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 6 | 6 | 4 | [#437](https://github.com/pypose/pypose/pull/437), [#415](https://github.com/pypose/pypose/pull/415), [#416](https://github.com/pypose/pypose/pull/416), [#417](https://github.com/pypose/pypose/pull/417) |
| [Denys88/rl_games](https://github.com/Denys88/rl_games) | 1,408 | [#24](https://api.github.com/repos/Denys88/rl_games/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#384](https://github.com/Denys88/rl_games/pull/384) |
| [geoopt/geoopt](https://github.com/geoopt/geoopt) | 1,102 | [#3](https://api.github.com/repos/geoopt/geoopt/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 10 | 10 | 10 | [#254](https://github.com/geoopt/geoopt/pull/254), [#253](https://github.com/geoopt/geoopt/pull/253), [#255](https://github.com/geoopt/geoopt/pull/255), [#256](https://github.com/geoopt/geoopt/pull/256), [#258](https://github.com/geoopt/geoopt/pull/258), [#259](https://github.com/geoopt/geoopt/pull/259), [#257](https://github.com/geoopt/geoopt/pull/257), [#267](https://github.com/geoopt/geoopt/pull/267), [#266](https://github.com/geoopt/geoopt/pull/266), [#262](https://github.com/geoopt/geoopt/pull/262) |
| [Toni-SM/skrl](https://github.com/Toni-SM/skrl) | 1,100 | [#3](https://api.github.com/repos/Toni-SM/skrl/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 3 | 3 | 3 | [#469](https://github.com/Toni-SM/skrl/pull/469), [#467](https://github.com/Toni-SM/skrl/pull/467), [#475](https://github.com/Toni-SM/skrl/pull/475) |
| [dfki-ric/pytransform3d](https://github.com/dfki-ric/pytransform3d) | 707 | [#15](https://api.github.com/repos/dfki-ric/pytransform3d/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 2 | 2 | 2 | [#389](https://github.com/dfki-ric/pytransform3d/pull/389), [#383](https://github.com/dfki-ric/pytransform3d/pull/383) |
| [naver/roma](https://github.com/naver/roma) | 647 | [#2](https://api.github.com/repos/naver/roma/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 4 | 4 | 4 | [#33](https://github.com/naver/roma/pull/33), [#32](https://github.com/naver/roma/pull/32), [#30](https://github.com/naver/roma/pull/30), [#29](https://github.com/naver/roma/pull/29) |
| [lucidrains/rectified-flow-pytorch](https://github.com/lucidrains/rectified-flow-pytorch) | 489 | [#3](https://api.github.com/repos/lucidrains/rectified-flow-pytorch/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| [neka-nat/kinpy](https://github.com/neka-nat/kinpy) | 181 | [#2](https://api.github.com/repos/neka-nat/kinpy/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 3 | 3 | 3 | [#29](https://github.com/neka-nat/kinpy/pull/29), [#28](https://github.com/neka-nat/kinpy/pull/28), [#27](https://github.com/neka-nat/kinpy/pull/27) |
| [danijar/elements](https://github.com/danijar/elements) | 73 | [#3](https://api.github.com/repos/danijar/elements/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 2 | 2 | 2 | [#18](https://github.com/danijar/elements/pull/18), [#19](https://github.com/danijar/elements/pull/19) |
| [stephane-caron/qpmpc](https://github.com/stephane-caron/qpmpc) | 55 | [#2](https://api.github.com/repos/stephane-caron/qpmpc/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 5 | 5 | 3 | [#17](https://github.com/stephane-caron/qpmpc/pull/17), [#16](https://github.com/stephane-caron/qpmpc/pull/16), [#15](https://github.com/stephane-caron/qpmpc/pull/15) |
| [morluto/rea](https://github.com/morluto/rea) | 409,561 | [#74](https://api.github.com/repos/morluto/rea/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 3 | 3 | 3 | [#4524](https://github.com/morluto/rea/pull/4524), [#4414](https://github.com/morluto/rea/pull/4414), [#3919](https://github.com/morluto/rea/pull/3919) |
| [huggingface/lerobot](https://github.com/huggingface/lerobot) | 28,587 | [#224](https://api.github.com/repositories/748713144/contributors?per_page=100&anon=false&page=3)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26,881 | [#365](https://api.github.com/repositories/221654678/contributors?per_page=100&anon=false&page=4)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| [recommenders-team/recommenders](https://github.com/recommenders-team/recommenders) | 21,971 | [#49](https://api.github.com/repos/recommenders-team/recommenders/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 6 | 6 | 2 | [#2388](https://github.com/recommenders-team/recommenders/pull/2388), [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | 19,236 | [#54](https://api.github.com/repos/huggingface/sentence-transformers/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 3 | 3 | 3 | [#4127](https://github.com/huggingface/sentence-transformers/pull/4127), [#4116](https://github.com/huggingface/sentence-transformers/pull/4116), [#4113](https://github.com/huggingface/sentence-transformers/pull/4113) |
| [kornia/kornia](https://github.com/kornia/kornia) | 11,459 | [#196](https://api.github.com/repositories/145693916/contributors?per_page=100&anon=false&page=2)<br><sub>2026-10-30</sub> | 2 | 2 | 2 | [#5517](https://github.com/kornia/kornia/pull/5517), [#5474](https://github.com/kornia/kornia/pull/5474) |
| [tile-ai/tilelang](https://github.com/tile-ai/tilelang) | 8,852 | [#210](https://api.github.com/repositories/867004514/contributors?per_page=100&anon=false&page=3)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| [rasbt/mlxtend](https://github.com/rasbt/mlxtend) | 5,190 | [#95](https://api.github.com/repos/rasbt/mlxtend/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| [geomstats/geomstats](https://github.com/geomstats/geomstats) | 1,528 | [#82](https://api.github.com/repos/geomstats/geomstats/contributors?per_page=100&anon=false&page=1)<br><sub>2026-10-30</sub> | 1 | 1 | 1 | [#2131](https://github.com/geomstats/geomstats/pull/2131) |

## Changes since 23 October 2026

| Project | Verified merged author PRs | Newly verified PRs |
|---|---:|---|
| REA | 2 → 3 | [#4524](https://github.com/morluto/rea/pull/4524) |
| DeepFace | 17 → 18 | [#1658](https://github.com/serengil/deepface/pull/1658) |
| TileLang | 0 → 1 | [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| RSL-RL | 2 → 3 | [#244](https://github.com/leggedrobotics/rsl_rl/pull/244) |
| RL Games | 0 → 1 | [#384](https://github.com/Denys88/rl_games/pull/384) |
| Geoopt | 4 → 10 | [#254](https://github.com/geoopt/geoopt/pull/254), [#253](https://github.com/geoopt/geoopt/pull/253), [#255](https://github.com/geoopt/geoopt/pull/255), [#256](https://github.com/geoopt/geoopt/pull/256), [#258](https://github.com/geoopt/geoopt/pull/258), [#259](https://github.com/geoopt/geoopt/pull/259) |
| qpmpc | 1 → 3 | [#17](https://github.com/stephane-caron/qpmpc/pull/17), [#16](https://github.com/stephane-caron/qpmpc/pull/16) |

The verified inventory increased from **69 to 82 PRs**, and from **22 to 24 merged-PR repositories**. Earlier snapshots remain available unchanged.

## Other accepted work

These changes entered upstream through maintainer integration. Their original author PRs were closed without being directly merged, so they are **excluded from the 82 merged-PR total**.

| Project / original PR | Adoption evidence | Attribution |
|---|---|---|
| TD-MPC2 [#98](https://github.com/nicklashansen/tdmpc2/pull/98) | [Implementation cherry-pick](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a); the authored commit remains in the verified default-branch history. Target-Q history and evaluation mode are preserved during model conversion. | Commit author is Afloat16. This separately adopted contribution brings the accepted-project total to 25; current stars: 993, contributor-list position #3 / 1 commit contribution. |
| Robotics Toolbox [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) | Adopted by merged [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883), 22 October 2026; [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/6b85d77c01d0ececacc57cf46a1613b3e8caf09e). Circular particle-heading moments. | Maintainer-authored squash retains `Co-authored-by: Afloat <132809511+Afloat16@users.noreply.github.com>`. |
| Robotics Toolbox [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) | Adopted by merged [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805), 16 October 2026 (Asia/Shanghai); [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/97c6c0fe15038069c366e5474b3a7fb1cd215fa2). Normalized-time quintic trajectories and the Hermite alternative. | Maintainer-authored squash retains the same Afloat co-author trailer. |

Robotics Toolbox is already one of the 24 merged-PR repositories and is counted once in the 25-project total. Maintainer-authored PRs #883 and #805 are not added as Afloat16-authored merged PRs. Open work, including Denoising Diffusion #390 and REA #3940, is not counted as merged.

