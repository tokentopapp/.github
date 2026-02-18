# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any tokentop project, please report it responsibly.

**Do NOT open a public GitHub issue for security vulnerabilities.**

Instead, use [GitHub Private Vulnerability Reporting](https://github.com/tokentopapp/tokentop/security/advisories/new) on the affected repository. Click the **Security** tab → **Advisories** → **New draft security advisory**.

You should receive an acknowledgment within 48 hours. We will work with you to understand the issue and coordinate a fix before any public disclosure.

## Scope

This policy applies to all repositories in the `tokentopapp` organization:

- `tokentop` — Core application
- `plugin-sdk` — Plugin development kit
- `agent-*` — Agent plugins (claude-code, opencode, cursor, windsurf, gemini-cli, antigravity)

## What to Report

- Authentication or authorization bypasses
- Credential exposure (API keys, tokens)
- Remote code execution
- Data exfiltration
- Dependency vulnerabilities with a known exploit

## What NOT to Report

- Issues that require physical access to a user's machine
- Social engineering attacks
- Denial of service (we're a local CLI tool)
- Issues in dependencies without a working exploit

## Supported Versions

We only support the latest released version of each package. Please update before reporting.
