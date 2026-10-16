# Armoreum Launchpad

Armoreum token-deployer, V4 launch/seeding, and multichain launch source with routing and funding helpers.

[MIT License](LICENSE) · [Contributing](CONTRIBUTING.md) · [Security](SECURITY.md) · [Releases](https://github.com/armoreum/armoreum-launchpad/releases) · [Support](mailto:support@armoreum.io)

## Status

**Source preview extracted from actual supplied code.** This is a focused module repository, not an additional original package found in the archives. The application and full contract snapshots are preserved separately. No live service, deployment, independent audit, or registry package is claimed.

## Source modules

- `src/multichain-funding.ts`
- `src/multichain-launch-sequence.ts`
- `src/launch-chain-ids.ts`
- `src/post-launch-links.ts`

The repository includes **16 Solidity files**, including the complete relative-import closure of the selected module. Compile with `npm run compile` after reviewing dependencies. Full Solidity compilation/integration tests are not claimed by this source extraction.

## Included launch responsibilities

The source includes the supplied token-deployer generations, fixed-supply token source, V4 hook factories and seeding, and multichain launch modules. Relative Solidity dependencies are included recursively.

Frontend-independent helpers cover chain-specific funding-order URL selection, launch-leg sequencing and pause messages, chain-specific identifiers/detail selection, and post-launch reference links. Tests use synthetic inputs.

The full launch UI remains in the application repository. API orchestration, funding reconciliation, persistent jobs, server authorization, shared network presets, and production deployment records were not supplied and are not fabricated here.

Source availability is not proof that a launch completed or that a contract is active. Existing receipts must be reconciled before retrying; a metadata failure must not be treated as proof that a deployment transaction failed.

## Development and verification

Use Node.js 24 or newer and review dependencies before installation:

```sh
npm install --ignore-scripts
npm test
```

The source archive had no original dependency lockfile. Dependency versions for this module are explicit, but complete transitive resolution and audit must still be reviewed. For source inspection, the copied Node tests can also be run directly after installing their runtime dependencies in an isolated environment.

See [verification](docs/verification.md) for checks actually performed. Tests use synthetic data; no funded transaction or mainnet write is part of this verification.

## Provenance and shared code

[SOURCE_MANIFEST.json](SOURCE_MANIFEST.json) records each copied source path and checksum. Read [source scope](docs/source-scope.md). Shared code is deliberately preserved when necessary; the repository count does not imply seven independent implementations or seven running services.

## Open source and releases

Project-owned source is MIT-licensed; upstream imports retain their own licenses. GitHub Releases provide tagged source ZIP/TAR archives. `private: true` prevents accidental npm publication; it does not restrict the public source. Do not treat the source preview as an audited deployable package.

## Armoreum ecosystem

[armoreum](https://github.com/armoreum/armoreum) · [armoreum-contracts](https://github.com/armoreum/armoreum-contracts) · [armoreum-authorization](https://github.com/armoreum/armoreum-authorization) · [armoreum-recovery](https://github.com/armoreum/armoreum-recovery) · [armoreum-bridge](https://github.com/armoreum/armoreum-bridge) · [armoreum-launchpad](https://github.com/armoreum/armoreum-launchpad) · [armoreum-docs](https://github.com/armoreum/armoreum-docs)

Issues and pull requests are open. General and private security contact: **support@armoreum.io**.
