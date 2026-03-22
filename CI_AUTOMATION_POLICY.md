# CI/CD Automation Policy

To ensure code quality and consistency, all linting, formatting, and tests must run in CI/CD (not just locally).

## Recommendations
- Use GitHub Actions, GitLab CI, or your preferred CI/CD tool.
- Run `npm run lint`, `npm run format`, and `npm test` on every PR.
- Block merges if checks fail.
- Document your CI/CD setup in README.md or docs/.

---

If you need a starter GitHub Actions workflow, let me know!