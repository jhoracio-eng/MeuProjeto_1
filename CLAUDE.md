# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository overview

This is a minimal static site consisting of a single self-contained file, `index.html`. There is no build system, package manager, framework, or test suite — all HTML, CSS, and JavaScript live inline in that one file.

## Running the site

Open `index.html` directly in a browser, or serve the directory with any static file server (e.g. `python -m http.server`) if browser access to `file://` needs to be avoided.

## Notes for editing

- Content is in Brazilian Portuguese (`lang="pt-BR"`).
- Keep styles and scripts inline in `index.html` unless the project grows enough to justify splitting into separate files.
