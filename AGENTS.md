# Project guidance

Before changing product behavior:

* Read docs/00\_INDEX.md
* Read docs/product/product-learning-spec.md

Before changing quiz/content logic:

* Read docs/content/editorial-guide.md
* Read docs/content/scenario-bank-structure.md
* Read docs/content/golden-question-set.md

Before changing review behavior:

* Read docs/learning/answer-review-system.md

Treat files under docs/ as the authoritative product specification.
Do not change product rules silently.
If implementation conflicts with the specs, report the conflict first.



\## Development workflow



Before implementation or creating a new worktree:



1\. Read `docs/00\_INDEX.md` and the relevant authoritative specs.

2\. Run `git status`.

3\. If product/content decisions have changed but the corresponding docs

&#x20;  are not updated, stop and report that first.

4\. If authoritative docs contain uncommitted changes, tell the user that

&#x20;  the docs baseline should be committed before implementation.

5\. Start implementation only from the committed baseline.

6\. Use a separate branch/worktree for parallel implementation work when appropriate.



Do not silently commit, discard, or overwrite product-spec changes.

