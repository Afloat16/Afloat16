# Upstream contribution record

Snapshot assembled: **7 November 2026 · 22:37 CST (UTC+8)**. Account: [Afloat16](https://github.com/Afloat16). Display dates use **Asia/Shanghai**; each machine-readable observation keeps its own timestamp.

**154 verified merged author PRs · 32 upstream repositories · 165 default-branch author commits across 33 accepted-contribution projects**

Since the previous snapshot, **12 additional author PRs** were verified, including the first merged contribution to **[openMVG](https://github.com/openMVG/openMVG)**. **88 merged author PRs** are in 11 projects with more than 10,000 stars. The separate adopted-work record now contains **14 integrations/cherry-picks**; details and original-source mappings are below.

The homepage lists **26 upstream projects with at least 1,000 stars**, covering **139 merged author PRs**. Of the displayed projects with directly merged author PRs, **13** have a verified top-30 position. The total counters cover all verified author merges, including those in smaller projects. This display rule does not filter my own projects or the full index.

## Verification method

- The complete merged-only search returned **152 distinct PRs** across 2 pages. Comparing those identities with the 142 individually verified baseline records identified 12 additions. The two historical indexing omissions, Geoopt [#258](https://github.com/geoopt/geoopt/pull/258) and [#259](https://github.com/geoopt/geoopt/pull/259), retain their direct merged evidence. All 142 old PR objects keep their original verification dates. The separate all-status cross-check read the latest 200 of 877 results, reaching earlier than the previous snapshot. It is not a count of accepted work.
- Each addition has a directly checked author, merge date, target branch, final SHA and merge-commit author. All 12 new final SHAs were present in the respective default-branch author inventories at the time they were read. The 33 complete author inventories total **165** commits. Merged PRs, author-filtered default-branch commits, graph counts and maintainer integrations are separate measures.
- The new openMVG PR was merged into **`develop`**, its default branch. Historical exceptions remain explicit: Recommenders [#2419](https://github.com/recommenders-team/recommenders/pull/2419) targeted `staging`, with commit author `miguelgfierro`; Trimesh [#2618](https://github.com/mikedh/trimesh/pull/2618) targeted `release/angles`, with commit author `mikedh`. The corresponding current default-branch author counts are 6 and 0.
- Current repository stars, forks and default branches come from official metadata. Each of the 26 eligible repositories was checked in the official Contributors graph: **21 explicit positions** and **5 complete top-100 absence checks**. The 7 smaller projects retain their individually dated graph observations. Their stars and author inventories were still refreshed.
- Positions use the All period and the default-branch Commit measure. GitHub's [graph definition](https://docs.github.com/en/repositories/viewing-activity-and-data-for-your-repository/viewing-a-projects-contributors) excludes merge and empty commits. Explicit card numbers preserve GitHub's displayed tie order; missing from all 100 displayed positions gives no exact rank. Large-repository pages can omit the measure selector or line counts. Graph caches and actual observation times are recorded independently of PR and author checks. Earlier REST metrics and their original dates remain in the snapshots.
- The final changes for the 12 new author merges were reviewed for scope and attribution. The six featured project rows retain their 13 selected PRs and original review dates. Regression source and fixtures were inspected where present; upstream tests were not rerun and no new CI result is claimed.

Sources: [Current snapshot](contributions-2026-11-07-2237.json) · [Previous snapshot](contributions-2026-11-06-1110.json) · [Previous full record](CONTRIBUTIONS-2026-11-06-1110.md) · [Author PR search](https://github.com/search?q=author%3AAfloat16%20is%3Apr%20-user%3AAfloat16&type=pullrequests).

## Selected merges by project

Six projects, one row each. Their complementary engineering examples, merge SHAs and review dates are retained. The new work is linked in the complete inventory and incremental review below.

| Latest selected merge | Upstream project · ★ | Representative engineering | PR / merged commit |
|---|---|---|---|
| 2026-11-06 | **[REA](https://github.com/morluto/rea)**<br>439,835 ★ | Complete partial ZIP reads and detect premature EOF; preserve UTF-8 code-point boundaries in byte-bounded diagnostic output. | [#4414](https://github.com/morluto/rea/pull/4414) · [`82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33)<br>[#8907](https://github.com/morluto/rea/pull/8907) · [`3eff806`](https://github.com/morluto/rea/commit/3eff8065e757c6e3bab96d164abfceafd340e6d1) |
| 2026-11-04 | **[Craft Anything](https://github.com/storytold/craft-anything)**<br>19,725 ★ | Persist rebuild progress across runs; correct bounded binary parsing and damaged-file recovery; recover minified esbuild dependencies through semantic bindings. | [#557](https://github.com/storytold/craft-anything/pull/557) · [`48759fb`](https://github.com/storytold/craft-anything/commit/48759fb5fccde45405c2db29d162ac55edbc6562)<br>[#766](https://github.com/storytold/craft-anything/pull/766) · [`eab6a0f`](https://github.com/storytold/craft-anything/commit/eab6a0f01bf9fc3a36798d322e4442e169394dfc)<br>[#438](https://github.com/storytold/craft-anything/pull/438) · [`89bcd06`](https://github.com/storytold/craft-anything/commit/89bcd061905de0f43e1dab161535fa4439ceb622) |
| 2026-11-02 | **[COLMAP](https://github.com/colmap/colmap)**<br>13,173 ★ | Make benchmark translation-angle errors invariant to reconstruction scale through numerically robust vector normalization. | [#4932](https://github.com/colmap/colmap/pull/4932) · [`27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd) |
| 2026-11-02 | **[Sentence Transformers](https://github.com/huggingface/sentence-transformers)**<br>19,266 ★ | Preserve ranking-loss gradients with weighted log-sigmoid, stabilize FP16 scalar quantization, and keep padded LSTM outputs aligned with token features. | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · [`abd266f`](https://github.com/huggingface/sentence-transformers/commit/abd266f29c7135e7ab9ccd3a41dfa74456b40c20)<br>[#4113](https://github.com/huggingface/sentence-transformers/pull/4113) · [`847abf6`](https://github.com/huggingface/sentence-transformers/commit/847abf6e6f2187159d699c0001af2bb1f65e1f18)<br>[#4301](https://github.com/huggingface/sentence-transformers/pull/4301) · [`26a0f49`](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c) |
| 2026-11-01 | **[DeepFace](https://github.com/serengil/deepface)**<br>23,655 ★ | Align Milvus scores with DeepFace distance units, fetch complete galleries beyond the single-query limit, and preserve empty, singleton and multi-image batch structure. | [#1634](https://github.com/serengil/deepface/pull/1634) · [`bf5ed73`](https://github.com/serengil/deepface/commit/bf5ed7339a0d430cbd214e4923ee6a694f808dec)<br>[#1649](https://github.com/serengil/deepface/pull/1649) · [`5696e33`](https://github.com/serengil/deepface/commit/5696e3313ffdf6d51cd67f38a9da88ccd58ebb5e)<br>[#1675](https://github.com/serengil/deepface/pull/1675) · [`8e565c0`](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac) |
| 2026-10-22 | **[LeRobot](https://github.com/huggingface/lerobot)**<br>28,731 ★ | Apply the existing V-JEPA 2 pairwise RoPE correction to VLA-JEPA's training-only world predictor. | [#4835](https://github.com/huggingface/lerobot/pull/4835) · [`f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693) |

### Craft Anything

**[#557](https://github.com/storytold/craft-anything/pull/557) — Persist rebuild progress across runs, stopping unchanged turns while preserving cancellation, recovery and new requests.** Merged 2026-11-03.

Introduces a versioned, atomically persisted progress record and deterministic content fingerprints with bounded, cancellable traversal. Integrates before/after-turn state, check-only recovery, deferred note resets and error preservation so retries and application restarts cannot silently reset the unchanged-turn allowance. Distinguishes identical rewrites from actual file-content changes, records symlinks without following them, and caches content digests within a run.

Scope: This is a file-progress guard, not a measure of semantic application improvement or model quality. Scan I/O or traversal-limit failures disable the guard for that run; record corruption or newer versions remain errors. Cache reuse relies on available file metadata. No runtime speedup, sandbox guarantee or upstream-test pass is claimed; this review did not rerun tests.

Evidence: [merged PR](https://github.com/storytold/craft-anything/pull/557) · [upstream commit `48759fb`](https://github.com/storytold/craft-anything/commit/48759fb5fccde45405c2db29d162ac55edbc6562); merge commit author: `Afloat16`.

**[#766](https://github.com/storytold/craft-anything/pull/766) — Correct partial Java decoding, signed DEX values, bounded AAPT string recovery and damaged ext indirect-block handling.** Merged 2026-11-04.

Five production files address four parser correctness issues found during review of maintainer integration #722. Java reference extraction preserves decoded references while surfacing incomplete bytecode decoding as partial coverage. DEX signed LEB128 decoding enforces the five-byte signed-32-bit representation and valid fifth-byte sign extension. Legacy AAPT UTF-8 recovery checks candidate lengths inside the string-data region and shares a 65,536-probe budget across the whole pool while retaining the existing output cap. Classic ext single/double-indirect traversal treats unreadable nonzero metadata as unrecovered data, keeps true sparse ranges, stops at file EOF and reports unsupported needed triple-indirect traversal.

Scope: A follow-up correctness repair to existing parsers, not an original parser architecture. The ext extent-tree path is unchanged and needed triple-indirect traversal remains unsupported. Legacy UTF-8 recovery still uses lossy decoding and bounded output; this is not strict UTF-8 validation or a promise to recover arbitrary corrupt inputs. No throughput, exploit-prevention or model-quality result is claimed. Merged production changes and regression fixtures were inspected, but tests were not rerun and no final-merge CI pass was independently verified.

Evidence: [merged PR](https://github.com/storytold/craft-anything/pull/766) · [upstream commit `eab6a0f`](https://github.com/storytold/craft-anything/commit/eab6a0f01bf9fc3a36798d322e4442e169394dfc); merge commit author: `Afloat16`.

**[#438](https://github.com/storytold/craft-anything/pull/438) — Recover minified esbuild dependencies through semantic bindings, distinguishing shadowed and same-named wrappers.** Merged 2026-11-03.

Replaces wrapper-name matching with semantic symbol keys, threads scoping information into bundle analysis, deduplicates call bindings and resolves wrapper dependencies after visiting the file. This retains dependencies after minification while avoiding false links through local parameters or similarly named wrappers in another scope.

Scope: Targets recognized esbuild wrapper patterns, not general JavaScript alias or whole-program dependency analysis; the fallback without semantic scoping remains name-based. The later adopted #641 via maintainer integration #656 improves the cap behavior under many unrelated calls and must not be credited to #438 alone. Regression tests were inspected, not rerun.

Evidence: [merged PR](https://github.com/storytold/craft-anything/pull/438) · [upstream commit `89bcd06`](https://github.com/storytold/craft-anything/commit/89bcd061905de0f43e1dab161535fa4439ceb622); merge commit author: `Afloat16`.

### COLMAP

**[#4932](https://github.com/colmap/colmap/pull/4932) — Make benchmark translation-angle errors invariant to reconstruction scale.** Merged 2026-11-02.

Normalizes finite nonzero vectors by their largest absolute component before the L2 norm, avoiding the previous small-norm floor and overflow. Merged regressions exercise independent scales from 1e-200 to 1e200, angle invariants, input preservation, zero vectors and reconstruction-level similarity transforms.

Scope: This changes benchmark pose-error evaluation, not the reconstruction solver or reconstruction quality. The final merged test files are geometry_test.py and utils_test.py; the PR body's geometry_scale_test.py command does not describe the final filenames. Tests were not rerun during this review.

Evidence: [merged PR](https://github.com/colmap/colmap/pull/4932) · [upstream commit `27ffad4`](https://github.com/colmap/colmap/commit/27ffad4388ce5647df3ea9e547bf8e1ea155fbcd); merge commit author: `Afloat16`.

### Sentence Transformers

**[#4116](https://github.com/huggingface/sentence-transformers/pull/4116) — Preserve LambdaLoss and RankNet gradients for strongly misordered pairs using weighted log-sigmoid.** Merged 2026-10-12.

Moves the weighted pairwise objective into log-probability space, avoiding probability clamps that cap large losses and suppress gradients. The merged regression compares both losses and gradients against float64 binary cross-entropy references, across score gaps, sigma values, logarithm bases and padded batches.

Scope: This is objective-function correctness, not a measured ranking-accuracy or training-throughput improvement. No pretrained-model, GPU or distributed training result was verified in this review; tests were inspected but not rerun.

Evidence: [merged PR](https://github.com/huggingface/sentence-transformers/pull/4116) · [upstream commit `abd266f`](https://github.com/huggingface/sentence-transformers/commit/abd266f29c7135e7ab9ccd3a41dfa74456b40c20); merge commit author: `Afloat16`.

**[#4113](https://github.com/huggingface/sentence-transformers/pull/4113) — Use float32 calibration arithmetic to prevent FP16 scalar-quantization range underflow and overflow.** Merged 2026-10-08.

The final production change casts scalar calibration ranges to float32 before computing bucket steps. It prevents narrow nonconstant FP16 ranges from collapsing to identical int8/uint8 codes and avoids overflow for large opposite-signed endpoints. Merged tests cover inferred, supplied and calibration-embedding ranges, shared multivector ranges and torch.float16 inputs.

Scope: The merged code uses ranges.astype(np.float32, copy=False), not the np.result_type implementation described in the older PR body. Do not claim float64 calibration-range preservation. This is a scoped scalar-quantization fix; no new quantization algorithm, accuracy gain, accelerator result or throughput gain is claimed. Tests were not rerun.

Evidence: [merged PR](https://github.com/huggingface/sentence-transformers/pull/4113) · [upstream commit `847abf6`](https://github.com/huggingface/sentence-transformers/commit/847abf6e6f2187159d699c0001af2bb1f65e1f18); merge commit author: `Afloat16`.

**[#4301](https://github.com/huggingface/sentence-transformers/pull/4301) — Preserve padded LSTM sequence lengths so token outputs stay aligned with companion features.** Merged 2026-11-02.

Passes the original padded width as total_length when unpacking packed recurrent sequences, preventing batch-dependent shortening of token_embeddings.

Scope: The final merged diff contains only the production LSTM module; preparation-time regression results should not be described as tests added in the merged patch. No GPU DataParallel or model-quality improvement is claimed. Tests were not rerun in this review.

Evidence: [merged PR](https://github.com/huggingface/sentence-transformers/pull/4301) · [upstream commit `26a0f49`](https://github.com/huggingface/sentence-transformers/commit/26a0f49fad7927dcc565a6ee9880730c2c65c64c); merge commit author: `Afloat16`.

### DeepFace

**[#1634](https://github.com/serengil/deepface/pull/1634) — Convert Milvus cosine-similarity and squared-L2 scores into DeepFace distance units.** Merged 2026-10-01.

Repairs the vector-database adapter boundary: cosine scores become 1 minus clamped similarity; squared L2 becomes the square root of a nonnegative score. This lets existing downstream ranking, threshold and confidence logic consume distances in the units it expects. Merged unit and Milvus Lite integration regressions compare ANN and exact paths using fixed vectors.

Scope: Does not change learned embeddings, face-recognition accuracy, approximate-index recall or other database adapters. Integration test code uses fixed synthetic vectors rather than learned model outputs. Tests and historical CI were not rerun or newly validated during this review.

Evidence: [merged PR](https://github.com/serengil/deepface/pull/1634) · [upstream commit `bf5ed73`](https://github.com/serengil/deepface/commit/bf5ed7339a0d430cbd214e4923ee6a694f808dec); merge commit author: `Afloat16`.

**[#1649](https://github.com/serengil/deepface/pull/1649) — Read complete Milvus galleries with a query iterator and close it on success or failure.** Merged 2026-10-03.

Replaces the single query capped at 16,384 records with SDK iteration using the existing batch_size. This prevents silently omitting remaining gallery records from full-gallery reads and releases the iterator in a finally block. The merged real Milvus Lite regression inserts 16,385 records and checks every ID and the last payload.

Scope: The method still accumulates all returned records in a Python list; it is not a bounded-memory streaming API or a measured throughput improvement. Scope is Milvus full-gallery reads. Test code was inspected but not rerun.

Evidence: [merged PR](https://github.com/serengil/deepface/pull/1649) · [upstream commit `5696e33`](https://github.com/serengil/deepface/commit/5696e3313ffdf6d51cd67f38a9da88ccd58ebb5e); merge commit author: `Afloat16`.

**[#1675](https://github.com/serengil/deepface/pull/1675) — Preserve consistent result structure for empty, singleton and multi-image representation batches.** Merged 2026-11-01.

Determines batch shape from input form rather than length; keeps scalar-image output flat, retains the outer batch dimension for list/4D inputs and returns empty batches before loading a model.

Scope: Corrects the representation API's batch structure; the singleton-batch output shape intentionally changes. The merged regression uses SFace inference; no recognition-accuracy improvement is claimed. Tests were not rerun in this review.

Evidence: [merged PR](https://github.com/serengil/deepface/pull/1675) · [upstream commit `8e565c0`](https://github.com/serengil/deepface/commit/8e565c050b821b8585e3c9527e419b0be5495fac); merge commit author: `Afloat16`.

### REA

**[#4414](https://github.com/morluto/rea/pull/4414) — Complete short positional ZIP reads and report premature EOF as an integrity failure.** Merged 2026-10-22.

Accumulates FileHandle.read results using consistent buffer and file offsets until the admitted read is complete; a zero-byte read before completion raises the existing integrity failure. Final merged tests inject short reads into real descriptors while exercising production ZIP enumeration and extraction.

Scope: Archive-reader correctness within existing allocation/read budgets; no throughput or expanded security-boundary claim. Cancellation coverage proves no entry is published after cancellation, not necessarily that every underlying read stops immediately. This review did not rerun tests or establish full-suite, cross-platform or forced-short-read public CLI/MCP coverage.

Evidence: [merged PR](https://github.com/morluto/rea/pull/4414) · [upstream commit `82e4e03`](https://github.com/morluto/rea/commit/82e4e032dfe97b7912cebc2812e1e9fc41c1eb33); merge commit author: `Afloat16`.

**[#8907](https://github.com/morluto/rea/pull/8907) — Preserve UTF-8 code-point boundaries in byte-bounded diagnostic excerpts without hiding known malformed head bytes.** Merged 2026-11-06.

Adds separate retained-head and retained-tail boundary handling to BoundedOutputExcerpt. The head drops only a suffix that could still form a valid UTF-8 code point, rejecting invalid leaders and already-invalid second-byte ranges from that trimming rule. The tail removes a possible leading continuation-byte fragment, while runs longer than three bytes remain diagnostic evidence. Untruncated output joins the retained buffers before decoding. Regression code iterates every two-chunk split, bytewise appends, malformed prefixes and subprocess stdout/stderr.

Scope: A diagnostic excerpt boundary fix under the existing raw-byte budget. It is not a full UTF-8 validator, a grapheme-cluster segmenter or a promise to preserve every malformed sequence at an ambiguous tail boundary. It does not alter process-execution capabilities, exit codes, retention limits or the tail policy. Regression code was inspected; tests and cited CI were not independently rerun or verified.

Evidence: [#8907](https://github.com/morluto/rea/pull/8907) · [upstream commit `3eff806`](https://github.com/morluto/rea/commit/3eff8065e757c6e3bab96d164abfceafd340e6d1); merge commit author: `Afloat16`. Final production diff reviewed at 2026-11-06T02:37:23.896Z.

### LeRobot

**[#4835](https://github.com/huggingface/lerobot/pull/4835) — Apply V-JEPA 2's existing pairwise RoPE correction to VLA-JEPA's training-only world predictor.** Merged 2026-10-22.

Replaces frequency-block repetition with repeat_interleave(2, dim=-1), matching the adjacent-coordinate rotation layout and retaining the position axis for a single frequency. The correction targets the RoPE geometry used by the world predictor; it is an application of prior upstream work.

Scope: Not an original RoPE algorithm. The final merged diff contains the production helper and documentation only, with no added regression test file. Parameter names/shapes remain load-compatible, but existing world-predictor outputs and training losses change; pretrained quality requires separate evaluation. The world predictor is training-only, so no closed-loop robot performance, inference-quality or full-suite/GPU validation improvement is claimed. Tests were not rerun during this review.

Evidence: [merged PR](https://github.com/huggingface/lerobot/pull/4835) · [upstream commit `f9e9d73`](https://github.com/huggingface/lerobot/commit/f9e9d739ea7055b282ea1b165e8785412a674693); merge commit author: `Afloat16`.

Attribution: LeRobot's merged documentation credits upstream V-JEPA 2 PR #15 to echosprint. At the 3 November review, the PR #15 API identified its author login as physiclaw (user id 73099895); no account-rename history is inferred here. PR #15 proposes repeat_interleave but is closed without merge; merged PR #75 documents the fix while retaining the released-model implementation for compatibility. LeRobot applies the existing correction, not an original algorithm. Sources: [V-JEPA 2 #15](https://github.com/facebookresearch/vjepa2/pull/15) · [compatibility notes in #75](https://github.com/facebookresearch/vjepa2/pull/75).

Other candidates remain in the complete inventory. COLMAP #4931 resolves benchmark paths; REA #3919 deduplicates setup clients. The selected rows emphasize complementary numerical, byte-handling, retrieval and state-management work.

## Previously selected work

The following earlier review remains available; #441 is no longer in the homepage selection and remains in the merged-PR inventory.

**[#441](https://github.com/storytold/craft-anything/pull/441) — Compare imported and defined WebAssembly tag signatures while preserving index spaces and truncation diagnostics.** Merged 2026-11-03.

Adds tag metadata to the binary report, resolves exported tags to function signatures, and tracks the imported-tag index independently of capped import/tag lists. Prevents defined tags from being assigned a skipped imported index and preserves unresolved, partial and invalid diagnostics. End-to-end tool tests distinguish changed tag parameter types and re-exported imported tags.

Scope: Covers static tag metadata and signature comparison; it does not execute WebAssembly, prove full runtime/interface compatibility, or resolve omitted metadata beyond configured limits. Synthetic valid and malformed module regressions were inspected but not rerun.

Evidence: [merged PR](https://github.com/storytold/craft-anything/pull/441) · [upstream commit `fa4aae2`](https://github.com/storytold/craft-anything/commit/fa4aae2e79198ece843a876512172bfb10d902e3); merge commit author: `Afloat16`.

### REA — previously selected #4524

The homepage now features #8907 alongside #4414. The following earlier review remains unchanged, with its original evidence dates in the snapshot.

**[#4524](https://github.com/morluto/rea/pull/4524) — Reject malformed UTF-8 before HTTP CDP discovery JSON decoding, while preserving valid Unicode.** Merged 2026-10-27.

Validates the complete size-bounded response buffer with node:buffer.isUtf8 before replacement-prone decoding. The merged regression suite distinguishes malformed title/URL bytes from a legitimate U+FFFD character, verifies multibyte text split across HTTP chunks and checks recovery on the next discovery.

Scope: A scoped HTTP discovery validation fix; it does not change WebSocket framing, endpoint authorization, provider capabilities or public command/schema shape. Malformed UTF-8 now produces the existing invalid_endpoint_response error. Tests use simulated loopback HTTP producers, not a qualified real-browser or packaged-install run. No performance improvement is claimed and tests were not rerun in this review.

Evidence: [merged PR](https://github.com/morluto/rea/pull/4524) · [upstream commit `095a51c`](https://github.com/morluto/rea/commit/095a51cf38d2a0dc58368f6c9482062d594f856b); merge commit author: `Afloat16`.

## Complete merged-PR index

The following index includes smaller repositories omitted from the homepage. A retained graph date is shown explicitly; stars, merged counts and author inventories are current observations.

| Repository | Upstream ★ | Graph position · checked | Graph commits | Default-branch author commits | Merged PRs | Verified merged PRs |
|---|---:|---:|---:|---:|---:|---|
| [morluto/rea](https://github.com/morluto/rea) | 439,835 | [#65](https://github.com/morluto/rea/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 6 | [#8907](https://github.com/morluto/rea/pull/8907), [#8909](https://github.com/morluto/rea/pull/8909), [#8908](https://github.com/morluto/rea/pull/8908), [#4524](https://github.com/morluto/rea/pull/4524), [#4414](https://github.com/morluto/rea/pull/4414), [#3919](https://github.com/morluto/rea/pull/3919) |
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 114,275 | [#52](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 5 | 4 | 4 | [#5458](https://github.com/thedotmack/claude-mem/pull/5458), [#5367](https://github.com/thedotmack/claude-mem/pull/5367), [#5340](https://github.com/thedotmack/claude-mem/pull/5340), [#5341](https://github.com/thedotmack/claude-mem/pull/5341) |
| [huggingface/lerobot](https://github.com/huggingface/lerobot) | 28,731 | [—](https://github.com/huggingface/lerobot/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | — | 1 | 1 | [#4835](https://github.com/huggingface/lerobot/pull/4835) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26,942 | [—](https://github.com/deepset-ai/haystack/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | — | 1 | 1 | [#13076](https://github.com/deepset-ai/haystack/pull/13076) |
| [serengil/deepface](https://github.com/serengil/deepface) | 23,655 | [#4](https://github.com/serengil/deepface/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 24 | 24 | 24 | [#1678](https://github.com/serengil/deepface/pull/1678), [#1680](https://github.com/serengil/deepface/pull/1680), [#1679](https://github.com/serengil/deepface/pull/1679), [#1677](https://github.com/serengil/deepface/pull/1677), [#1676](https://github.com/serengil/deepface/pull/1676), [#1675](https://github.com/serengil/deepface/pull/1675), [#1658](https://github.com/serengil/deepface/pull/1658), [#1655](https://github.com/serengil/deepface/pull/1655), [#1651](https://github.com/serengil/deepface/pull/1651), [#1653](https://github.com/serengil/deepface/pull/1653), [#1652](https://github.com/serengil/deepface/pull/1652), [#1649](https://github.com/serengil/deepface/pull/1649), [#1654](https://github.com/serengil/deepface/pull/1654), [#1648](https://github.com/serengil/deepface/pull/1648), [#1646](https://github.com/serengil/deepface/pull/1646), [#1647](https://github.com/serengil/deepface/pull/1647), [#1643](https://github.com/serengil/deepface/pull/1643), [#1644](https://github.com/serengil/deepface/pull/1644), [#1634](https://github.com/serengil/deepface/pull/1634), [#1638](https://github.com/serengil/deepface/pull/1638), [#1636](https://github.com/serengil/deepface/pull/1636), [#1633](https://github.com/serengil/deepface/pull/1633), [#1631](https://github.com/serengil/deepface/pull/1631), [#1630](https://github.com/serengil/deepface/pull/1630) |
| [recommenders-team/recommenders](https://github.com/recommenders-team/recommenders) | 21,981 | [#46](https://github.com/recommenders-team/recommenders/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 3 | [#2419](https://github.com/recommenders-team/recommenders/pull/2419), [#2388](https://github.com/recommenders-team/recommenders/pull/2388), [#2389](https://github.com/recommenders-team/recommenders/pull/2389) |
| [storytold/craft-anything](https://github.com/storytold/craft-anything) | 19,725 | [#2](https://github.com/storytold/craft-anything/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 44 | 34 | 34 | [#1092](https://github.com/storytold/craft-anything/pull/1092), [#1090](https://github.com/storytold/craft-anything/pull/1090), [#1093](https://github.com/storytold/craft-anything/pull/1093), [#1091](https://github.com/storytold/craft-anything/pull/1091), [#1089](https://github.com/storytold/craft-anything/pull/1089), [#1088](https://github.com/storytold/craft-anything/pull/1088), [#767](https://github.com/storytold/craft-anything/pull/767), [#717](https://github.com/storytold/craft-anything/pull/717), [#766](https://github.com/storytold/craft-anything/pull/766), [#773](https://github.com/storytold/craft-anything/pull/773), [#673](https://github.com/storytold/craft-anything/pull/673), [#675](https://github.com/storytold/craft-anything/pull/675), [#677](https://github.com/storytold/craft-anything/pull/677), [#674](https://github.com/storytold/craft-anything/pull/674), [#557](https://github.com/storytold/craft-anything/pull/557), [#552](https://github.com/storytold/craft-anything/pull/552), [#546](https://github.com/storytold/craft-anything/pull/546), [#554](https://github.com/storytold/craft-anything/pull/554), [#550](https://github.com/storytold/craft-anything/pull/550), [#433](https://github.com/storytold/craft-anything/pull/433), [#559](https://github.com/storytold/craft-anything/pull/559), [#544](https://github.com/storytold/craft-anything/pull/544), [#543](https://github.com/storytold/craft-anything/pull/543), [#541](https://github.com/storytold/craft-anything/pull/541), [#542](https://github.com/storytold/craft-anything/pull/542), [#439](https://github.com/storytold/craft-anything/pull/439), [#442](https://github.com/storytold/craft-anything/pull/442), [#441](https://github.com/storytold/craft-anything/pull/441), [#440](https://github.com/storytold/craft-anything/pull/440), [#438](https://github.com/storytold/craft-anything/pull/438), [#437](https://github.com/storytold/craft-anything/pull/437), [#436](https://github.com/storytold/craft-anything/pull/436), [#435](https://github.com/storytold/craft-anything/pull/435), [#434](https://github.com/storytold/craft-anything/pull/434) |
| [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) | 19,266 | [#28](https://github.com/huggingface/sentence-transformers/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 6 | [#4323](https://github.com/huggingface/sentence-transformers/pull/4323), [#4114](https://github.com/huggingface/sentence-transformers/pull/4114), [#4301](https://github.com/huggingface/sentence-transformers/pull/4301), [#4127](https://github.com/huggingface/sentence-transformers/pull/4127), [#4116](https://github.com/huggingface/sentence-transformers/pull/4116), [#4113](https://github.com/huggingface/sentence-transformers/pull/4113) |
| [colmap/colmap](https://github.com/colmap/colmap) | 13,173 | [#49](https://github.com/colmap/colmap/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 2 | 2 | 2 | [#4931](https://github.com/colmap/colmap/pull/4931), [#4932](https://github.com/colmap/colmap/pull/4932) |
| [kornia/kornia](https://github.com/kornia/kornia) | 12,352 | [#85](https://github.com/kornia/kornia/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 6 | [#6580](https://github.com/kornia/kornia/pull/6580), [#6582](https://github.com/kornia/kornia/pull/6582), [#6449](https://github.com/kornia/kornia/pull/6449), [#6451](https://github.com/kornia/kornia/pull/6451), [#5517](https://github.com/kornia/kornia/pull/5517), [#5474](https://github.com/kornia/kornia/pull/5474) |
| [lucidrains/denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) | 10,723 | [#9](https://github.com/lucidrains/denoising-diffusion-pytorch/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 1 | 1 | 1 | [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) |
| [tile-ai/tilelang](https://github.com/tile-ai/tilelang) | 8,924 | [—](https://github.com/tile-ai/tilelang/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | — | 1 | 1 | [#3357](https://github.com/tile-ai/tilelang/pull/3357) |
| [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail) | 7,893 | [#17](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 3 | 3 | 3 | [#1184](https://github.com/JetBrains/thinkrail/pull/1184), [#1186](https://github.com/JetBrains/thinkrail/pull/1186), [#1185](https://github.com/JetBrains/thinkrail/pull/1185) |
| [openMVG/openMVG](https://github.com/openMVG/openMVG) | 6,590 | [#96](https://github.com/openMVG/openMVG/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 1 | 1 | 1 | [#2445](https://github.com/openMVG/openMVG/pull/2445) |
| [KevinMusgrave/pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning) | 6,342 | [#9](https://github.com/KevinMusgrave/pytorch-metric-learning/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 3 | [#756](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/756), [#759](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/759), [#758](https://github.com/KevinMusgrave/pytorch-metric-learning/pull/758) |
| [Eigenwise/atomic-agents](https://github.com/Eigenwise/atomic-agents) | 6,320 | [#23](https://github.com/Eigenwise/atomic-agents/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 2 | 2 | 1 | [#292](https://github.com/Eigenwise/atomic-agents/pull/292) |
| [rasbt/mlxtend](https://github.com/rasbt/mlxtend) | 5,191 | [#60](https://github.com/rasbt/mlxtend/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 1 | 1 | 1 | [#1207](https://github.com/rasbt/mlxtend/pull/1207) |
| [mikedh/trimesh](https://github.com/mikedh/trimesh) | 3,719 | [—](https://github.com/mikedh/trimesh/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | — | 0 | 1 | [#2618](https://github.com/mikedh/trimesh/pull/2618) |
| [petercorke/robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) | 3,567 | [#7](https://github.com/petercorke/robotics-toolbox-python/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 14 | 11 | 11 | [#801](https://github.com/petercorke/robotics-toolbox-python/pull/801), [#800](https://github.com/petercorke/robotics-toolbox-python/pull/800), [#799](https://github.com/petercorke/robotics-toolbox-python/pull/799), [#798](https://github.com/petercorke/robotics-toolbox-python/pull/798), [#797](https://github.com/petercorke/robotics-toolbox-python/pull/797), [#796](https://github.com/petercorke/robotics-toolbox-python/pull/796), [#795](https://github.com/petercorke/robotics-toolbox-python/pull/795), [#794](https://github.com/petercorke/robotics-toolbox-python/pull/794), [#793](https://github.com/petercorke/robotics-toolbox-python/pull/793), [#792](https://github.com/petercorke/robotics-toolbox-python/pull/792), [#719](https://github.com/petercorke/robotics-toolbox-python/pull/719) |
| [leggedrobotics/rsl_rl](https://github.com/leggedrobotics/rsl_rl) | 3,123 | [#4](https://github.com/leggedrobotics/rsl_rl/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 4 | 3 | 3 | [#244](https://github.com/leggedrobotics/rsl_rl/pull/244), [#240](https://github.com/leggedrobotics/rsl_rl/pull/240), [#239](https://github.com/leggedrobotics/rsl_rl/pull/239) |
| [elalish/manifold](https://github.com/elalish/manifold) | 2,395 | [—](https://github.com/elalish/manifold/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | — | 1 | 1 | [#1905](https://github.com/elalish/manifold/pull/1905) |
| [pypose/pypose](https://github.com/pypose/pypose) | 1,621 | [#16](https://github.com/pypose/pypose/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 6 | 6 | 4 | [#437](https://github.com/pypose/pypose/pull/437), [#415](https://github.com/pypose/pypose/pull/415), [#416](https://github.com/pypose/pypose/pull/416), [#417](https://github.com/pypose/pypose/pull/417) |
| [geomstats/geomstats](https://github.com/geomstats/geomstats) | 1,529 | [#83](https://github.com/geomstats/geomstats/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 1 | 1 | 1 | [#2131](https://github.com/geomstats/geomstats/pull/2131) |
| [Denys88/rl_games](https://github.com/Denys88/rl_games) | 1,411 | [#7](https://github.com/Denys88/rl_games/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 4 | 4 | 4 | [#394](https://github.com/Denys88/rl_games/pull/394), [#393](https://github.com/Denys88/rl_games/pull/393), [#392](https://github.com/Denys88/rl_games/pull/392), [#384](https://github.com/Denys88/rl_games/pull/384) |
| [Toni-SM/skrl](https://github.com/Toni-SM/skrl) | 1,105 | [#4](https://github.com/Toni-SM/skrl/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 3 | 3 | 3 | [#469](https://github.com/Toni-SM/skrl/pull/469), [#467](https://github.com/Toni-SM/skrl/pull/467), [#475](https://github.com/Toni-SM/skrl/pull/475) |
| [geoopt/geoopt](https://github.com/geoopt/geoopt) | 1,104 | [#2](https://github.com/geoopt/geoopt/graphs/contributors?all=1)<br><sub>2026-11-07</sub> | 13 | 13 | 13 | [#280](https://github.com/geoopt/geoopt/pull/280), [#279](https://github.com/geoopt/geoopt/pull/279), [#278](https://github.com/geoopt/geoopt/pull/278), [#254](https://github.com/geoopt/geoopt/pull/254), [#253](https://github.com/geoopt/geoopt/pull/253), [#255](https://github.com/geoopt/geoopt/pull/255), [#256](https://github.com/geoopt/geoopt/pull/256), [#258](https://github.com/geoopt/geoopt/pull/258), [#259](https://github.com/geoopt/geoopt/pull/259), [#257](https://github.com/geoopt/geoopt/pull/257), [#267](https://github.com/geoopt/geoopt/pull/267), [#266](https://github.com/geoopt/geoopt/pull/266), [#262](https://github.com/geoopt/geoopt/pull/262) |
| [dfki-ric/pytransform3d](https://github.com/dfki-ric/pytransform3d) | 707 | [#17](https://github.com/dfki-ric/pytransform3d/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 2 | 2 | 2 | [#389](https://github.com/dfki-ric/pytransform3d/pull/389), [#383](https://github.com/dfki-ric/pytransform3d/pull/383) |
| [naver/roma](https://github.com/naver/roma) | 647 | [#2](https://github.com/naver/roma/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 4 | 4 | 4 | [#33](https://github.com/naver/roma/pull/33), [#32](https://github.com/naver/roma/pull/32), [#30](https://github.com/naver/roma/pull/30), [#29](https://github.com/naver/roma/pull/29) |
| [lucidrains/rectified-flow-pytorch](https://github.com/lucidrains/rectified-flow-pytorch) | 491 | [#6](https://github.com/lucidrains/rectified-flow-pytorch/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 1 | 1 | 1 | [#50](https://github.com/lucidrains/rectified-flow-pytorch/pull/50) |
| [neka-nat/kinpy](https://github.com/neka-nat/kinpy) | 181 | [#3](https://github.com/neka-nat/kinpy/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 3 | 3 | 3 | [#29](https://github.com/neka-nat/kinpy/pull/29), [#28](https://github.com/neka-nat/kinpy/pull/28), [#27](https://github.com/neka-nat/kinpy/pull/27) |
| [danijar/elements](https://github.com/danijar/elements) | 73 | [#3](https://github.com/danijar/elements/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 2 | 2 | 2 | [#18](https://github.com/danijar/elements/pull/18), [#19](https://github.com/danijar/elements/pull/19) |
| [stephane-caron/qpmpc](https://github.com/stephane-caron/qpmpc) | 56 | [#2](https://github.com/stephane-caron/qpmpc/graphs/contributors?all=1)<br><sub>2026-11-05 · retained</sub> | 4 | 5 | 3 | [#17](https://github.com/stephane-caron/qpmpc/pull/17), [#16](https://github.com/stephane-caron/qpmpc/pull/16), [#15](https://github.com/stephane-caron/qpmpc/pull/15) |

`—` denotes absence from the complete displayed top 100. TD-MPC2, whose original PR was cherry-picked, is in the separate adopted-work section.

## Changes since 6 November 2026 · 11:10 CST (UTC+8)

| Measure | Previous | Current |
|---|---:|---:|
| Verified merged author PRs | 142 | 154 |
| Merged-PR repositories | 31 | 32 |
| Accepted-contribution repositories | 32 | 33 |
| Default-branch author commits | 153 | 165 |
| Merged PRs in projects above 10,000 stars | 78 | 88 |
| Separately adopted integrations/cherry-picks | 12 | 14 |
| Homepage projects at or above 1,000 stars | 25 | 26 |
| Visible top-30 projects | 13 | 13 |
| Personal software stars | 14 | 15 |
| Personal software default-branch commits | 145 | 145 |

### Current graph changes

Only changes in the official graph positions or graph commit counts are shown. A newly recorded repository has no previous observed position.

| Project | Previous position / graph commits | Current position / graph commits |
|---|---|---|
| [morluto/rea](https://github.com/morluto/rea/graphs/contributors?all=1) | #60 / 6 | #65 / 6 |
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem/graphs/contributors?all=1) | #67 / 4 | #52 / 5 |
| [storytold/craft-anything](https://github.com/storytold/craft-anything/graphs/contributors?all=1) | #2 / 35 | #2 / 44 |
| [colmap/colmap](https://github.com/colmap/colmap/graphs/contributors?all=1) | #55 / 2 | #49 / 2 |
| [kornia/kornia](https://github.com/kornia/kornia/graphs/contributors?all=1) | Absent from displayed top 100 | #85 / 6 |
| [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail/graphs/contributors?all=1) | #19 / 2 | #17 / 3 |
| [openMVG/openMVG](https://github.com/openMVG/openMVG/graphs/contributors?all=1) | New project | #96 / 1 |

### New directly merged author PRs

| Merged (Asia/Shanghai) | Project / PR | Final merge | Engineering change |
|---|---|---|---|
| 2026-11-07 17:28 | thedotmack/claude-mem [#5458](https://github.com/thedotmack/claude-mem/pull/5458) | [`259bf69`](https://github.com/thedotmack/claude-mem/commit/259bf6956d4b9766f2533951aa572d39fcc59add) | Keep example code unchanged and rewrite single-quoted HTML links in translated READMEs. |
| 2026-11-07 17:24 | storytold/craft-anything [#1092](https://github.com/storytold/craft-anything/pull/1092) | [`464935e`](https://github.com/storytold/craft-anything/commit/464935ef96d0e72d1d1752a58f8e27f57607edad) | Launch a Go project from a single cmd/*/main.go entrypoint without guessing between commands. |
| 2026-11-07 17:24 | storytold/craft-anything [#1090](https://github.com/storytold/craft-anything/pull/1090) | [`d8087e7`](https://github.com/storytold/craft-anything/commit/d8087e70fc2990f3b261d122427d9d4e0cde7e0c) | Decode bounded DNS service records and retain addresses from questionless replies. |
| 2026-11-07 16:42 | storytold/craft-anything [#1093](https://github.com/storytold/craft-anything/pull/1093) | [`23000e3`](https://github.com/storytold/craft-anything/commit/23000e314a6868d3d598065d75f4e9c1a4ba5805) | Keep system tools and single-player media applications on the application build path. |
| 2026-11-07 16:42 | storytold/craft-anything [#1091](https://github.com/storytold/craft-anything/pull/1091) | [`aed326c`](https://github.com/storytold/craft-anything/commit/aed326ca6d74bfd119a3d1b191257c8f06fe3c51) | Charge malformed pcapng packet records to the scan budget and handle invalid timestamp fractions explicitly. |
| 2026-11-07 16:40 | storytold/craft-anything [#1089](https://github.com/storytold/craft-anything/pull/1089) | [`6cbc669`](https://github.com/storytold/craft-anything/commit/6cbc66984c518bf4af7ed261594431eceba54e95) | Detect malformed TLS ClientHello offers while preserving unknown version values. |
| 2026-11-07 16:37 | storytold/craft-anything [#1088](https://github.com/storytold/craft-anything/pull/1088) | [`2a5845c`](https://github.com/storytold/craft-anything/commit/2a5845c64b4a863c8a8d223041e863ba99c416a5) | Export six half- and single-precision Unity texture layouts as 8-bit PNG. |
| 2026-11-07 09:15 | openMVG/openMVG [#2445](https://github.com/openMVG/openMVG/pull/2445) | [`5f84739`](https://github.com/openMVG/openMVG/commit/5f84739844e8bc6aba243128498ff44910f60b66) | Restore bearing-aligned cheirality checks for spherical-camera DLT triangulation. |
| 2026-11-07 04:43 | kornia/kornia [#6580](https://github.com/kornia/kornia/pull/6580) | [`1c52e60`](https://github.com/kornia/kornia/commit/1c52e60146fbd1ff53dc4611600a06b53919d4e8) | Accumulate weighted float16 and bfloat16 meter updates in float32 while retaining the original last value. |
| 2026-11-07 01:29 | kornia/kornia [#6582](https://github.com/kornia/kornia/pull/6582) | [`52ed4c7`](https://github.com/kornia/kornia/commit/52ed4c7aada4adac9e8270df0c00949219e07f2c) | Export bfloat16 images to NumPy as float32 while preserving the stored layout. |
| 2026-11-06 23:16 | storytold/craft-anything [#767](https://github.com/storytold/craft-anything/pull/767) | [`ccfb5d4`](https://github.com/storytold/craft-anything/commit/ccfb5d48fc39dcf9d6ece3b96e912a8eb62d283d) | Make loopback-request and cancellation tests wait for the conditions they assert. |
| 2026-11-06 21:32 | JetBrains/thinkrail [#1184](https://github.com/JetBrains/thinkrail/pull/1184) | [`d39ef8b`](https://github.com/JetBrains/thinkrail/commit/d39ef8bc8504de6e6a66c6358aa02b4095d55b33) | Identify SVG from the first XML element in a bounded file prefix. |

#### thedotmack/claude-mem #5458

A Markdown parser supplies code-block source line ranges instead of toggling on fence-looking strings; quote-aware attribute rewrites preserve the original delimiters for href, src and srcset.

Scope: Affects the README translation utility, not runtime memory or model behavior.

Evidence: [#5458](https://github.com/thedotmack/claude-mem/pull/5458) · [final merged commit](https://github.com/thedotmack/claude-mem/commit/259bf6956d4b9766f2533951aa572d39fcc59add).

#### storytold/craft-anything #1092

The bounded directory scan only selects an unambiguous command package and supplies it as a separate go run argument, keeping the root main.go recipe first.

Scope: Recognizes a specific layout with a bounded scan, not arbitrary recursive Go package discovery.

Evidence: [#1092](https://github.com/storytold/craft-anything/pull/1092) · [final merged commit](https://github.com/storytold/craft-anything/commit/464935ef96d0e72d1d1752a58f8e27f57607edad).

#### storytold/craft-anything #1090

The reader validates type-specific RDATA, including SOA, SRV and CAA; separates mDNS name/compression and class handling where needed, and uses the answer owner when a reply has no question.

Scope: Summarizes observed packets, not a DNS resolver or full protocol implementation; incomplete observations remain identified.

Evidence: [#1090](https://github.com/storytold/craft-anything/pull/1090) · [final merged commit](https://github.com/storytold/craft-anything/commit/d8087e70fc2990f3b261d122427d9d4e0cde7e0c).

#### storytold/craft-anything #1093

Refines word boundaries, normalized whitespace and contextual checks around level/player terms without losing explicit game examples.

Scope: A targeted request-routing heuristic; no general classification accuracy benchmark.

Evidence: [#1093](https://github.com/storytold/craft-anything/pull/1093) · [final merged commit](https://github.com/storytold/craft-anything/commit/23000e314a6868d3d598065d75f4e9c1a4ba5805).

#### storytold/craft-anything #1091

Rejected packet blocks with overflowing data extents or unknown interfaces now consume the same packet budget as accepted records. The parser aggregates warning reasons, withholds invalid classic-PCAP timestamps, and handles subnanosecond decimal resolutions without discarding a valid zero fractional result.

Scope: Bounds the handled packet records, not every byte or every pcapng block type. Timestamps remain integer nanoseconds; no timing-precision benchmark is claimed.

Evidence: [#1091](https://github.com/storytold/craft-anything/pull/1091) · [final merged commit](https://github.com/storytold/craft-anything/commit/aed326ca6d74bfd119a3d1b191257c8f06fe3c51).

#### storytold/craft-anything #1089

The packet parser checks variable-length offers, marks duplicate or inconsistent extensions as partial, and continues validating ALPN after reaching the retained-output cap. Only reserved GREASE values receive that label.

Scope: A passive capture parser, not a TLS endpoint or a security/protocol-conformance certification.

Evidence: [#1089](https://github.com/storytold/craft-anything/pull/1089) · [final merged commit](https://github.com/storytold/craft-anything/commit/6cbc66984c518bf4af7ed261594431eceba54e95).

#### storytold/craft-anything #1088

The texture decoder distinguishes R, RG and RGBA samples; it converts linear RGB to sRGB, leaves alpha linear, checks required byte lengths, and handles half-float NaNs separately from infinity.

Scope: The export is a clipped 8-bit visualization, not lossless HDR output. It does not add support for every Unity texture format.

Evidence: [#1088](https://github.com/storytold/craft-anything/pull/1088) · [final merged commit](https://github.com/storytold/craft-anything/commit/2a5845c64b4a863c8a8d223041e863ba99c416a5).

#### openMVG/openMVG #2445

The reconstructed point must have a positive dot product with each observed bearing in its own camera frame. This accepts valid rear-hemisphere points and rejects antipodal rays even when their projective DLT constraints coincide.

Scope: Changes the oriented-depth validity test, not the linear triangulation solver or a measured reconstruction-accuracy result.

Evidence: [#2445](https://github.com/openMVG/openMVG/pull/2445) · [final merged commit](https://github.com/openMVG/openMVG/commit/5f84739844e8bc6aba243128498ff44910f60b66).

#### kornia/kornia #6580

Promotion happens before weighting, preventing avoidable FP16 overflow and low-precision running-sum loss. Other input types keep their existing promotion behavior.

Scope: Applies to AverageMeter's running totals; no training-accuracy or performance benchmark.

Evidence: [#6580](https://github.com/kornia/kornia/pull/6580) · [final merged commit](https://github.com/kornia/kornia/commit/1c52e60146fbd1ff53dc4611600a06b53919d4e8).

#### kornia/kornia #6582

Only the unsupported bfloat16 NumPy export needs a dtype conversion; the image object and its metadata remain intact, and supported CPU data can retain shared storage.

Scope: The bfloat16 path copies; it is not zero-copy, and does not change the stored tensor dtype or DLPack format.

Evidence: [#6582](https://github.com/kornia/kornia/pull/6582) · [final merged commit](https://github.com/kornia/kornia/commit/52ed4c7aada4adac9e8270df0c00949219e07f2c).

#### storytold/craft-anything #767

Test fixtures wait for complete bounded HTTP headers and check the lifetime of the mock replay answerer after shutdown; the unavailable-endpoint fixture avoids a transient listener.

Scope: Changes test fixtures and accompanying documentation. No production cancellation or networking fix is claimed.

Evidence: [#767](https://github.com/storytold/craft-anything/pull/767) · [final merged commit](https://github.com/storytold/craft-anything/commit/ccfb5d48fc39dcf9d6ece3b96e912a8eb62d283d).

#### JetBrains/thinkrail #1184

The file classifier skips declarations, processing instructions, comments and doctypes; the doctype scanner tracks quoted text and internal-subset depth before checking the document root.

Scope: A bounded MIME classifier, not a general XML validator or SVG sanitizer.

Evidence: [#1184](https://github.com/JetBrains/thinkrail/pull/1184) · [final merged commit](https://github.com/JetBrains/thinkrail/commit/d39ef8bc8504de6e6a66c6358aa02b4095d55b33).

## Other accepted work

The following **14 separately accepted integrations and cherry-picks** are excluded from the **154 directly merged author PRs**. Original PRs here were closed without being directly merged. The [snapshot](contributions-2026-11-07-2237.json) records upstream links, commits, authors and the dates each identity and branch observation was verified.

| Project / original PR | Adoption evidence | Attribution |
|---|---|---|
| TD-MPC2 [#98](https://github.com/nicklashansen/tdmpc2/pull/98) | [Implementation cherry-pick](https://github.com/nicklashansen/tdmpc2/commit/332f19e4aba4bffe2dc736f45ea7f7bdc585903a); the authored commit remains in the verified default-branch history. Target-Q history and evaluation mode are preserved during model conversion. | Commit author is Afloat16. This separately adopted contribution brings the accepted-project total to 33; current stars: 999, retained graph position [#6](https://github.com/nicklashansen/tdmpc2/graphs/contributors?all=1) / 1 commit contribution, read 2026-11-05 11:23 Asia/Shanghai. |
| Robotics Toolbox [#735](https://github.com/petercorke/robotics-toolbox-python/pull/735) | Adopted by merged [#883](https://github.com/petercorke/robotics-toolbox-python/pull/883), 22 October 2026; [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/6b85d77c01d0ececacc57cf46a1613b3e8caf09e). Circular particle-heading moments. | Maintainer-authored squash retains `Co-authored-by: Afloat <132809511+Afloat16@users.noreply.github.com>`. |
| Robotics Toolbox [#736](https://github.com/petercorke/robotics-toolbox-python/pull/736) | Adopted by merged [#805](https://github.com/petercorke/robotics-toolbox-python/pull/805), 16 October 2026 (Asia/Shanghai); [squash commit](https://github.com/petercorke/robotics-toolbox-python/commit/97c6c0fe15038069c366e5474b3a7fb1cd215fa2). Normalized-time quintic trajectories and the Hermite alternative. | Maintainer-authored squash retains the same Afloat co-author trailer. |
| Craft Anything<br>[#591](https://github.com/storytold/craft-anything/pull/591), [#592](https://github.com/storytold/craft-anything/pull/592), [#593](https://github.com/storytold/craft-anything/pull/593), [#594](https://github.com/storytold/craft-anything/pull/594), [#595](https://github.com/storytold/craft-anything/pull/595), [#596](https://github.com/storytold/craft-anything/pull/596) | Adopted by merged [#645](https://github.com/storytold/craft-anything/pull/645), 2026-11-03 20:58 (Asia/Shanghai); [commit `0eea78d`](https://github.com/storytold/craft-anything/commit/0eea78d7aa50a4943c8cf60c1a3dcadf0d85e658). HTML scanner correctness for tag boundaries, raw-text elements, preload token lists and URL character references. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 6 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#597](https://github.com/storytold/craft-anything/pull/597), [#598](https://github.com/storytold/craft-anything/pull/598), [#600](https://github.com/storytold/craft-anything/pull/600), [#601](https://github.com/storytold/craft-anything/pull/601) | Adopted by merged [#649](https://github.com/storytold/craft-anything/pull/649), 2026-11-03 21:07 (Asia/Shanghai); [commit `3ee1642`](https://github.com/storytold/craft-anything/commit/3ee164277023a3d76a3859f5796782eba6260f3f). Local preview request scoping, streaming file responses and bounded connection handling. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 4 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#602](https://github.com/storytold/craft-anything/pull/602), [#603](https://github.com/storytold/craft-anything/pull/603), [#604](https://github.com/storytold/craft-anything/pull/604), [#605](https://github.com/storytold/craft-anything/pull/605) | Adopted by merged [#648](https://github.com/storytold/craft-anything/pull/648), 2026-11-03 21:25 (Asia/Shanghai); [commit `82856a3`](https://github.com/storytold/craft-anything/commit/82856a30b2e464018616bcbb5822927ce241f0bc). HAR credential redaction, decoded-byte accounting and valid-date path templates. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 4 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#606](https://github.com/storytold/craft-anything/pull/606), [#607](https://github.com/storytold/craft-anything/pull/607), [#608](https://github.com/storytold/craft-anything/pull/608), [#609](https://github.com/storytold/craft-anything/pull/609), [#610](https://github.com/storytold/craft-anything/pull/610), [#611](https://github.com/storytold/craft-anything/pull/611), [#612](https://github.com/storytold/craft-anything/pull/612), [#613](https://github.com/storytold/craft-anything/pull/613), [#614](https://github.com/storytold/craft-anything/pull/614), [#615](https://github.com/storytold/craft-anything/pull/615) | Adopted by merged [#652](https://github.com/storytold/craft-anything/pull/652), 2026-11-03 21:29 (Asia/Shanghai); [commit `15de366`](https://github.com/storytold/craft-anything/commit/15de36614b2d1039ed68bffcc36e0e92053b3f12). Binary plist, OID, base64, source-map and archive parser correctness. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 10 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#616](https://github.com/storytold/craft-anything/pull/616), [#617](https://github.com/storytold/craft-anything/pull/617), [#619](https://github.com/storytold/craft-anything/pull/619), [#620](https://github.com/storytold/craft-anything/pull/620), [#621](https://github.com/storytold/craft-anything/pull/621) | Adopted by merged [#653](https://github.com/storytold/craft-anything/pull/653), 2026-11-03 21:41 (Asia/Shanghai); [commit `aeb86a6`](https://github.com/storytold/craft-anything/commit/aeb86a69a35db8afca288a616e8622e866e03c52). Agent availability and Windows discovery, chat-model gating, bounded SSE events and retry request preservation. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 5 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#640](https://github.com/storytold/craft-anything/pull/640), [#641](https://github.com/storytold/craft-anything/pull/641), [#642](https://github.com/storytold/craft-anything/pull/642) | Adopted by merged [#656](https://github.com/storytold/craft-anything/pull/656), 2026-11-03 21:49 (Asia/Shanghai); [commit `ebed13d`](https://github.com/storytold/craft-anything/commit/ebed13d0fcb8d75932f8a512a7e680e375a013cd). Conditional ARM32 call dataflow, esbuild dependency discovery under caps and distinct window-comparison labels. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 3 source PRs are Afloat16-authored and were closed without direct merges. |
| Craft Anything<br>[#676](https://github.com/storytold/craft-anything/pull/676) | Adopted by merged [#683](https://github.com/storytold/craft-anything/pull/683), 2026-11-04 01:33 (Asia/Shanghai); [commit `636b3ff`](https://github.com/storytold/craft-anything/commit/636b3ff3d78cc50962375618a42c7972b60f2be2). Bound CRC-CPIO checksum work across firmware probes, with shared byte limits, cancellation checks and explicit skipped-verification results. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The source PR is Afloat16-authored and was closed without a direct merge. |
| Craft Anything<br>[#688](https://github.com/storytold/craft-anything/pull/688), [#690](https://github.com/storytold/craft-anything/pull/690), [#691](https://github.com/storytold/craft-anything/pull/691), [#692](https://github.com/storytold/craft-anything/pull/692), [#693](https://github.com/storytold/craft-anything/pull/693), [#694](https://github.com/storytold/craft-anything/pull/694), [#695](https://github.com/storytold/craft-anything/pull/695), [#696](https://github.com/storytold/craft-anything/pull/696), [#697](https://github.com/storytold/craft-anything/pull/697), [#698](https://github.com/storytold/craft-anything/pull/698), [#699](https://github.com/storytold/craft-anything/pull/699), [#700](https://github.com/storytold/craft-anything/pull/700), [#701](https://github.com/storytold/craft-anything/pull/701), [#702](https://github.com/storytold/craft-anything/pull/702), [#703](https://github.com/storytold/craft-anything/pull/703), [#704](https://github.com/storytold/craft-anything/pull/704), [#705](https://github.com/storytold/craft-anything/pull/705), [#706](https://github.com/storytold/craft-anything/pull/706), [#707](https://github.com/storytold/craft-anything/pull/707), [#708](https://github.com/storytold/craft-anything/pull/708), [#709](https://github.com/storytold/craft-anything/pull/709), [#710](https://github.com/storytold/craft-anything/pull/710), [#711](https://github.com/storytold/craft-anything/pull/711), [#712](https://github.com/storytold/craft-anything/pull/712), [#713](https://github.com/storytold/craft-anything/pull/713), [#714](https://github.com/storytold/craft-anything/pull/714), [#715](https://github.com/storytold/craft-anything/pull/715) | Adopted by merged [#722](https://github.com/storytold/craft-anything/pull/722), 2026-11-04 02:43 (Asia/Shanghai); [commit `b9ca099`](https://github.com/storytold/craft-anything/commit/b9ca099903aeef5d4b33a7e83e8e7062ab94c65a). Respect declared lengths and reject invalid values across bytecode, database, archive, filesystem, configuration and packet parsers. | Integration PR and commit author: `bflatastic`; retains the Afloat co-author trailer. The 27 source PRs are Afloat16-authored and were closed without direct merges. |
| Claude-Mem<br>[#5339](https://github.com/thedotmack/claude-mem/pull/5339) | Extra invalid-input regression cases adopted into merged [#5336](https://github.com/thedotmack/claude-mem/pull/5336), 2026-11-04 11:18 (Asia/Shanghai); [commit `de134d3`](https://github.com/thedotmack/claude-mem/commit/de134d3be64d2b835b4f8fe933b53fa5fb983198). | PR and final-commit author: `ryrenz`; maintainer `thedotmack` integrated the extra tests and retained the Afloat co-author trailer. Only the rejection tests are credited to Afloat; #5339's production implementation was not adopted. |
| Craft Anything<br>[#842](https://github.com/storytold/craft-anything/pull/842), [#844](https://github.com/storytold/craft-anything/pull/844), [#877](https://github.com/storytold/craft-anything/pull/877), [#878](https://github.com/storytold/craft-anything/pull/878), [#879](https://github.com/storytold/craft-anything/pull/879), [#880](https://github.com/storytold/craft-anything/pull/880), [#881](https://github.com/storytold/craft-anything/pull/881), [#882](https://github.com/storytold/craft-anything/pull/882), [#883](https://github.com/storytold/craft-anything/pull/883), [#884](https://github.com/storytold/craft-anything/pull/884), [#885](https://github.com/storytold/craft-anything/pull/885), [#886](https://github.com/storytold/craft-anything/pull/886), [#888](https://github.com/storytold/craft-anything/pull/888), [#889](https://github.com/storytold/craft-anything/pull/889), [#890](https://github.com/storytold/craft-anything/pull/890), [#891](https://github.com/storytold/craft-anything/pull/891), [#892](https://github.com/storytold/craft-anything/pull/892), [#893](https://github.com/storytold/craft-anything/pull/893), [#894](https://github.com/storytold/craft-anything/pull/894), [#895](https://github.com/storytold/craft-anything/pull/895), [#896](https://github.com/storytold/craft-anything/pull/896), [#897](https://github.com/storytold/craft-anything/pull/897), [#898](https://github.com/storytold/craft-anything/pull/898), [#899](https://github.com/storytold/craft-anything/pull/899), [#900](https://github.com/storytold/craft-anything/pull/900), [#901](https://github.com/storytold/craft-anything/pull/901), [#902](https://github.com/storytold/craft-anything/pull/902), [#903](https://github.com/storytold/craft-anything/pull/903), [#904](https://github.com/storytold/craft-anything/pull/904), [#905](https://github.com/storytold/craft-anything/pull/905), [#906](https://github.com/storytold/craft-anything/pull/906), [#907](https://github.com/storytold/craft-anything/pull/907) | Adopted by [#986](https://github.com/storytold/craft-anything/pull/986), 2026-11-07 00:10 (Asia/Shanghai); [commit `60409b6`](https://github.com/storytold/craft-anything/commit/60409b684c805482cfa3965fbc368bcc26de106d). Bounded binary-format parsing: declared-length and value checks for network captures, archives, Unity/Unreal, binaries and other formats. | Integration PR and final commit: `bflatastic`. The final squash includes an Afloat trailer. The maintainer combined overlapping DNS fixes from [#842](https://github.com/storytold/craft-anything/pull/842), [#880](https://github.com/storytold/craft-anything/pull/880) and [#881](https://github.com/storytold/craft-anything/pull/881); the ZIP padding contribution from [#975](https://github.com/storytold/craft-anything/pull/975) is by `Silvertree2010`. |
| Craft Anything<br>[#716](https://github.com/storytold/craft-anything/pull/716), [#718](https://github.com/storytold/craft-anything/pull/718) | Adopted by [#995](https://github.com/storytold/craft-anything/pull/995), 2026-11-07 00:50 (Asia/Shanghai); [commit `e0922f4`](https://github.com/storytold/craft-anything/commit/e0922f4ff4568af4118618951dab5ca4378ee995). Exclusive creation of atomic-write temporary files and preservation of distinct HTTP replay samples. | Integration PR and final commit: `bflatastic`. The final squash has no Afloat trailer. The author retained the source commits; [#1012](https://github.com/storytold/craft-anything/pull/1012) later restored attribution separately. Pasted-picture naming in [#733](https://github.com/storytold/craft-anything/pull/733) is by `HerrnJung`. |

**Craft Anything: 94 original PRs, 10 maintainer integrations.** The earlier eight integrations account for 60 original PRs. Two new integrations account for 34 more: #986 replays 32 parser PRs; #995 replays #716 and #718. Each of those 34 Afloat16-authored PRs was directly verified closed without merge, and each original head SHA was located in the complete integration commit list ([#986 commits](https://github.com/storytold/craft-anything/pull/986/commits), [#995 commits](https://github.com/storytold/craft-anything/pull/995/commits)). Those exact source mappings, the relevant final patch and default-branch presence establish adoption; a “supersedes” note alone would not.

The eight earlier integration commits and the new [#986](https://github.com/storytold/craft-anything/pull/986) include an Afloat co-author trailer. [#995](https://github.com/storytold/craft-anything/pull/995) has **no** such trailer. In [#1012](https://github.com/storytold/craft-anything/pull/1012) ([commit `b186f01`](https://github.com/storytold/craft-anything/commit/b186f01af1f00fa4da5f4da7c6e1793e09ab5d1d)), the maintainer documented lost co-author credits for thirteen squash merges, including #995, and credited Afloat among the affected contributors. That single documentation commit is an attribution correction, **not an eleventh code integration**. Thus there are ten named Craft commits with Afloat trailers, but their membership differs from the ten code integrations. No graph position or commit count is inferred from those sets.

Two pages of Craft’s default-branch history (200 commits) covered the interval since the previous snapshot. The two new code integrations, the attribution correction and older integrations #683 and #722 were seen in those pages. The other six older Craft integrations retain their prior presence dates. Across all 12 previously documented adoption records, the earlier TD-MPC2 cherry-pick, the two Robotics Toolbox squashes and those two Craft commits were re-observed. Claude-Mem’s older #5336 is outside its current latest-100 window; its previous presence verification remains dated 6 November. Original identity checks for all 12 retain their earlier dates.

Integration authors also contributed implementation work. In Craft #722, for instance, the maintainer manually combined SQLite encoding and page-bound changes. In Claude-Mem #5336, Afloat’s credit covers the five invalid-input regression cases, while `ryrenz` wrote the production numeric-string normalization. The entire combined diff is not attributed to Afloat. Upstream tests were not rerun during this review.

Previously excluded Craft sources remain excluded: #599 from #649, #618 from #653, #689 from #722, and the superseded proposals #681 and #768 without a verified adoption mapping. The ten Craft integrations, the two Robotics Toolbox adoptions, the Claude-Mem tests and the TD-MPC2 cherry-pick are recorded separately from **154 directly merged author PRs / 165 default-branch author commits**. Each upstream repository is counted once.
