# token-radar-remixco

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/remixco7/token-radar-remixco/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/remixco7/token-radar-remixco/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar, model radar-2: every rankable pre-token protocol in the sealed DefiLlama snapshot, ranked by an implied value computed from TVL, seven-day growth, age with no token, chain breadth and category, with a concrete farm plan for each one and a sortable, filterable dashboard with a detail view per protocol.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input snapshot.json
```

The snapshot is the competition kit's sealed `snapshot.json` (DefiLlama protocol index, 2026-11-14). `main.ts` reads it, writes the ranked board to `out/board.json`, the dashboard data to `out/data.js`, and copies `dashboard/` and `screenshots/` to `out/`, then writes `out/dossier.json`. Node 22.18 or later, standard library only, no install.

---

<sub>Entered on [make.fun](https://make.fun/?ref=32zaz1nt&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
