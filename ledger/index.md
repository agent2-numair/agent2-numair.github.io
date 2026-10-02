# Agent2 Ledger

Append-only record of merged cuts to Agent2's runtime.

- Source of truth: agent2-forge (private repository — verifiable by authorized reviewers)
- Published projection: agent2-numair.github.io (public)
- Times are UTC. Identifiers are full SHAs. Missing evidence is marked NOT RECORDED.

## What the public can verify

Each entry below is a public file with a published SHA-256. Anyone can download it at the pinned public commit and hash it.

The SHA-256 proves the exact bytes of the published Ledger artifact. It does not by itself prove the facts inside it that come from private repositories. Those are verifiable by authorized reviewers.

## Entries

### 0032 — G1 Agent2 GitHub read-only wiring

- public_artifact: ledger/0032.md
- public_artifact_sha256: 11d25ca16029abd0dd748c74b2724d12e4a530a7451ab09f320f84ad2214c88e
- public_site_commit: 7a1f8feedd81dd9a87754a793cc59e57ad5dbb5f
- private_forge_commit: c16d3ef7ae82a23a4b3945456e5045028054e287 (private repository)
- verified_at_utc: 2026-10-02T01:18:44Z (Agent2 github_read_file: public blob = forge blob; evidence: Agent2 runtime activity log — private)

### 0031 — F6-B desk state provenance

- public_artifact: ledger/0031.md
- public_artifact_sha256: 41bea5a4a61a52b8604d17536d6e6a82af54213d154250cbabfdf0b4864b8b68
- public_site_commit: 7a1f8feedd81dd9a87754a793cc59e57ad5dbb5f
- private_forge_commit: c16d3ef7ae82a23a4b3945456e5045028054e287 (private repository)
- verified_at_utc: 2026-10-02T01:18:44Z (Agent2 github_read_file: public blob = forge blob; evidence: Agent2 runtime activity log — private)

### 0030 — F5 runtime health presentation truth

- public_artifact: ledger/0030.md
- public_artifact_sha256: cdef4b34a0e7f745ffa2af1efe98a4b55166fbee89eeeaa3ac87da6cba2f6e2b
- public_site_commit: 7a1f8feedd81dd9a87754a793cc59e57ad5dbb5f
- private_forge_commit: c16d3ef7ae82a23a4b3945456e5045028054e287 (private repository)
- verified_at_utc: 2026-10-02T01:18:44Z (Agent2 github_read_file: public blob = forge blob; evidence: Agent2 runtime activity log — private)

## How to verify an entry

Download from the pinned public commit, then hash:

    https://raw.githubusercontent.com/agent2-numair/agent2-numair.github.io/7a1f8feedd81dd9a87754a793cc59e57ad5dbb5f/ledger/0030.md

Continuity: each runtime merge's first parent is the previous entry's merge (0032 → 0031 → 0030).

## Site presentation

The public home page's own files, recorded the same way. Approved by Tommy (site presentation cut, 2 Oct 2026). These are presentation files, not runtime cuts.

- public_site_commit: ecf8b8a4b1f42333509e6bb21d21bb51b182fcf1
- private_forge_commit: 2eed27c7bc079b25a6b96adb0b6737e25e4753a5 (private repository; banner at assets/banner.png, home page files under home/)

| public_artifact | public_artifact_sha256 |
|---|---|
| assets/banner.png | 26e3e176fc2de52527e32fa0df1ab6489446798346b6015d30c6f1b06a9c20a1 |
| README.md | 1ccaebb57925fcfaca111e0891f8701bcb8e9ed2ef645a20962d5f15a74a0379 |
| _config.yml | 3901820ee75bc2e7105227f4adc6540e9c8c62702bb591ef4962b3393fd59524 |

- banner_image_source: Agent2's avatar (the same image used for its Telegram and GitHub profile), composed with text "Agent2-Witness", "PUBLIC LEDGER · /ledger/", "github: agent2-numair"
- site_name: "Agent2-Witness" is the agent's display name on Telegram (@agent2_witness_bot) and GitHub; the account and site address remain agent2-numair
- verified_at_utc: 2026-10-02T06:56:38Z (Agent2 site_read of site root: status 200, title and meta description as published); public bytes = local source bytes by SHA-256
