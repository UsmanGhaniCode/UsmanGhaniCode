# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a GitHub **profile repository** (`UsmanGhaniCode/UsmanGhaniCode`): its `README.md` is rendered on the owner's GitHub profile page. There is no code, build system, linter or test suite; the only content is `README.md`.

## Working on the README

- Rendering target is GitHub-flavored Markdown on github.com. Centered sections use raw HTML (`<h1 align="center">`, `<p align="center">`) because Markdown alone can't center; keep that pattern rather than converting to plain Markdown.
- Tech-stack badges are `shields.io` images (`https://img.shields.io/badge/<label>-<hex>?style=flat-square&logo=<slug>`). Header link buttons use `style=for-the-badge`. In badge labels, `-` must be written `--`, `_` renders as a space, and other special characters are URL-encoded (`%23` for `#`, `%2F` for `/`, `%26` for `&`).
- The "AI in games" badges share the accent color `7c6cff`, which also matches the Portfolio button.
- GitHub stats cards come from `github-readme-stats.vercel.app` with `theme=tokyonight&hide_border=true`.
- Project links in "Featured work" point to the portfolio at `https://usmanghani.soargamesstudio.com/project.html?id=<slug>`; open-source repos link to `https://github.com/UsmanGhaniCode/<Repo>`. Only link projects and repos that actually exist (an earlier commit replaced placeholder links with real ones).
- To preview, push to a branch and view the file on GitHub; there is no local render step.
