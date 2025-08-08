# AGENTS.md

## Environment
- Build command: `JEKYLL_ENV=development bundle exec jekyll build`
- Serve command (for manual checks): `bundle exec jekyll serve --host 0.0.0.0 --port 4000`
- Test/verify: ensure `_site` is generated and no build errors.

## Tasks for Codex
- When asked to “run the site”, execute the build command above.
- If `serve` is requested, start the server and provide the terminal output/URL.
- When modifying config or content, re-run the build and include the last ~50 lines of build logs in the result.

## Notes
- Use the existing `Gemfile` and `Gemfile.lock` (do not upgrade gems unless requested).
- For GitHub Pages parity, keep `github-pages` pinned.
