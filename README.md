# Defaults for every repository on this account

GitHub reads this repository for *default community health files*. Any repository owned by
`MrYaz` that does not carry its own copy of one of these files falls back to the copy here —
including private repositories, and including repositories created in the future. Nothing has
to be copied into a new project for it to pick these up.

| File | What it does |
| --- | --- |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | Pre-fills the description box of every new pull request. |

## Why this repository is public

GitHub requires it: *"A repository for default files cannot be private."* Nothing private lives
here — only the template text above. Every actual project stays private.

## Changing a template

Edit the file here and the change applies everywhere at once. To let one project differ, commit
a file of the same name into that project; its own copy wins over the default.

## What this account cannot enforce

Branch protection and rulesets — blocking direct pushes to `main`, requiring a pull request or a
green check before a merge — need GitHub Pro on private repositories. On the current plan the
API answers `Upgrade to GitHub Pro or make this repository public to enable this feature.`
So the pull request flow here is a convention, not a gate.
