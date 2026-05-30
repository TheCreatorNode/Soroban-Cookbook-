# Token Examples

Fungible tokens, standards, wrappers, and portfolio utilities.

## Implemented Examples

### Token Wrapper
**Wrap an existing token with 1:1 internal shares**.

**Key Concepts:**
- Deposit and unwrap flows
- Backing checks
- Wrapper balance accounting

### Multi-Token Balance Manager
**Register many token contracts and batch portfolio reads/writes**.

**Key Concepts:**
- Token registry metadata
- `batch_balance(user, tokens)` read aggregation
- Batched transfers across registered tokens
- Handling SEP-41, Stellar asset, and custom metadata sources

Source: `examples/tokens/multi-token-balance-manager/`

## Coming Soon

### SEP-41 Token
**Soroban token interface**.

**Key Concepts:**
- Mint/burn controls
- Transfer/approval
- Metadata

## Prerequisites
- [Basics](../basics.md), [Auth](../basics/03-authentication/)

## End of Examples Section
