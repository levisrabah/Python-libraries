---
name: snyk-security-at-inception
description: Guide Copilot to generate secure code following Snyk best practices
applyTo: "**"
---

## Security-first coding rules (Copilot)

When generating or modifying code:

- Prefer secure-by-default libraries and APIs.
- Never hardcode secrets (API keys, tokens, credentials).
- Always suggest environment variables or secret managers for sensitive values.
- Validate and sanitize all external input.
- Use safe dependency versions and avoid known vulnerable packages.
- When applicable, generate code compatible with Snyk Code and Snyk Open Source scanning.

## Fix guidance

- If security issues are detected in newly generated code, suggest fixes inline.
- After applying fixes, ensure no new vulnerabilities are introduced.
- Favor clarity and maintainability when applying security fixes.
