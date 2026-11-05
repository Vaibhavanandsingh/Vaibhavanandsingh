# Vaibhav Anand Singh

BIT Mesra CSE '27 · Backend & Infra Engineer · Prev SDE Intern [@ PromptCue](#experience) · 3 PRs merged into [KubeArmor (CNCF)](#open-source)

[![Vaibhavanandsingh](https://img.shields.io/badge/@Vaibhavanandsingh-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Vaibhavanandsingh)
[![Email](https://img.shields.io/badge/btech10261.23@bitmesra.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:btech10261.23@bitmesra.ac.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-anand-singh-412604299)

## Works

### Projects

1. **[BitSpot](https://github.com/Vaibhavanandsingh/BitSpot)**: A centralized-exchange MVP where an Express API is decoupled from an in-memory matching engine over Redis request/response queues, correlated per request id. Market and limit orders with partial fills, maker/taker fills and VWAP per order, with JWT auth and Postgres persistence. TypeScript.

2. **[BharatGraph](https://github.com/Vaibhavanandsingh/BharatGraph)**: Indian-name-aware entity resolution for graph fraud detection. A rule-based phonetic encoder scores **F1 0.951** against Soundex 0.758, NYSIIS 0.647 and Double Metaphone 0.463 on 500 synthetic entities — and **1.000 recall** on initials and dropped middle names, where every baseline scores 0.000. Python.

3. **[loan-eligibility-engine](https://github.com/Vaibhavanandsingh/loan-eligibility-engine)**: A streaming AWS Lambda validates and upserts **10,000 users in 2.3 s using 110 MB**. Each free-text eligibility rule is LLM-compiled once and cached by content hash, so repeat matching of 170,000 user–product pairs makes **zero LLM calls**. Moving matching from n8n into one generated SQL statement in Postgres cut network transfer from 6 MB to 9 KB and matching time from **74 s to 4 s**, with all 42,937 matches verified identical. Python.

4. **[eBPF-Network-Filtering](https://github.com/Vaibhavanandsingh/eBPF-Network-Filtering)**: eBPF network-filtering examples — configurable TCP port dropping with XDP and process-specific TCP allowlisting with cgroup eBPF, with Go loaders and demo instructions. C + Go.

### Open Source

1. **[kubearmor/KubeArmor](https://github.com/kubearmor/KubeArmor)** — CNCF sandbox runtime-security project. Three PRs merged upstream ([#2560](https://github.com/kubearmor/KubeArmor/pull/2560), [#2562](https://github.com/kubearmor/KubeArmor/pull/2562), [#2563](https://github.com/kubearmor/KubeArmor/pull/2563)): fixed workflow self-reference path filters across 3 files, upgraded `actions/checkout` to v4 across 16 workflow files, and landed a 65-file correctness pass that added a codespell check to CI.

### Experience

1. **SDE Intern — PromptCue** *(7 months)*: Built an AI aggregator on Next.js with Redis caching.

### Achievements

1. **1st place — CICADA-CTF, PANTHEON TECHFEST**, ahead of 50+ teams.
2. **Runner-up — Hackfest'25, IIT (ISM) Dhanbad**: 2nd in a problem-statement track.
3. **Runner-up — Hackatron'25, BIT Sindri**: 2nd overall.
4. **3 pull requests merged** into a CNCF sandbox project (KubeArmor).

### Education

- **Birla Institute of Technology, Mesra** — B.Tech, Computer Science & Engineering *(2023 – 2027)*

## Activity

[![Vaibhav's contribution chart](https://ghchart.rshah.org/409ba5/Vaibhavanandsingh)](https://github.com/Vaibhavanandsingh)
