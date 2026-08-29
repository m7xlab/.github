# Contributing to m7xlab projects

Thanks for your interest in contributing! 🎉

We welcome bug reports, feature requests, documentation improvements, and pull
requests across our public repositories. This document captures the workflow we
prefer — it keeps reviews fast and the history clean.

## 🐛 Reporting bugs

Open an issue on the relevant repository using the **Bug report** template. If
you're not sure which repo, drop a note at [hello@m7xlab.top](mailto:hello@m7xlab.top)
and we'll route it.

Please include:

- A clear, descriptive title
- Steps to reproduce (or a minimal failing snippet / log)
- Expected vs. actual behavior
- Environment (OS, runtime version, dependency versions)
- Any relevant screenshots or traces

## ✨ Suggesting features

Open an issue using the **Feature request** template. Describe the problem the
feature would solve, the proposed shape, and any alternatives you've considered.

## 🔧 Submitting a pull request

1. **Open an issue first** for non-trivial changes so we can agree on the
   approach before code is written.
2. Fork the repository and create a feature branch:
   ```bash
   git checkout -b feat/short-descriptive-name
   ```
3. Keep commits small and focused. Use [Conventional Commits](https://www.conventionalcommits.org/)
   for messages (`feat: …`, `fix: …`, `docs: …`, `chore: …`).
4. Add or update tests for any behavior change.
5. Run the project's lint / typecheck / test suite locally before pushing.
6. Push your branch and open a PR. Fill in the PR template; link the related
   issue with `Closes #123`.
7. Respond to review feedback — small, follow-up commits are fine.

## 🧪 Local development

Each repo has its own README with setup instructions. Most use Node.js ≥ 22 or
Python ≥ 3.11. If you hit setup trouble, open an issue — we'd rather fix the
docs than have you stuck.

## 📜 License

By submitting a contribution, you agree that your contributions will be
licensed under the same license as the repository you're contributing to (usually
MIT). You also confirm you have the right to submit the work.

## 🤝 Code of Conduct

Participation is governed by our [Code of Conduct](./CODE_OF_CONDUCT.md). By
participating, you agree to abide by its terms.

## 💬 Questions?

[hello@m7xlab.top](mailto:hello@m7xlab.top)
