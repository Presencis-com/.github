# Presencis

Open standards, schemas, and offline verification tools for **Sovereign AI Assurance**.

Presencis publishes the machine-readable document schemas, regulatory crosswalks, and offline cryptographic verifiers behind AI Bills of Materials (**AI-BOM**), Cryptographic Bills of Materials (**CBOM**), Verified Software Bills of Materials (**VSBOM**), and post-quantum signed evidence receipts (`Ed25519` + FIPS 204 `ML-DSA-65`).

## Canonical Surfaces

- **Platform & Documentation:** https://presencis.com/
- **Aegis Assurance & Quad-BOM:** https://presencis.com/aegis/
- **Vigil Runtime Observation:** https://presencis.com/vigil/
- **Halo Cryptography & Receipts:** https://presencis.com/halo/
- **Hugging Face Organization:** https://huggingface.co/presencis
- **npm Scope:** `@presencis` (`https://www.npmjs.com/org/presencis`)

## Open Repositories & Datasets

| Asset | Platform | Location | Purpose |
| --- | --- | --- | --- |
| `.github` | GitHub | https://github.com/Presencis-com/.github | Organization profile, coordinated disclosure (`SECURITY.md`), Apache-2.0 license |
| `bom-schemas` (`@presencis/bom-schemas`) | GitHub / npm | https://github.com/Presencis-com/bom-schemas | JSON Schema Draft 2020-12 + Zod validators for AI-BOM, CBOM, and VSBOM |
| `halo-verify` (`@presencis/halo-verify`) | GitHub / npm | https://github.com/Presencis-com/halo-verify | Offline `Ed25519` + FIPS 204 `ML-DSA-65` evidence & audit receipt verifier CLI/library |
| `regulatory-crosswalks` | GitHub | https://github.com/Presencis-com/regulatory-crosswalks | Cross-framework crosswalks across 95 global AI, cyber, healthcare, and privacy regimes |
| `regulatory-mcp` (`@presencis/regulatory-mcp`) | GitHub / npm | https://github.com/Presencis-com/regulatory-mcp | Read-only stdio MCP server for frameworks, crosswalks, and compliance Q&As |
| `regulatory-clause-qa-bench` | Hugging Face | https://huggingface.co/datasets/presencis/regulatory-clause-qa-bench | 360 regulatory Q&A benchmark rows grounded to https://presencis.com/questions/ |
| `shadow-ai-endpoint-taxonomy` | Hugging Face | https://huggingface.co/datasets/presencis/shadow-ai-endpoint-taxonomy | Egress classification taxonomy for 54 commercial AI, coding, and agent endpoints |
| `posture-receipt-inspector` | Hugging Face Space | https://huggingface.co/spaces/presencis/posture-receipt-inspector | Zero-egress client-side browser inspector for AI-BOM, CBOM, VSBOM, and signed receipts |

## Security & Licensing

All repositories and datasets listed above are released under the **Apache License 2.0**. Report security vulnerabilities to **security@presencis.com** — see [SECURITY.md](https://github.com/Presencis-com/.github/blob/main/SECURITY.md).

