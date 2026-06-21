# Helixa Aomi App V0

Read-only Aomi App for Helixa AgentDNA profile and Cred lookup.

## Tools

- `search_agents`
- `get_agent_profile`
- `check_cred`
- `compare_agents`

V0 intentionally has no minting, payments, SIWA, transaction signing, or writes. It only reads public Helixa API endpoints.

## Build verification

Verified locally with:

```bash
cargo fmt --check
cargo test --lib
cargo build
```

Drop the `helixa/` folder into an Aomi/community apps workspace for review.
