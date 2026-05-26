# Contributing to BlackBox

Thanks for considering a contribution. Whether it's a bug report, a feature idea, a doc fix, or a pull request — it's appreciated.

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By participating you agree to uphold it.

## Development setup

BlackBox is a **single-file HTML app**. There is no build step.

```bash
git clone https://github.com/aim-gas/BlackBox.git
cd BlackBox
python3 -m http.server 8000
# → open http://localhost:8000
```

Just edit `index.html` and refresh.

## Code style

- **No frameworks, no build tools.** Keep it vanilla JS / CSS / HTML.
- **No npm dependencies.** All libraries load from CDN, pinned to specific versions.
- Use the existing module pattern: `const ModuleName = { method() { … } }`.
- Match the existing CSS-variable-driven theming (`var(--accent)`, `var(--card)`, etc.).
- Don't introduce a backend, telemetry, or any outbound request unless the user explicitly enabled it.

## Pull request checklist

- [ ] PR title concise and descriptive
- [ ] Tested in Chrome and Firefox
- [ ] No new outbound network calls without explicit user opt-in
- [ ] No new npm dependencies
- [ ] `index.html` opens cleanly with no console errors
- [ ] Existing features still work

## Reporting security issues

**Please do not file public issues for security vulnerabilities.** See [SECURITY.md](SECURITY.md).

## Licence

By contributing, you agree your contributions are licensed under [MIT](LICENSE), and respect the [trademark policy](TRADEMARKS.md).
