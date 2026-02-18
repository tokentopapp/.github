# Contributing to tokentop

Thanks for your interest in contributing! This guide applies to all repos in the `tokentopapp` organization.

## Getting Started

1. Fork the repo
2. Clone your fork
3. Create a branch: `git checkout -b feat/my-feature`
4. Install dependencies: `bun install`
5. Make your changes

## Development

All projects use [Bun](https://bun.sh/) as the runtime and package manager.

```bash
bun install          # Install dependencies
bun run build        # Build
bun test             # Run tests
bun run typecheck    # Type checking
```

## Commit Messages

We use [Conventional Commits](https://www.conventionalcommits.org/). Every commit and PR title must follow the format:

```
type(scope): description
```

**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, `revert`

**Examples:**
- `feat(dashboard): add cost breakdown chart`
- `fix(agent): handle missing API key gracefully`
- `docs: update plugin SDK getting started guide`

## Pull Requests

1. Keep PRs focused — one feature or fix per PR
2. Fill out the PR template completely
3. Ensure CI passes before requesting review
4. Link related issues

## Reporting Issues

- **tokentop core or general bugs**: File on [tokentopapp/tokentop](https://github.com/tokentopapp/tokentop/issues)
- **Plugin SDK issues**: File on [tokentopapp/plugin-sdk](https://github.com/tokentopapp/plugin-sdk/issues)
- **Agent plugin issues**: Use the issue redirect in the agent repo — it will route you to the correct place with the right labels

## Code Style

- TypeScript strict mode
- No `any` types, `@ts-ignore`, or `@ts-expect-error`
- Follow existing patterns in the codebase

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
