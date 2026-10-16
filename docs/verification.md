# Verification

Command: `npm test` with Node.js 24.13.0 and ethers 6.17.0 available in the isolated validation environment.

**11 tests passed; 0 failed or skipped.** Checks cover funding-order routes, launch-leg sequencing/pause messages, chain-specific identifiers and detail selection, and post-launch links.

All relative Solidity imports in the extraction resolve to copied files. These helper tests do not establish Solidity compilation, successful token deployment, V4 integration, transaction funding, backend reconciliation, or current live contract configuration.

Copied source digests match `SOURCE_MANIFEST.json`. Explicit dependency versions exist in the package registry and were not marked deprecated when checked. Review [NOTICE.md](../NOTICE.md): upstream package metadata includes BUSL/LZBL declarations; Armoreum's MIT License does not replace them.
