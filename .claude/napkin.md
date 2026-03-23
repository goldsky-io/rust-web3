# Napkin

## Corrections
| Date | Source | What Went Wrong | What To Do Instead |
|------|--------|----------------|-------------------|

## User Preferences
- (accumulate here as you learn them)

## Patterns That Work
- (approaches that succeeded)

## Patterns That Don't Work
- (approaches that failed and why)

## Domain Notes
- rust-web3 fork chain: tomusdrw/rust-web3 → graphprotocol/rust-web3 → goldsky-io/rust-web3
- Default branch changed to `goldsky-reqwest-tracing-2` (was `master`) on 2026-03-23
- `goldsky-reqwest-tracing-2` is the production branch consumed by goldsky-io/graph-node
- `master` branch is old (v0.10.0-graph) with outdated deps — not used by anything
- Production branch (v0.19.0-graph) uses reqwest for HTTP, soketto for WS
