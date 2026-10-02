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
