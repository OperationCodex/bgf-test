
# BFG Practice Pack

This bundle contains sample files you can commit to a test Git repository so you can practice cleaning history with **BFG Repo-Cleaner**.

## Contents
- `secrets/.env` — contains a dummy `SECRET_KEY` (pretend secret to be removed)
- `secrets/api_keys.txt` — contains dummy API keys and a fake email (PII)
- `data/public_notes.txt` — harmless file
- `data/large_blob.bin` — a generated binary blob to simulate large files
- `bfg/replacements.txt` — patterns for BFG `--replace-text`

## Suggested Practice Scenarios
1. **Delete specific files from history**: remove everything under `secrets/`.
2. **Replace secrets in history**: use `bfg/replacements.txt` to replace the `SECRET_KEY` and API keys with `[REDACTED]`.
3. **Purge large files**: delete `data/large_blob.bin` from history or set a size filter.

None of the values in this pack are real. They are for training purposes only.
