# Contributing to Pacta Protocol

Welcome, and thank you for helping build Pacta — open trust infrastructure that lets AI
agents safely discover, contract, escrow, verify, and pay real businesses.

These guidelines apply to **every repository in the [Pacta-Protocol](https://github.com/Pacta-Protocol)
organization**. Individual repositories may add their own `CONTRIBUTING.md` with
setup and testing details specific to that codebase — read that too when it exists.

## Ways to contribute

- **Report a bug** — open an issue with steps to reproduce.
- **Suggest an idea** — open an issue or a [Discussion](https://github.com/orgs/Pacta-Protocol/discussions).
- **Improve docs** — small fixes can go straight to a pull request.
- **Write code** — see the flow below.
- **Report a vulnerability** — do **not** open a public issue; follow
  [SECURITY.md](SECURITY.md).

## Before you start

- **Search first.** Check open issues and Discussions so we don't duplicate work.
- **Open an issue for anything non-trivial** before writing code, so the approach can
  be agreed on before you spend time on it. Small, obvious fixes can skip this.
- Contributions to the **protocol itself** follow a proposal process — see the
  `GOVERNANCE.md` in the [Pacta.Protocol](https://github.com/Pacta-Protocol/Pacta.Protocol)
  repository.

## The pull-request flow

1. **Fork** the repository (or branch, if you have write access).
2. Create a branch off `main` with a descriptive name.
3. Make your change. Keep it **small and focused** — one concern per pull request.
4. **Run the repository's tests** and make sure they pass. If you change behaviour, add
   or update a test.
5. Write clear commit messages. Describe *what* changed and *why*.
6. **Sign off** your commits (see below).
7. Open the pull request against `main` and fill in the template. Link the issue it
   closes.
8. A maintainer reviews. Address feedback by pushing more commits to the same branch.

## Developer Certificate of Origin (sign-off)

Pacta uses the [Developer Certificate of Origin](https://developercertificate.org/) —
a lightweight statement that you have the right to submit your contribution under the
project's license. There is no CLA and no external tooling.

Add a sign-off line to every commit:

```bash
git commit -s -m "Your message"
```

This appends `Signed-off-by: Your Name <your@email>` using your git identity, which
certifies the DCO.

## Style

Write code that reads like the code around it — match the existing naming, comment
density, and idioms of the file you're editing. Prefer small, readable changes over
broad rewrites.

## Code of Conduct

Participation in Pacta is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By
taking part, you agree to uphold it.

## License

Unless a repository states otherwise, contributions are accepted under that
repository's license (MIT). By contributing, you agree your work is licensed under it.
