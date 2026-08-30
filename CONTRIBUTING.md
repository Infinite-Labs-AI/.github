# Contributing to Infinite Labs AI projects

Thank you for contributing. This file provides organization defaults; a repository's own `CONTRIBUTING.md`, `AGENTS.md`, README, and test instructions take precedence.

## Before opening a pull request

1. Read the target repository's setup, architecture, safety, and contribution instructions.
2. Fork or branch from the current default branch and keep the change focused.
3. Add or update tests for behavior changes.
4. Run the repository's documented formatter, lint, type, test, and build checks.
5. Explain what changed, why it changed, and the exact verification you ran.

Keep unrelated refactors out of the same pull request. Preserve compatibility and data-safety boundaries unless the change explicitly reviews them.

## Secrets and private data

Never commit credentials, tokens, `.env` files, private keys, customer data, personal health data, private browser/session state, or private repository content. Use documented fixtures and synthetic examples.

## Security reports

Do not use a public issue or pull request to disclose a vulnerability. Follow the private process in [SECURITY.md](SECURITY.md).

## Reviews and conduct

Maintainers may ask for narrower scope, additional evidence, or changes required by a repository's public contract. Participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
