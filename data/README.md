# Data

This directory is reserved for sanitized, machine-readable project data.

## Safe candidates

- Public release metadata
- Spotify artist/release IDs and URLs
- Catalog exports with sensitive fields removed
- Public metric snapshots
- Example schemas

## Keep private

Do not commit:

- passwords
- API secrets or OAuth tokens
- private Spotify for Artists exports
- unredacted earnings data
- private contact information
- private label or promoter correspondence

Use ignored directories such as `data/private/`, `data/exports/`, or `data/snapshots/` for local-only material.

## Possible files

```text
releases.json
spotify-public.json
private-metrics.example.csv
```

Document the source and update date inside each dataset so AI assistants do not treat stale numbers as current.

