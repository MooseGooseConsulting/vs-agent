# Repository constraints

- Model access uses the official `openai-codex` SDK managed OAuth path. Never read, copy, export, log, or commit OAuth credentials.
- Models propose movement; `spine/controller.py` remains the sole movement-input writer.
- `episodes/`, `eval_set/`, and experiment ledgers are append-only.
