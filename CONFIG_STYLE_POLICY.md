# Config and Style Consolidation Policy

To avoid confusion and drift:

- Use a single source of truth for each config (e.g., one .eslintrc.js, one .prettierignore, one style.css per app).
- Document which config/style files are authoritative in README.md.
- Remove or archive unused/duplicate configs and styles.
- For shared styles, use imports or symlinks instead of copies.

---

Review your configs/styles regularly!