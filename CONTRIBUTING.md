# Contributing to Kabuk

Thanks for wanting to help. Kabuk is early, so the best first step is to open an issue and talk
before writing a large change.

## Before you start

- Check existing issues to avoid duplicates.
- For anything bigger than a small fix, describe what you want to do and wait for a reply.
- You need to agree to the [CLA](CLA.md) before we can merge your first pull request.

## Working on code

- JavaScript projects use bun, not npm.
- Rust code is formatted with `cargo fmt` and must pass `cargo clippy -- -D warnings`.
- Every change needs tests. Coverage is held at 100% and CI fails below that.
- User-facing text must exist in English, Turkish, Kazakh and Russian.
- Commit messages follow Conventional Commits (`feat:`, `fix:`, `docs:` and so on). Releases are
  generated from them.

## Pull requests

Keep them focused. Say what changed and why. Make sure CI is green.

## Licensing

The open repositories are GPLv3. Enterprise server code is closed source and is not part of these
repositories.

## Conduct and security

Be kind, see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Report vulnerabilities privately, see
[SECURITY.md](SECURITY.md).
