# WORKBLOCK sample packages

Sample AI team configurations (`*.workblock.json`) for the WORKBLOCK v2 market's **GitHub import**.

- `packages/hello-research.workblock.json` — two-step example: summarize pasted public material, then a second AI reviews the summary for unsupported claims. CC0-1.0.

## Use in WORKBLOCK
AI 팀 마켓 → **GitHub에서 가져오기** → `PPBJ/workblock-sample-packages` → 찾기 → 가져오기.
WORKBLOCK resolves the commit SHA, checks format and security before import, and records the file hash as provenance. Imported packages never run automatically.

## Publish your own
Add a `*.workblock.json` file (≤ 1 MiB) to a public repository and give the repository the topic `workblock-package`.
