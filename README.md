# PR OSS Skill

A portable Claude/Codex skill for concise, evidence-grounded pull request descriptions. It leads with purpose and the core decision, preserves relevant compatibility and validation information, and uses only the sections the PR needs.

## Use

1. Download [SKILL.md](SKILL.md), or extract the repository ZIP.
2. In your existing approved Claude/Codex session, ask: “Read SKILL.md and prepare a PR description using this approved diff, intent, and repository template.”
3. Review the result before publishing. The skill grants no new permission to change code, split commits, publish, or merge.

The single SKILL.md file is sufficient. No Python, Git, local model, API key, telemetry, or native installation is required. Keep your company's approved provider and data boundaries; do not send restricted data to an unapproved session. Existing adequate descriptions may remain unchanged. Migration bullets apply when there is a breaking change; three fixed sections are not required.

## Version, license, and source

Version: [2.2.0](VERSION). License: [MIT](LICENSE); canonical license text: [Open Source Initiative](https://opensource.org/license/mit).

This package contains original PR OSS skill text. Its minimal structure was informed by [Ponytail](https://github.com/DietrichGebert/ponytail), licensed under [MIT](https://github.com/DietrichGebert/ponytail/blob/main/LICENSE). No third-party code or skill text is bundled.
