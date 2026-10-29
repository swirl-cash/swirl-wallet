# SWIRL Wallet

Browser extension, dApp bridge, private-note wallet and recovery tools.

## Source layout

- `apps/extension`: Manifest V3 wallet and browser verification.
- `packages/wallet`: keys, addresses, encryption, notes and proofs.
- `packages/contracts/build/circuits`: public artifacts required by wallet tests.

This is the component source snapshot of the tested SWIRL Protocol workspace. For the root dependency lockfile, integrated build and complete cross-component test flow, use [swirl-protocol](https://github.com/swirl-cash/swirl-protocol).

Never commit real private keys, recovery phrases, API credentials, server environment files or local service state. Public contract addresses, verification keys and proving artifacts are not account credentials.
