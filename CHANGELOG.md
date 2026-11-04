# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-11-04

### Added
- Claude Code plugin packaging: `.claude-plugin/plugin.json` and `marketplace.json`. Install with
  `/plugin install chanmeng-academic-paper-review --marketplace ChanMeng666/chanmeng-academic-paper-review`. The repo, marketplace, plugin and skill all
  use the name `chanmeng-academic-paper-review`. The manual `git clone` install still works as before.
- CI runs `claude plugin validate --strict` on the manifests.

### Added
- Standard community-health documentation (`CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`, `GOVERNANCE.md`, this changelog).

## [0.1.0]

### Added
- Initial documented release of Academic Paper Review Skill.
