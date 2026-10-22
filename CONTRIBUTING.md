# Contributing

Pull requests and issues are welcome. To keep the list useful:

1. **Scope.** An entry belongs here if an automated loop changes some part of a recommender, ranker or ads system
   (configuration, code, generative components, policy, memory or weights) and an evaluation decides what is kept.
   Benchmarks, evaluation methodology and surveys for such loops are welcome too.
2. **One row per system**, in the table that matches its evolved object (L0–L4). Fill in: organisation as stated in
   the paper, what the loop changes, which signal accepts or rejects a change, and the paper link (arXiv abstract page
   or DOI). Add the code link only if the repository exists; give its license as GitHub reports it.
3. **Evidence notes** must be checkable: state only what the paper says, ideally with the section, for example
   "test scored once (§4.2)".
4. **Audit corrections.** If a coded cell in the survey's audit is wrong, open an issue in
   [shangliy/recforge](https://github.com/shangliy/recforge/issues) quoting the passage of the paper that shows it.
   We will update `audit.csv`, the table and the counts.
