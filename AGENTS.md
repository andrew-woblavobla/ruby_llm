# Repository instructions

- Read `CLAUDE.local.md` before running tests, builds, linters, or other heavy commands. It is the source of truth for the local and devbox workflow, including which commands must stay on the host.
- Treat tool-specific wording in that file as workflow intent. Use equivalent available tools without weakening its safety checks or completion criteria.
- Work from the repository root. Preserve unrelated changes and stage only files belonging to the requested task.
- Never commit credentials, private keys, tokens, local environment files, or generated secret material.
- Do not deploy, migrate production data, rotate credentials, or make other external changes unless the task explicitly requires it.
