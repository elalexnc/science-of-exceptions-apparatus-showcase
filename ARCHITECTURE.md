# Architecture (Public-Safe)

## Directory-level roles
- `ultrasound_whitepaper_refresh/og_reconstruction/`
  - Historical/protocol-faithful reconstruction track.
- `ultrasound_whitepaper_refresh/enhanced_2026/`
  - Safety-forward modernization track.
- `ultrasound_whitepaper_refresh/research/`
  - Context docs, sourcing notes, and high-level regulatory orientation.

## Conceptual flow
```mermaid
flowchart TD
  A["Archival Inputs"] --> B["OG Reconstruction"]
  A --> C["Enhanced 2026 Path"]
  B --> D["Comparative Analysis"]
  C --> D
  D --> E["Public-Safe Research Outputs"]
  E --> F["Private Technical Review"]
```

## Scope note
This architecture description is intentionally non-operational and excludes implementation detail.
